# Seja bem-vindo a Branch MASTER
```
Repositório para armazenar e compartilhar desenvolvimentos de Projetos.
```

# Projetos Protheus
```
Repositório para armazenar e compartilhar desenvolvimentos de Projetos.
```
## Liguagens
```
Repositorio para armazenar códigos e projetos internos do departamento de TI para o ERP Totvs Protheus.
```
 - [X] ADVPL
 - [X] TL++
 - [X] PL-SQL
 - [X] T-SQL
 - [X] HTML5
 - [X] CSS
 - [X] JS


## Utilização Github on VsCode
```````
Estamos partindo do presuposto que você sabe usar o VsCode como compilador do ADVPL e possui a extenção do ADVPL instalada.
Sendo assim, vamos lá!
```````
1. Faça download do VsCode - https://code.visualstudio.com/download
2. Faça download do Git - https://git-scm.com/downloads
3. Instale os aplicativos no seu desktop
4. Crie uma pasta vazia no c:\Git
5. Crie uma conta no GitHub para obter um usuário - https://github.com/join
6. Abra o VsCode instale as seguintes extensões
```
 - Totvs Developer Studio
 - GitLens
 ```
7. - Clique em arquivo abrir pasta e selelcione a pasta "c:\git"
8. - Clique em Exibir>Terminal
9. - Execute os comandos em sequencia :
````````````
	git init
	git checkout -b develop 
	git clone https://github.com/bda-dev/advpl.git --branch develop
	git remote add origin https://github.com/bda-dev/advpl.git
	git config --global user.name "seu nome"
	git config --global core.email "seu email"
	git fetch
	git add *
	git commit -m "criado minha branch e iniciado o git"	
	git pull origin develop
 ````````````
 
## Utilização Github on VsCode
```
Outros comandos após alterações locais dos fontes, para salvar no Git local e enviar para nuvem.
```
- git add *	
```
Adiciona arquivo(s) e\ou pasta(s) criada(s)\modificada(s) no "container" local.
```
- git commit -m
```````
	"
	- Chamado: 41207 
	- Data...: 3.9.20 
	- Autor..: Bruno Abrigo 
	- Prolema: Descrição do Problema
	- Solucao: Descrição da solução
	"
```````
- git push origin develop
```
Envia atualizações para a nuvem(GitHub).
```
	
## PipeLine
```
Estrategia DevOps para automação continua e entrega continua.
```
 - [X] Manage Code
 - [X] Plann
 - [X] Develop
 - [X] Verify
 - [X] Package version
 - [X] Release
 - [X] Configure
 - [X] Deploy
 - [X] Monitor

## FlowProcess | Events
```
- Scrum
- Create Backlog
- Planning
- Daily
- Sprints
- Review
```
![scrum](https://github.com/bda-dev/sices-dev/blob/master/scrum.png)

## Envolvidos
```
- Key-User
 - TeamScrum
   - IT Manager 
   - Analysts
   - Developers
   - Q.A
   - Coordinator
```

## Gestao Fontes | Repositorio Master
``````
- Armazenamos aqui os fontes desenvolvidos em equipe.
 - Utilize brachs com seu nome e ao final será realizado um merge para fundir sua ramificação paralela ao projeto Master.
 ``````
![gitflow2](https://github.com/bda-dev/sices-dev/blob/master/gitflow2.png)

## Gestão de Branches
```
- Como funciiona ?
 ```
 - [ ] **Branches**
   
   - [ ] Master
   
    - __contém o nosso código de produção, todo o código que estamos desenvolvendo, em algum momento será “juntado” com essa branch.__
    
   - [ ] Develop
   
    - __contém o código do nosso próximo deploy, isso significa que conforme as features vão sendo finalizadas elas vão sendo juntadas nessa branch para posteriormente passarem por mais uma etapa antes de ser juntada com a master__
   
   - [ ] HotFix
   
    - __São branches responsáveis pela realização de alguma correção crítica encontrada em produção e por isso são criadas à partir da master. Importante ressaltar que essa branch deve ser juntada tanto com a master quanto com a develop__
   
   - [ ] Feature
   
    - __são branches para o desenvolvimento de uma funcionalidade específica, por convenção elas tem o nome iniciado por feature/, por exemplo: feature/cadastro-usuarios. Importante ressaltar que essas branches são criadas sempre à partir da branch develop__
   
   - [ ] Release
   
    - __tem uma confiança maior que a branch develop e que se encontra em nível de preparação para ser juntada com a master e com a develop (caso alguma coisa tenha sido modificada na branch em questão)__
    
![gitflow](https://github.com/bda-dev/sices-dev/blob/master/gitflow.png)

## Kanban
```
- Utilize o Kanban em projects para visualizar os projetos.
```
## Idealizador 
```
@BrunoDaniel
```
## Contribuintes 
``````

``````
![giphy](https://github.com/bda-dev/sices-dev/blob/master/giphy.gif)

## Motivando em 3,2,1..
```
1. “Um bote não vai para frente se cada um rema à sua própria maneira”
2. “A felicidade no trabalho consiste no resultado de se aprender a trabalhar em equipe”
3. “Eu faço o que você não pode, e você faz o que eu não posso. Juntos podemos fazer grandes coisas”
 ```
