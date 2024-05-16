# Instruções Git
Um guia com instruções básicas do Git

## Índice
- [Como instalar o Git no Ubuntu](#como-instalar-o-git-no-ubuntu)
- [Configurações básicas do Git](#configurações-básicas-do-git)
______________________________________________________________________

## Como Instalar o Git no Ubuntu
1. Abra o terminal (Ctrl + Alt + T) e execute o comando abaixo, que irá adicionar o PPA do Git aos repositórios APT do seu sistema Ubuntu, permitindo que você instale o Git mais recente via gerenciador de pacotes:
```
sudo add-apt-repository ppa:git-core/ppa
```
2. Em seguida, para garantir que o sistema tenha acesso às versões mais recentes dos pacotes disponíveis, execute a linha de comando:
```
sudo apt update
```
3. Por fim, instale o Git em sua máquina:
```
sudo apt install git
```

## Configurações Básicas do Git
1. No terminal, execute o comando abaixo para configurar globalmente o nome de usuário:
```
git config --global user.name SEUNOMEAQUI
```
Isso é útil para garantir que os commits feitos em todos os seus repositórios Git usem o mesmo nome de usuário.
2. Você pode também configurar um e-mail:
```
git config --global user.email EMAIL@EMAIL.COM
```
Isso é útil para garantir que as contribuições e atividades sejam atribuídas corretamente a você nos repositórios Git.
