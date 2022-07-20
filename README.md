![Datahub](logo_dh.png)

## Teste de avaliação para seleção de Engenheiro de Dados 

### Introdução

Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo para a vaga de Engenheiro de Dados. Antes de iniciar, esteja em um ambiente tranquilo e confortável, pense no problema e na melhor forma de resolvê-lo.
O nosso objetivo com este desafio é medir o seu conhecimento técnico de engenharia de dados, por isso não vamos estabelecer nenhum tipo de restrição sobre padrões de projeto, organização de código e boas práticas. Realize o teste usando técnicas que você já conhece e tem segurança. Podemos lhe questionar sobre a sua solução durante a entrevista.

### Questionário

Edite este documento e descreva um pouco sobre a sua experiência nas tecnologias abaixo:

*Python -
<br>
*Spark -
<br>
*Airflow -
<br>
*Banco de dados relacionais ( qual ? ) -
<br>
*Banco de dados NoSQl ( qualquer ) -
<br>
*Cloud -

### Desafio

Faça um fork do projeto para um repositório publico do seu Github.

Nele contém o arquivo docker-compose.yaml que cria ambiente no Docker para realizar o desafio. Fique a vontade para editar caso necessário.

Use o comando abaixo na pasta do projeto para subir o ambiente:
```console
~$ docker compose up .
```

Considere o dataset abaixo:<br>
<br>
**Dados Cadastrais das Revendas de Gás Liquefeito de Petróleo (GLP)**

**Link para download**: [https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/arquivos/arquivos-dados-cadastrais-das-revendas-de-gas-liquefeito-de-petroleo-glp/cadastro-revendas-glp-1.csv](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/arquivos/arquivos-dados-cadastrais-das-revendas-de-gas-liquefeito-de-petroleo-glp/cadastro-revendas-glp-1.csv)

Crie um pipeline no Airflow para realizar a carga do dataset em uma tabela do PostgreSQL.

O pipeline deve conter uma etapa de tratamento para remover acentuações do atributo **RAZAOSOCIAL**. Pode realizar outros tratamentos se achar necessário.

##### Não há um prazo pré-estabelecido para a conclusão deste teste, porém o prazo utilizado será considerado para desempate

---

### Envie o link do repositório com a solução do problema para o recrutador.



