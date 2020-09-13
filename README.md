# Git-Github


![image](https://user-images.githubusercontent.com/62863159/93007351-8f596780-f53e-11ea-8e5c-68f169d72f66.png)

![image](https://user-images.githubusercontent.com/62863159/93007354-97190c00-f53e-11ea-9928-65d753b03285.png)


<h2>Comandos Básicos do Github</h2>

`git init`
(inicialização um respositório local)

`git clone <URL para o repositório remoto>`
(inicialização um git local que referência um repositório remoto)


![image](https://user-images.githubusercontent.com/62863159/93007346-810b4b80-f53e-11ea-8429-69f83f8e8b00.png)


<h2>Adicionar</h2>

`git add <Arquivo>`
(Adicionar mudanças “Adicionar o Index” )

`git  add  .`
( Adicionar todas as mudanças na pasta local )

`git add  -A`
( Adicionar todas as mudanças feitas )

`git reset  `
`git reset<arquivo>`
( É possível desfazer o add “remover o index”  )

![image](https://user-images.githubusercontent.com/62863159/93007389-05f66500-f53f-11ea-8c93-f0c5e8331af0.png)


<h2>Fluxo de Trabalho</h2>

![image](https://user-images.githubusercontent.com/62863159/93007398-1575ae00-f53f-11ea-818d-80f8dd13cd2e.png)


<h2>Diferenciar as modificações</h2>

`git status`
( Verifica o status atual da pasta )

`git diff  <index>`
( Mostra as diferenças alteradas nos arquivos )


Edições de arquivo, adição/ exclusão.
São consideradas mudanças, mas listadas de forma 
diferente

![image](https://user-images.githubusercontent.com/62863159/93007429-62f21b00-f53f-11ea-945e-9a11aa1fc875.png)

<h2>Confirmar Mudanças</h2>

Após isso para confirmar suas mudanças enviadas para o Head

`git commit -m “comentário de alteração”`

`git commit -am “comentário de alteração”`

( commit -am adiciona somente as mudanças feitas e arquivos novos 
devem ser feitos pelo add. )

![image](https://user-images.githubusercontent.com/62863159/93007447-a51b5c80-f53f-11ea-8858-6be37cf393df.png)

<h2>Enviando Alterações </h2>

Após as alterações estiverem no Head, na área de trabalho local 
devemos enviar para o repositório remoto

`git push`

![image](https://user-images.githubusercontent.com/62863159/93007460-af3d5b00-f53f-11ea-9590-75d17048cfe4.png)

<h2>Atualizar</h2>

Verificar as novas atualizaçoes

`git fetch`

Atualizar o repositório 

`git pull`

![image](https://user-images.githubusercontent.com/62863159/93007488-d3993780-f53f-11ea-9ddb-da25c84c6e80.png)

<h2>Descartar alterações locais</h2>

Para descartar as alterações locais em um arquivo

`git checkout --<arquivo>`

Para descartar todas as alterações local

`git checkout  .`

Para excluir todos os arquivos e diretórios, que são conhecidos pelo git.

`git clean -d -f`

![image](https://user-images.githubusercontent.com/62863159/93007509-02afa900-f540-11ea-9957-bdc4ecfc8834.png)

<h2>Descartar alterações locais(caso tenha feito o uso
de git add)</h2>

Para descartar as alterações locais em um arquivo

`git fecth`

`git reset-hard`

![image](https://user-images.githubusercontent.com/62863159/93007541-47d3db00-f540-11ea-9178-6ce687c80044.png)

