---
title: Diretriz de exportação de dados do ciclo de vida
description: Diretriz de exportação de informações sobre o ciclo de vida do produto
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546738"
---
# <a name="lifecycle-data-export-guidance"></a>Diretriz de exportação de dados do ciclo de vida
Este documento descreve como usar o arquivo de exportação do produto.

## <a name="query-information"></a>Informações das Consultas
No documento do Excel, há campos para ajudar a identificar os dados preenchidos na tabela do produto.

### <a name="end-of-support"></a>Fim do Suporte
O valor de fim do suporte filtrará os produtos pela data de término do suporte do produto ou pelas datas de término do lançamento.

Valores possíveis: Todos (sem filtro aplicado), Ano e Intervalo.

### <a name="family"></a>Família
O valor da família filtra os produtos por seu nível pai dentro da hierarquia conhecida como família.

Valores possíveis: Todos (sem filtro aplicado), Nome da Família

### <a name="group"></a>Group
O valor do grupo filtra produtos em seu nível pai (família) para um grupo específico.

Valores possíveis: Todos (sem filtro aplicado), Nome do Grupo

## <a name="table-columns"></a>Colunas de Tabela
A tabela do produto consiste em colunas que definem o produto, edições, versões e datas de suporte correspondentes.

> [!NOTE]
> Haverá uma linha para cada combinação de produto, edição e versão.

### <a name="product"></a>Produto
O nome do produto.

### <a name="edition"></a>Edição
A coluna de edição será preenchida quando o produto contiver edições. Quando não houver nenhuma edição do produto, esse campo ficará em branco.

### <a name="release"></a>Liberar
A coluna de versão será preenchida quando o produto contiver várias versões.
Quando o produto tiver apenas uma versão, esse campo ficará em branco.

### <a name="support-policy"></a>Política de Suporte
Este campo define qual política de suporte o produto segue.

Valores possíveis: [Fixo,](/lifecycle/policies/fixed) [Moderno](/lifecycle/policies/modern), Componente

### <a name="start-date"></a>Data de Início
Suporte de data iniciado para o produto.

### <a name="mainstream-date"></a>Data Base
Quando a Política de Suporte é **Fixa** ou **Componente**, esta é a data de término base do produto.
  
Quando a Política de Suporte é **Moderna,** o valor fica em branco.

### <a name="extended-end-date"></a>Data de Término Estendida
Quando a Política de Suporte é **Fixa** ou **Componente**, essa é a data de término estendida do produto.

Quando a Política de Suporte é **Moderna,** o valor fica em branco.

### <a name="retirement-date"></a>Data da Aposentadoria
Quando a Política de Suporte é **Fixa** ou **Componente**, o valor fica em branco.

Quando a Política de Suporte é **Moderna**, essa é a data de aposentadoria do produto.

### <a name="release-start-date"></a>Data de Início da Versão
Data em que o suporte iniciou para a versão. Quando o produto tiver apenas uma versão, esse campo ficará em branco.
 
### <a name="release-end-date"></a>Data de Término da Versão
Data em que o suporte terminou para a versão.
Quando o produto tiver apenas uma versão, esse campo ficará em branco.

### <a name="docs-url"></a>Url dos Documentos
Url para a documentação estendida.
