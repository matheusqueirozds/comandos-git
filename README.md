<div align="center">
  
# Principais comandos para usar no Git
  
> 👨🏽‍💻 Guia para devs e divas cansados de pesquisar os comandos no Google.
  
  <img src="https://user-images.githubusercontent.com/70871620/193434684-7d0ac05b-39eb-467e-9fb9-50281d5a756f.gif" height="200px" title="Nas crônicas de água e fogo, eu prefiro, bug por imersão à la dracarys" />
  
<br>
  
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
 
</div>

---

<details>
<summary><h2>🎓 Autor</h2></summary>

<div align="left">
  
[Matheus Queiroz](https://github.com/matheusqueirozds) |  
:-------------------------:|
 <a href="https://github.com/matheusqueirozds"><img src="https://avatars.githubusercontent.com/u/70871620?v=4" width="100px;" alt="Foto do Matheus Queiroz no GitHub" title="Não sou Jason Momoa, mas adoro peixe"/></a> |
  
</div>
</details>

---

<details>
<summary><h2>🐣 Criando um projeto</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git init` | Transforma o diretório atual em um repositório do Git, possibilitando assim a gravação de revisões do projeto
 `git init nome-da-pasta` | Cria um repositório do Git vazio na pasta especificada.  

</details>

---

<details>
<summary><h2>🤼 Clonando um repositório</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git clone link-do-repositorio` | Cria uma cópia de um repositório existente.

</details>

---

<details>
<summary><h2>🏠 Mudanças locais</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git add .` | Adiciona todos os arquivos da pasta onde você se encontra à Staging Area (que é local), preparando todas as alterações. No entanto, esse comando não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar `git commit`
 `git add nome-do-arquivo` |	Envia os arquivos modificados para a Staging Area
 `git status` | Permite que você veja todas as alterações do projeto monitoradas pelo git
 `git commit -m "mensagem clara explicando a mudança no código"` |	Cria uma versão do seu projeto com os arquivos que estiverem na Staging Area e descreve uma mensagem explicando as modificações realizadas. Em resumo, um commit funciona como tirar uma foto. Importante: não esquecer do comando -m e das aspas ao redor da mensagem 
 `comme "mensagem clara explicando a mudança no código"` |	É a junção do `git add` com o `git commit`, já adicionando os arquivos a staging area e efetuando um commit
 `git commit --amend -m "mensagem clara explicando a mudança no código"` | Modifica o último commit. Em vez de criar um novo commit, as mudanças preparadas são adicionadas ao commit anterior.

</details>

---

<details>
<summary><h2>💬 Histórico</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git log` | Permite verificar o histórico de commits do projeto, começando pelo mais novo
 `git log -- graph` | Mostra de forma mais descritiva e visual o que está acontecendo
 `git log -p nome-do-arquivo` |	Mostra as mudanças ao longo do tempo para um arquivo específico
 `git blame nome-do-arquivo` |	Mostra quem alterou o quê e quando

</details>

---

<details>
<summary><h2>🕸 Branches</h2></summary>

 Comando | Descrição
 --- | :---
`git branch` | Lista todas as branches no seu repositório local. A branch padrão se chama master ou main
`git branch nome-da-branch` |  Permite criar uma nova branch, com o nome que você escolheu
`git checkout nome-da-branch` | Permite acessar uma branch que já foi criada (localmente ou remota) 
`gc nome-da-branch` | Faz a mesma coisa que o comando anterior
`git checkout -b nome-da-branch`  | Cria uma nova branch e já acessa diretamente
`gcb nome-da-branch` | Faz a mesma coisa que o comando anterior
`git branch -D nome-da-branch` | Exclui sua branch 
`git merge` | Mescla as linhas de desenvolvimento. De modo geral, esse comando é usado para combinar alterações feitas em dois branches distintos. Por exemplo, um desenvolvedor faria merge quando quisesse combinar alterações de um branch de recurso no branch principal para implantação.
`git push origin nome-da-branch` | Empurra a branch para o espaço remoto, juntamente com todos os commits e objetos. Também as branches no repositório remoto caso ainda não existam. 
`pushme nome-da-branch` |  Efetua o commit e faz push para o repositório

</details>

---

<details>
<summary><h2>✅ Atualizar e Publicar</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git fetch` | Puxa todas as informações de um repositório remoto para seu repositório local, de forma segura, deixando o trabalho atual intacto
 `git merge` | Atualiza o estado de trabalho do repositório local com as modificações puxadas pelo comando `git fetch`, modificando a branch ativa
 `git pull` | É a junção dos comandos `git fetch` e  `git merge`, atualizando imediatamente a branch ativa no seu repositório local com as alterações commitadas na branch remota
`git push | Envia as suas alterações feitas para a branch no repositório remoto. Só envia as alterações que foram commitadas

</details>

---

<details>
<summary><h2>🤝🏽 Contribua com esse guia!</h2></summary>

Contribuições são sempre bem-vindas!

Este é um projeto totalmente livre que aceita contribuições via pull requests no GitHub. Este documento tem a responsabilidade de alinhar as contribuições de acordo com os padrões estabelecidos no mesmo. Em caso de dúvidas, [abra uma issue](https://github.com/matheusqueirozds/comandos-git/issues/new).

1. Fork este repositório. Caso não saiba como fazer isso, [clique aqui](https://youtu.be/q-QTbNu8Ybc) para conferir.
2. Verifique se as informações estão corretas e se irá ajudar outros devs e divas.
3. Envie seus commits.
4. Solicite a pull request.
5. Insira um pequeno resumo dos links adicionados.
</details>
