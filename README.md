# Instruções Git
Um guia com instruções básicas do Git

## Índice
- [Como instalar o Git no Ubuntu](#como-instalar-o-git-no-ubuntu)


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
