[GitHub repo size](https://img.shields.io/github/repo-size/AlanJoabio/DesafiodaDIO) 

<!--Banner session-->
<p align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo.png" alt="DIO" tittle="Digital Innovation One">
</p>

<!--Banner session-->
<p>
<h1 align="center">
Desafio de Projeto da DIO - Infraestrutura como Código - Script de Provisionamento de um Servidor Web (Apache)
</p>

<h2 align="center">
<p> Portfólio criado com o intuito de mostrar meus projetos ao decorrer da minha carreira, incluir  as atividades da Digital Innovation One.</p>

## Criado um arquivo Script.sh com orientação do [Prof. Denilson Bonatti](https://github.com/denilsonbonatti).

<p>
#!/bin/bash </p>

<p> echo "Atualizando o servidor..." </p>
<p> apt-get update </p>
<p> apt-get upgrade -y </p>
<p> apt-get install apache2 -y </p>
<p> apt-get install unzip -y </p>


<p> echo "Baixando e copiando os arquivos da aplicação..." </p>

<p> cd /tmp </p>
<p> wget https://github.com/denilsonbonatti/linux-site-dio/archive/refs/heads/main.zip </p>
<p> unzip main.zip </p>
<p> cd linux-site-dio-main </p>
<p> cp -R * /var/www/html/ </p>





