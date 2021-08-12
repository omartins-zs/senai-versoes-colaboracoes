# Senai Versões Colaborações
### Repositorio usado no curso de Programaçao Back-End do Senai UC7 Versionamento


<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-principais-comandos">Comandos</a> •
 <a href="#-tecnologias">Tecnologias</a>
</p>

 <div align="center">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
 </div>
 
### 💻 Sobre o projeto

🚀 Readme e Versionamento 

Readme desenvolvido por **[Gabriel Martins](https://www.linkedin.com/in/gabriel-martins-0479811b0/)**

### Alterações

 - Readme personalizado e adicionado links para auxilio

---


### 🔴 Principais Comandos


- git init
>Cria a estrutura inicial do repositório Git no computador local.


- git status
>Verifica o status das alterações realizadas no repositório.

- git add
>Adiciona arquivos ao histórico do projeto, na staging.

- git commit
>Registra/salva a alteração no repositório.

- git log
>Permite visualizar as alterações feitas.

- git show número-do-commit(Comando permite visualizar de qualquer commit)
>visualizar alteraçoes do commit no terminal

- git remote add origin "destino"
>Informa a pasta remota.

- git remote –v
>Permite visualizar o repositório remoto.

- git push -u origin master
>Publica as alterações no repositório remoto.

- git pull
>Baixa as alterações do repositório remoto na maquina local.

- git pull
>para baixar as atualizações do repositório remoto

- git clone
>para clonar a pasta do repositório remoto.

- git checkout -b tarefa/minha-primeira-branch ("–b" é para informar que vamos criar uma branch e esse ramo não existe)
>criar uma branch

- git checkout master
>voltar para a branch/trunk 'master'

- git checkout -b exemplo-branch (depois de -b "nome da nova branch")
>criar uma nova branch

- git pull origin tarefa/minha-primeira-branch (depois de origin "nome da branch")
>Realizar o download das informações fornecidas de outra branch

- git merge tarefa/minha-primeira-branch (depois de merge "nome da branch")
>Fazer a mesclagem com outra branch

- git tag -a v1.0 -m "minha primeira tag" (depois de -a "nome da tag", depois de -m "comentario")
>cria uma tag para marcar o ponto atual com o comando

- git tag
>Para ver as tags criadas

- git show v1.0 (depois de show "nome da tag")
>Para ver informações sobre uma tag específica

- git push origin --tags
>publicar as tags no repositório remoto  

<table>
            <tr>
                <th colspan="4">Desafio de versionamento Branch</th>
            </tr>
            <tr>
                <th colspan="4"></th>
            </tr>
            <tr>
                <th>Etapa</th>
                <th>Desafio</th>
                <th>Solução</th>
                <th>Status</th>
            </tr>
            <tr>
                <td align="center">1</td>
                <td>Retorna ao tronco principal</td>
                <td>git checkout master</td>
                <td align="center">✔️</td>
            </tr>
            <tr>
                <td align="center">2</td>
                <td>Cria uma nova branch</td>
                <td>git checkout –b nome-branch</td>
                <td align="center">✔️</td>
            </tr>
            <tr>
                <td align="center">3</td>
                <td>Publica a branch no repositório remoto</td>
                <td>git push origin nome-branch</td>
                <td align="center">✔️</td>
            </tr>
            <tr>
                <td align="center">4</td>
                <td>Mescla a branch atual com a branch referida</td>
                 <td>git merge origin nome-branch</td>
                 <td align="center">✔️</td>
            </tr>
</table>

 ---
 
### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto e Readme:

- **[Git](https://git-scm.com/downloads)**
- **[GitHub](https://github.com/)**

### **Utilitários**

- Readme: **[Tutorial](https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)**
- Editor: **[Visual Studio Code](https://code.visualstudio.com/)**
- Markdown: **[StackEdit](https://stackedit.io/)**, **[Markdown Emoji](https://gist.github.com/rxaviers/7360908)**
