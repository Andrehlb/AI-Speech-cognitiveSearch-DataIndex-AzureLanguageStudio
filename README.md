# # Repositório em construção 🚧🏗️🚧

# Azure Cognitive Search e Speech Studio: Utilizando AI Search para Indexação e Consulta de Dados e Speech Studio para transcrição de texto a partir de voz.

## Introdução
Este documento fornece uma visão geral do uso do **Azure AI | Cognitive Search e do Speech Studio**, poderosas plataformas de pesquisa e de transcrever fala para texto com alta precisão, produzir texto com som natural para vozes de fala, traduzir áudio falado e usar o reconhecimento de alto-falante durante conversas, em tempo real ou de forma assíncrona com transcrição em lote, baseada em nuvem que utiliza recursos avançados de IA para indexar, pesquisar e analisar grandes volumes de conteúdo não estruturado.

## Características do Cognitive Search
- **Indexação Eficiente:** Automatize a indexação de dados com pipelines de ingestão configuráveis.
- **Pesquisa Inteligente:** Implemente funcionalidades avançadas como pesquisa semântica, correção automática e sugestões.
- **Análise Profunda:** Extraia insights valiosos dos seus dados com análises detalhadas.

## Conversão de voz em texto em tempo real
Com fala em texto em tempo real, o áudio é transcrito à medida que a fala é reconhecida a partir de um microfone ou arquivo. Use fala em tempo real para texto para aplicativos que precisam transcrever áudio em tempo real, como:

- Transcrições, legendas ou legendas para reuniões ao vivo
- Diarização
- Avaliação da pronúncia
- Agentes de contact center auxiliam
- Ditado
- Agentes de voz

### Pré-requisitos
- Assinatura do Azure
- Conhecimento básico em APIs RESTful

### Configuração Speech Studio
1. Crie um serviço do **Azure Speech Studio** no portal do Azure.

![Serviço de fala cognitivo do Azure AI](inputs/image/painel-SpeechCognitiveServices-AzureAI-SpeechStudio-MS.png)

2. Selecione o Recurso Criado.

![Painel de Criar Recursos](inputs/image/Painel-Recurso-Criar_Recurso_Voz.png)

OU

3. Na página Azure AI | Speech Studio, clique no símbolo da engranagem (posição superior direito) e selecione criar novo recurso caso não tenha recursos.

![Painel Speech Studio](inputs/image/painel-AzureAI-SpeechStudio-MS.png)

4. Selecione "criar novo recurso"

![Painel Definições - Speech Studio](inputs/image/Painel-Definicoes.png)

5. Adicone os dados coforme seespecificado e clique no botão "Criar recurso"

![Painel de Criar Novo Recurso](inputs/image/Painel-Recurso-Criar_Recurso_Voz.png)

6. Após o recurso criado, clique no botão azul "Utilizar recurso".

![Painel de Criar Recursos](inputs/image/Painel-Definicoes-nomeRecurso_Voz.png)

7. O painel Speech Studio Introdução a Voz se abrirá.

![Painel Speech Studio](inputs/image/painel-AzureAI-SpeechStudio-MS.png)

8. Role a página para baixo e selecione a transcrição de voz mais adeuqada para o teu projeto, neste projeto será selecionada a "Conversão de vom em tempo real". 

![Painel de Transcrições de Modelo de Voz](inputs/image/painel-transcricoesModeloDeVoz-SpeechStudio-MS.png)

9. No painel de Conversão de voz em texto em tempo real selecione o idioma para a conversão

![Painel Conversão de voz em texto em tempo real](inputs/image/painel-conversaoVozTextoTempoReal_US-SpeechStudio-MS.png)

10. Grave um aúdio para ser transcrito e faça o upload.

![]
()

3. Configure os índices e os pipelines de ingestão conforme necessário.

4. Use as APIs RESTful ou SDKs fornecidos pela Microsoft para integrar a pesquisa em seus aplicativos.

## Exemplos de Uso
Este repositório inclui exemplos detalhados sobre como configurar e usar o **Azure AI | Speech and Cognitive Search** para realizar tarefas complexas de reconhecimento de voz, pesquisa e análise.

## Contribuição
Sinta-se à vontade para contribuir com este projeto, fazendo pull requests ou abrindo issues.

## Licença 
Este projeto está licenciado sob o **MIT License** - veja o arquivo LICENSE.md para mais detalhes.

Fontes: <br>
(1) https://psiandresorayalima.blogspot.com/2012/04/entenda-o-que-ha-por-tras-das-picuinhas.... https://psiandresorayalima.blogspot.com/2012/04/entenda-o-que-ha-por-tras-das-picuinhas.html. <br>
(2) https://www.scielo.br/j/anp/a/VzDhbFWq4GPvYBbMcDzXYhJ. https://www.scielo.br/j/anp/a/VzDhbFWq4GPvYBbMcDzXYhJ/. <br>
(3) https://pressreleases.scielo.org/en/2020/11/25/eating-habits-personality-mood-and.... https://pressreleases.scielo.org/en/2020/11/25/eating-habits-personality-mood-and-headache-how-eating-disorders-can-relate-to-migraine/. <br>
(4) www.psicologiamsn.com/2014/09/as-5-fases-do-luto-ou-sobre-a-morte-de-elisabeth-kubler.... http://www.psicologiamsn.com/2014/09/as-5-fases-do-luto-ou-sobre-a-morte-de-elisabeth-kubler-ross.html. <br>
(5) https://www.neurounifesp.com.br/unidades-academicas/ambulatorio-de-avc-e-sono. https://www.neurounifesp.com.br/unidades-academicas/ambulatorio-de-avc-e-sono/. <br>
(6) Azure Cognitive Search: Utilizando AI Search para indexação e consulta .... https://github.com/lucslima96/Azure-AI-Search. <br>
(7) O que é a IA do Azure Search? - Cloud Adoption Framework. https://learn.microsoft.com/pt-br/azure/cloud-adoption-framework/innovate/best-practices/cognitive-search. <br>
(8) Introdução à Pesquisa de IA do Azure - Azure AI Search. https://learn.microsoft.com/pt-pt/azure/search/search-what-is-azure-search. <br>
(9) Azure-Cognitive-Search-Utilizando-AI-Search-para-indexação-e-consulta .... https://github.com/dansfisica85/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-dados. <br>
