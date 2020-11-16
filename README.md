# Protheus_Docker
Base de testes docker para testes

## 1.passo

criar as seguintes pastas 

na raiz do projeto **protheus_volume** dentro de protheus_ volume criar as seguintes pastas **apo** e **protheus_data**
e dentro de protheus_data criar as seguintes pastas **Semaforo** , **System**, **Systemload** no final deverá ficar da seguinte forma

totvs_volume
1. apo
 
2. protheus_data> Semaforo, System, Systemload 


####  os requisitos do projeto a serem baixados e instalados 

 * [INCLUDES](https://drive.google.com/file/d/1o8ImkYeScKMo0-mB5Lv5282KaXy293Je/view?usp=sharing)
 * [RPO](https://drive.google.com/file/d/1k3HtR_8sS-SAg2O6ABfJVILQwRVlVTzi/view?usp=sharing)
 * [WSL](https://docs.microsoft.com/pt-br/windows/wsl/install-win10)
 * [DOCKER](https://www.docker.com/products/docker-desktop)
 * [DataPlus](https://tableplus.com/windows)
 * [GIT](https://git-scm.com/downloads) 

## 2. passo configuração

apos baixar todos os requisitos e criar as pastas no diretorio do projeto agora vamos colocar o rpo em sua devido lugar

descompacte o RPO o arquivo tera este nome **tttp120.rpo** ele deverá ser colocado na pasta que criamos **apo**


## 3. passo subindo base

1. 
o arquivo **.env.sample** e onde estão as configuraçoes das bases caso queira mudar, caso não o nome do arquivo deve ser alterado ficando apenas **.env** 

2. 
com o docker instalado e aberto, agora devemos abrir o powerShell no diretorio do projeto e vamos executar deste comando **docker-compose up** assim começara a baixar todas as dependencias do projeto.


## 4. conexoes ao banco e protheus


1. Conexao ao banco
* Banco: Protheus_advpl_2
* Host: http://localhost
* port: 5432
* user: protheus
* password: protheus
* database: protheus

2. conexão protheus
* protheus web: http://localhost:8080
  
3. smartclient
* programa inicial: SIGAMDI
* comunicação do cliente: tcp
* amebiente no servidor: teste





















