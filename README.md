<p><img src="https://user-images.githubusercontent.com/63436406/129230824-6a4e2b32-3e83-4a95-8f7b-ce4322270731.png" align="left" height="150px" width="150px">
    <h1># Criando um Ecossistema Hadoop Totalmente Gerenciado com Google Cloud Dataproc</h1> 
    <p align="justify">

Código criado para utilização junto a plataforma da Digital Innovation One

## Desafio GCP Dataproc

O desafio faz parte do curso na plataforma da Digital Innovation One:

__*Criando um ecossitema Hadoop totalmente gerenciado com Google Cloud Platform*__

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contahem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

---

### Etapas do Desafio

1. Criar um bucket no Cloud Storage
1. Atualizar o arquivo ```contador.py``` com o nome do Bucket criado nas linhas que contém ```{SEU_BUCKET}```.
1. Fazer o upload dos arquivos ```contador.py``` e ```livro.txt``` para o bucket criado (instruções abaixo)
    - https://cloud.google.com/storage/docs/uploading-objects

1. Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando ```gs://{SEU_BUCKET}/contador.py```
1. O Job irá gerar uma pasta no bucket chamada ```resultado```. Dentro dessa pasta o arquivo ```part-00000``` irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

### Entrega do Resultado

1. Criar um repositório no GitHub.
2. Criar um arquivo chamado ```resultado.txt```. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
3. Inserir os arquivo ```resultado.txt``` e ```part-00000``` no repositório e informar na plataforma da Digital Innovation One.

---

### Considerações Finais

NOTA: Se o Job mostrar um WARN de Interrupt, basta ignorar. Existe um bug no Hadoop que é conhecido. Isso não impacta no processamento.

   </p>
</p>      

---

<br>
    <code><a href="https:/discord.com">
        <img src="https://img.shields.io/badge/Léo Albergaria%20-%237289DA.svg?&style=for-the-badge&logo=discord&logoColor=white" /></a></code>
    <code><a href="https://www.linkedin.com/in/adm-leo-albergaria/">
        <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a></code>
<br>     

<a href="https://www.digitalinnovation.one/">
    <img src="https://user-images.githubusercontent.com/63436406/127776292-9ec4809a-1137-4dc8-b493-7de0186fd55c.png" align="right" height="80px" width="250px" ></a>
