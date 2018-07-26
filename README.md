Projeto de Mineração de Dados
==========================

Repositório para o projeto da disciplina de Mineração de Dados da UFABC pós Ciência da Computação

# Instalação

Instalar o [git](https://git-scm.com/), se ainda não tiver.

Depois, clonar este reposório com os seguintes comandos:

    $ cd $HOME  # ou a pasta de preferência
    $ git clone https://github.com/flaviajanine/MD-audio-classify.git
    $ cd MD-audio-classify

Se não quiser baixar o git, pode simplesmente baixar o arquivo zip [master.zip](https://github.com/flaviajanine/MD-audio-classify/archive/dev.zip), descompactar e mover `MD-audioclassify` para o diretório de sua preferência.

## Python & Bibliotecas Necessárias

Instalar Python, muito importante que seja versão 3.

    $ python3 --version  # for Python 3

    $ sudo apt-get update
    $ sudo apt-get install python3

Depois instalar os requirements deste projeto com:

    $ pip3 install --upgrade -r requirements.txt

## Iniciando Jupyter

Iniciar o Jupyter notebook com o comando:

    $ jupyter notebook
    
Abrir o notebook com o nome 'Classifier' onde estará todo o código da solução.