# Principais comandos do Git

🚨 ATENÇÃO: Para utilizar atalhos mais curtos, como `comme`, `gcb`, etc., siga as orientações [desse post](https://www.instagram.com/p/CbinPZCAtdr/).

## Criando um Projeto

Comando | Descrição
| - | - |
`git init` | Cria um repositório vazio com o esqueleto de seu projeto. É o primeiro comando a ser digitado ao se criar um projeto Git.

<br>

## Clone

Comando | Descrição 
| - | - |
`git clone <link-do-repo>` | É o comando que clona as informações do repositório remoto (GitHub) para um repositório local (pasta na nossa máquina)

<br>

## Histórico

Comando | Descrição 
| - | - |
`git log` | Permite verificar o histórico de commits do projeto, começando pelo mais novo
`git log -- graph` | Mostra de forma mais descritiva e visual o que está acontecendo
`git log -p <nome-do-arquivo>` | Mostra as mudanças ao longo do tempo para um arquivo específico
`git blame <nome-do-arquivo>` | Mostra quem alterou o quê e quando

<br>

## Mudanças locais

Comando | Descrição 
| - | - |
`git status` | Fornece algumas informações sobre a branch em que você estiver no momento, como seu nome, se ela está atualizada em relação à master/main e quais arquivos foram modificados
`git add .` | Adiciona todos os arquivos da pasta onde você se encontra à Staging Area (que é local)
`git add <nome-do-arquivo>` | Envia os arquivos modificados, removidos e criados para a Staging Area 
`git commit -m "<mensagem explicando a mudança no código>"` | Cria uma versão do seu projeto com os arquivos que estiverem na Staging Area e descreve uma mensagem explicando as modificações realizadas. Importante: não esquecer do comando `-m` e das aspas ao redor da mensagem 
`comme` | Adiciona os arquivos a staging area e efetua um commit

<br>

## Branches

Comando | Descrição 
| - | - |
`git branch` | Lista todas as branches no seu repositório local. A branch padrão se chama master ou main
`git branch <nome-da-branch>` |  Permite criar uma nova branch, com o nome que você escolheu
`git checkout <nome-da-branch>` ou `gc`  | Permite acessar uma branch que já foi criada (localmente ou remota)
`git checkout -b <nome-da-branch>` ou `gcb` | Cria uma nova branch e já acessa diretamente
`git branch -D <nome-da-branch>` | Exclui sua branch 
`git push origin <nome-da-branch>` | Empurra a branch para o espaço remoto, juntamente com todos os commits e objetos. Também as branches no repositório remoto caso ainda não existam. 
`pushme` |  Efetua o commit e faz push para o repositório

<br>

## Atualizar e Publicar

Comando | Descrição 
| - | - |
`git push origin <nome-da-branch>` | Envia as suas alterações feitas para a branch no repositório remoto. Só envia as alterações que foram commitadas
`git pull origin <nome-da-branch>` ou `git pull` |  Atualiza a branch em questão no seu repositório local com as alterações commitadas na branch remota. Se você já estiver acessando a branch que deseja atualizar


#

## Stack utilizada
GitHub: Markdown

#

## Autores

<table>
  <tr>
     <td align="center">
      <a href="https://github.com/matheusqueirozds">
        <img src="https://avatars.githubusercontent.com/u/70871620?v=4" width="100px;" alt="Foto do Matheus Queiroz no GitHub"/><br>
        <sub>
          <b>@matheusqueirozds</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

#

## Contribua com esse guia!
Contribuições são sempre bem-vindas!

Clique [AQUI](contribuindo.md) para saber como colaborar.
