# Análise de Dados: Salários na Área de Dados

Este projeto envolve a análise de salários para cargos na área de dados, utilizando um dataset de salários e informações sobre profissionais da área de dados. O projeto inclui os seguintes passos:

## 1. Obtenção e Preparação dos Dados

- **Fonte dos Dados**: O dataset foi obtido no [Kaggle](https://www.kaggle.com/).
- **Mudanças Aplicadas**: Utilizando a biblioteca `pandas` em Python, renomeei as colunas, excluí os valores nulos e apliquei ajustes para deixar os dados mais coesos e utilizáveis.

### Exemplo de Mudanças Aplicadas:
- Renomeação de colunas para maior clareza (por exemplo, `nível_de_experiência` para `experiência`).
- Exclusão de valores nulos.

## 2. Criação do Banco de Dados MySQL

- Criei um banco de dados chamado `salarios_emprego` no MySQL Workbench.
- A tabela foi criada com os campos apropriados e os dados foram carregados utilizando Python e a biblioteca `SQLAlchemy`.

## 3. Carregamento de Dados para o Power BI

- Utilizei o conector **ODBC** para conectar o MySQL ao Power BI Desktop.
- Carreguei o banco de dados `salarios_emprego` e criei 4 gráficos em páginas diferentes no Power BI.

## 4. Gráficos Criados

### Página 1: Salário Médio por Cargo e Ano
- Gráfico de linhas mostrando a evolução do salário médio por cargo e ano para os cargos: **Data Scientist**, **Data Analyst** e **Data Engineer**.

### Página 2: Distribuição Geográfica dos Profissionais
- Gráfico de mapa de bolhas mostrando a distribuição de profissionais da área de dados pelo mundo.

### Página 3: Top 13 Países com os Melhores Salários
- Gráfico de barras mostrando os 13 países com os melhores salários médios para profissionais de dados.

### Página 4: Salário Médio por Tamanho da Empresa
- Gráfico de barras mostrando o salário médio por tamanho da empresa (Pequena, Média, Grande).

## 5. Como Reproduzir o Projeto

1. Baixe o dataset original de salários na área de dados no Kaggle.
2. Aplique as mudanças utilizando a biblioteca `pandas` conforme descrito.
3. Crie o banco de dados no MySQL e carregue os dados.
4. Conecte o MySQL ao Power BI através do conector ODBC.
5. Crie os gráficos no Power BI conforme descrito.

## 6. Requisitos

- **Python**: 3.12.7
- **Bibliotecas**: pandas, sqlalchemy, pymysql
- **MySQL Workbench**: Para criação do banco de dados
- **Power BI Desktop**: Para criação dos gráficos e dashboards
- **ODBC Driver**: Para conectar MySQL ao Power BI

## 7. Conclusão

Este projeto oferece uma análise interessante dos salários na área de dados e pode ser útil para profissionais da área que buscam entender melhor a distribuição salarial globalmente, com foco em cargos e modelos de trabalho.

## 8. Licença

Este projeto está licenciado sob a licença XYZ - consulte o arquivo LICENSE para mais informações.

