## Adicionando novo projeto já existente no repositorio do git

  1- Crie o repositório no GitHub/GitLab ou outro qualquer.
  2- no repositório local, digite "git init" para criar a branch. caso necessário, altere o nome da branch com o comando git branch -m <nome_branch> ou crie uma nova branch com o comando git checkout -b <nome_branch>
  3- Adicione os arquivos para o commit e crie o commit inicial.
  4- Adicione o repositório remoto no local utilizando o comando: git remote add origin <link_repo_remoto>
  5- Envie as alterações: git push -u origin <branch_name>

## Etapas sugeridas pelo github:

### create a new repository on the command line
	echo "# <project_name>" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/your_reposiotry/your_project.git
	git push -u origin main


### push an existing repository from the command line
	git remote add origin https://github.com/your_repository/your_project.git  
	git branch -M main
	git push -u origin main

