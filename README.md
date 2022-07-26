![Datahub](logo_dh.png)

## Teste de avaliação para seleção de Engenheiro de Dados 

### Introdução

Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo para a vaga de Engenheiro de Dados. Antes de iniciar, esteja em um ambiente tranquilo e confortável, pense no problema e na melhor forma de resolvê-lo.
O nosso objetivo com este desafio é medir o seu conhecimento técnico de engenharia de dados, por isso não vamos estabelecer nenhum tipo de restrição sobre padrões de projeto, organização de código e boas práticas. Realize o teste usando técnicas que você já conhece e tem segurança. Podemos lhe questionar sobre a sua solução durante a entrevista.

### Questionário

Edite este documento e descreva um pouco sobre a sua experiência nas tecnologias abaixo:

***
* Python -
***
* Spark -
***
* Airflow -
***
* Banco de dados relacionais ( qual ? ) -
***
* Banco de dados NoSQL ( qualquer ) -
***
* Cloud -
***

### Desafio técnico

Pré-requisitos: Docker

Faça um fork do projeto para um repositório público do seu Github.

Nele contém o arquivo docker-compose.yaml que cria o ambiente no Docker, necessário para realizar o desafio. Fique a vontade para fazer alterações.

Use o comando abaixo na pasta do projeto para subir o ambiente:
```console
~$ docker compose up .
```

Considere o dataset abaixo:<br>
<br>
**Dados Cadastrais dos Revendedores Varejistas de Combustíveis Automotivos**

**Link para download**: [https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/arquivos/arquivos-dados-cadastrais-dos-revendedores-varejistas-de-combustiveis-automotivos/dados-cadastrais-revendedores-varejistas-combustiveis-automoveis-1.csv](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/arquivos/arquivos-dados-cadastrais-dos-revendedores-varejistas-de-combustiveis-automotivos/dados-cadastrais-revendedores-varejistas-combustiveis-automoveis-1.csv)

Crie um pipeline no Airflow para realizar o download e carga do dataset em uma tabela ( criar tabela ) do PostgreSQL.

O pipeline deve conter as seguintes etapas:

* Download do arquivo 
* Tratamento / higienização - Remoção de acentuação do atributo **RAZAOSOCIAL**. Pode realizar outros tratamentos se achar necessário.
* Ingestão dos dados no PostgreSQL
* Validação - Verificar se a quantidade de registros inseridos na tabela é igual a quantidade de linhas do arquivo original.


---

### Save a sua DAG do Airflow no repositório e envie o link para o recrutador



