# Instruções Git
Um guia com instruções básicas do Git

## Índice
- [Como instalar o Git no Ubuntu](#como-instalar-o-git-no-ubuntu)
- [Configurações básicas do Git](#configurações-básicas-do-git)
- [Configurando a Autenticação do Git com Token no GitHub](#configurando-a-autenticação-do-git-com-token-no-gitHub)
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

3. Execute o comando abaixo para tornar a branch main como padrão:
```
git config --global init.defaultBranch main
```

## Configurando a Autenticação do Git com Token no GitHub
Para usar o Git e enviar suas alterações para o GitHub, é preciso se autenticar. Isso pode ser feito de duas maneiras: usando Tokens ou uma Chave SSH.
Os tokens são úteis porque podem guardar suas informações sem precisar salvar no servidor. Você pode configurá-los para ter as permissões que quiser e eles têm uma data de validade. Isso significa que param de funcionar depois de um tempo, como uma senha única que você usa só uma vez.

### Criando um Token
1. Faça login na sua conta [GitHub](https://github.com/)
2. 
