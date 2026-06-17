# Azure AI Search: Ingestão, Indexação e Consulta de Dados

## Descrição

Este repositório documenta a experiência prática realizada em um laboratório da DIO sobre organização de documentos, ingestão de dados, criação de índices inteligentes e exploração de informações utilizando recursos de inteligência artificial com o Azure AI Search.

O objetivo do laboratório foi praticar técnicas de organização, ingestão e pesquisa de documentos, compreendendo como os dados podem ser preparados, indexados, enriquecidos e consultados em uma solução de busca inteligente.

## Objetivos do laboratório

- Compreender o processo de ingestão de dados.
- Criar um índice de pesquisa.
- Explorar dados indexados.
- Entender o papel de data sources, indexers, indexes e skillsets.
- Documentar o processo técnico de forma clara.
- Utilizar o GitHub como portfólio técnico.

## Ferramentas utilizadas

- Microsoft Azure
- Azure AI Search
- Azure Portal
- Search Explorer
- GitHub
- Markdown

## Conceitos estudados

### Mineração de conhecimento

Mineração de conhecimento é o processo de extrair informações relevantes a partir de grandes volumes de dados, especialmente documentos, arquivos e conteúdos não estruturados. Com o Azure AI Search, esse processo pode ser apoiado por recursos de indexação, enriquecimento com IA e consultas inteligentes.

### Ingestão de dados

A ingestão de dados consiste em conectar uma fonte de dados ao serviço de pesquisa e preparar os conteúdos para serem processados. Essa etapa permite que documentos, registros ou arquivos sejam lidos e encaminhados para indexação.

### Índices de pesquisa

O índice de pesquisa é a estrutura responsável por armazenar os dados em um formato pesquisável. Ele define os campos disponíveis, os tipos de dados, os atributos de busca, filtros, ordenação e demais configurações necessárias para consultar as informações.

### Indexadores

Os indexadores automatizam o processo de leitura da fonte de dados e carregamento das informações no índice. Eles permitem executar a indexação de forma manual ou programada, mantendo os dados pesquisáveis atualizados.

### Skillsets

Skillsets são conjuntos de habilidades de enriquecimento aplicadas aos dados durante a indexação. Eles podem incluir extração de texto, reconhecimento de entidades, tradução, análise de imagens, detecção de idioma e outros recursos de inteligência artificial.

### Search Explorer

O Search Explorer é uma ferramenta do Azure Portal que permite testar consultas diretamente sobre um índice. Com ele, é possível validar os dados indexados, analisar retornos, testar filtros e compreender como a busca responde às consultas.

### Enriquecimento com IA

O enriquecimento com IA adiciona camadas de análise aos documentos durante o processo de indexação. Esse recurso ajuda a transformar dados brutos em informações mais úteis, estruturadas e fáceis de pesquisar.

### Pesquisa em documentos

A pesquisa em documentos permite localizar informações dentro de arquivos, relatórios, contratos, manuais e outros conteúdos textuais. Com índices bem configurados, é possível realizar consultas mais rápidas, organizadas e relevantes.

## Etapas realizadas

- Acesso ao portal do Azure.
- Criação ou acesso ao serviço Azure AI Search.
- Configuração da fonte de dados.
- Processo de ingestão de dados.
- Criação do índice.
- Configuração do indexador.
- Execução da indexação.
- Exploração dos dados pelo Search Explorer.
- Análise dos resultados obtidos.

## Estrutura conceitual do fluxo

```text
Documentos / Fonte de Dados
        ↓
Ingestão de Dados
        ↓
Indexador
        ↓
Índice de Pesquisa
        ↓
Consulta / Search Explorer
        ↓
Resultados organizados
```

## Exemplos de aplicação

- Pesquisa em documentos corporativos.
- Consulta em bases de conhecimento.
- Organização de arquivos institucionais.
- Busca em contratos, relatórios e manuais.
- Apoio a chatbots com dados internos.
- Mineração de conhecimento em grandes volumes de documentos.

## Prints

As capturas de tela do laboratório podem ser adicionadas na pasta `/images`, mantendo a documentação visual organizada junto ao projeto.

Exemplos de uso em Markdown:

```markdown
![Azure AI Search](images/azure-ai-search.png)
![Indice criado](images/search-index.png)
![Search Explorer](images/search-explorer.png)
```

## Insights adquiridos

- A ingestão de dados permite estruturar informações dispersas.
- O índice torna os documentos pesquisáveis.
- O indexador automatiza o processo de leitura e carregamento dos dados.
- O Search Explorer permite testar consultas diretamente no portal.
- O Azure AI Search pode ser usado como base para soluções com IA generativa e pesquisa corporativa.
- A organização correta dos campos melhora a qualidade das buscas.

## Possibilidades futuras

- Integrar Azure AI Search com aplicações web.
- Criar uma API para consultar documentos indexados.
- Usar Azure AI Search em soluções de RAG.
- Criar um chatbot com base em documentos internos.
- Aplicar busca semântica em documentos institucionais.
- Integrar com sistemas Java, Spring Boot ou Angular.

## Cuidados importantes

Ao preparar o projeto para publicação no GitHub, é importante não expor:

- chaves de API;
- tokens;
- strings de conexão;
- dados pessoais;
- documentos sensíveis;
- prints com informações privadas da conta Azure.

## Conclusão

O laboratório permitiu compreender como a ingestão, indexação e exploração de dados podem apoiar a mineração de conhecimento e a construção de soluções inteligentes. A experiência também demonstrou como o Azure AI Search pode ser aplicado em cenários corporativos para organizar documentos, facilitar consultas e servir como base para aplicações modernas com inteligência artificial.

## Autor

Autor: Lailton Alves da Costa Junior
