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
#!/bin/bash

echo "Atualizando o servidor..."
apt-get update
apt-get upgrade -y
apt-get install apache2 -y
apt-get install unzip -y


echo "Baixando e copiando os arquivos da aplicação..."

cd /tmp
wget https://github.com/denilsonbonatti/linux-site-dio/archive/refs/heads/main.zip
unzip main.zip
cd linux-site-dio-main
cp -R * /var/www/html/
</p>



