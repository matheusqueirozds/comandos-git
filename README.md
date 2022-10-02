<div align="center">
  
# Principais comandos para usar no Git bash
  
👨🏽‍💻 Guia para devs e divas cansados de pesquisar os comandos no Google.
  
  <img src="https://user-images.githubusercontent.com/70871620/193434684-7d0ac05b-39eb-467e-9fb9-50281d5a756f.gif" height="200px">
  
<br>
  
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
 
</div>

---

<details>
<summary><h2>🎓 Autor</h2></summary>

<div align="left">
  
[Matheus Queiroz](https://github.com/matheusqueirozds) |  
:-------------------------:|
 <a href="https://github.com/matheusqueirozds"><img src="https://avatars.githubusercontent.com/u/70871620?v=4" width="100px;" alt="Foto do Matheus Queiroz no GitHub"/></a> |
  
</div>
</details>

---

<details>
<summary><h2>🐣 Criando um projeto</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git init` | Cria um repositório vazio com o esqueleto de seu projeto. É o primeiro comando a ser digitado ao se criar um repositório. 

</details>

---

<details>
<summary><h2>🤼 Clonando um repositório</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git clone link-do-repositorio` | Permite que você faça uma cópia das informações de um repositório remoto (do GitHub, por exemplo) para um repositório local (em uma pasta do seu computador).

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
<summary><h2>🏠 Mudanças locais</h2></summary>

 Comando | Descrição 
 --- | :--- 
 `git status` | Fornece algumas informações sobre a branch em que você estiver no momento, como seu nome, se ela está atualizada em relação à master/main e quais arquivos foram modificados
 `git add .` | Adiciona todos os arquivos da pasta onde você se encontra à Staging Area (que é local)
 `git add nome-do-arquivo` |	Envia os arquivos modificados, removidos e criados para a Staging Area
 `git commit -m "mensagem explicando a mudança no código"` |	Cria uma versão do seu projeto com os arquivos que estiverem na Staging Area e descreve uma mensagem explicando as modificações realizadas. Importante: não esquecer do comando -m e das aspas ao redor da mensagem
 `comme "mensagem explicando a mudança no código"` |	Adiciona os arquivos a staging area e efetua um commit

</details>

---

<details>
<summary><h2>🕸 Branches</h2></summary>

 Comando | Descrição 
 --- | :--- 
`git branch` | Lista todas as branches no seu repositório local. A branch padrão se chama master ou main
`git branch <nome-da-branch>` |  Permite criar uma nova branch, com o nome que você escolheu
`git checkout <nome-da-branch>` ou `gc`  | Permite acessar uma branch que já foi criada (localmente ou remota)
`git checkout -b <nome-da-branch>` ou `gcb` | Cria uma nova branch e já acessa diretamente
`git branch -D <nome-da-branch>` | Exclui sua branch 
`git push origin <nome-da-branch>` | Empurra a branch para o espaço remoto, juntamente com todos os commits e objetos. Também as branches no repositório remoto caso ainda não existam. 
`pushme` |  Efetua o commit e faz push para o repositório

</details>

---

<details>
<summary><h2>✅ Atualizar e Publicar</h2></summary>

 Comando | Descrição 
 --- | :--- 
`git push origin <nome-da-branch>` | Envia as suas alterações feitas para a branch no repositório remoto. Só envia as alterações que foram commitadas
`git pull origin <nome-da-branch>` ou `git pull` |  Atualiza a branch em questão no seu repositório local com as alterações commitadas na branch remota. Se você já estiver acessando a branch que deseja atualizar

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
