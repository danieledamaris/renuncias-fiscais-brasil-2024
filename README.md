# 📊 Análise de Renúncias Fiscais no Brasil - 2024

Bem-vindo(a) ao meu primeiro repositório no GitHub! 🚀

Este projeto tem como objetivo analisar os dados abertos sobre as **Renúncias Fiscais** no Brasil referentes ao ano de 2024. Os programas de renúncia fiscal ocorrem quando o governo abre mão de receber parte dos impostos para estimular a economia, desenvolver regiões ou apoiar causas sociais e entidades não governamentais.

## 🎯 Objetivo do Projeto

Transformar dados brutos do governo em informações claras e visuais, entendendo para onde estão sendo direcionados os incentivos fiscais do país através de análise e visualização de dados **100% em Python**.

## 🛠️ Ferramentas Utilizadas

* **Python (Google Colab):** Utilizado para todo o ciclo de análise, desde a exploração inicial até a geração das visualizações interativas.
* **Pandas:** Biblioteca para manipulação, limpeza e estruturação dos arquivos CSV, com destaque para a função `groupby` na sumarização dos dados.
* **Plotly Express:** Biblioteca utilizada para a criação de gráficos interativos e dinâmicos, facilitando a interpretação dos indicadores financeiros.

## 📂 Estrutura do Repositório

O repositório contém os seguintes arquivos:

* `analise_renuncias_fiscais_2024.ipynb`: Notebook (Google Colab) contendo o código completo da análise exploratória, tratamento de dados e os gráficos interativos gerados.
* `2024_RenunciasFiscais.csv`: Primeira base de dados extraída do Portal da Transparência, com os dados gerais das renúncias.
* `2024_RenunciasFiscaisPorBeneficiario.csv`: Segunda base de dados, detalhando as renúncias por beneficiários.

## 📈 Etapas da Análise

1. **Extração:** Baixa das bases de dados em formato CSV diretamente do Portal da Transparência do Governo Federal.
2. **Análise Exploratória (Python):** Importação dos dados no Google Colab e utilização do Pandas para entender e organizar os montantes de renúncia agrupados por categorias relevantes (como por Unidade da Federação).
3. **Visualização de Dados (Python):** Construção de gráficos interativos no próprio notebook utilizando a biblioteca Plotly, visando facilitar a interpretação dos dados pelo público em geral de forma visual e clara.

## 📚 Referências Bibliográficas

* **Base de Dados Utilizada:** Portal da Transparência do Governo Federal - [Download de Dados: Renúncias](https://portaldatransparencia.gov.br/download-de-dados/renuncias)
* **Explicações Conceituais:** Portal da Transparência - [Entenda a Gestão Pública: Renúncias Fiscais](https://portaldatransparencia.gov.br/entenda-a-gestao-publica/renuncias-fiscais#:~:text=A%20ren%C3%BAncia%20fiscal%20ocorre%20quando%20o%20governo,setor%20privado%20ou%20por%20entidades%20n%C3%A3o%20governamentais)

---

Feito com dedicação por **Daniele Damaris Araujo** 👩‍💻. Conecte-se comigo e acompanhe minha jornada na análise de dados! [LinkedIn](https://wwww.linkedin.com/in/danieledamaris)

*Agradecimento especial ao professor **Mayko Costa** por todo incentivo e apoio na criação desse projeto. Este projeto é o Trabalho de Conclusão do Curso de Programação em Python para Ciência de Dados - SENAI Guarulhos Dutra - Abril/2026.*
