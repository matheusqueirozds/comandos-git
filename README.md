# Principais comandos do Git

### Git Clone

| Comando                | Descrição                                                                                                                              |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `git clone <url-do-repo>` | Clona o repositório para sua máquina. Repositórios podem ser encontrados nos arquivos locais ou em uma máquina remota via HTTP ou SSH. |
| `git add <diretorio>` | Envia para a área de staging todas as mudanças no diretório em seu próximo commit. Altere `<diretorio>` por um arquivo específico para enviar somente ele ao staging. |
| `git add .` | Envia para a área de staging todas as mudanças dentro do diretório onde o comando foi criado |
| `git commit -m "<mensagem explicando a mudança no código>"` | Commita mudanças em staging, mas ao invés de abrir um editor de texto, permite a inclusão da mensagem dentro do campo `<mensagem explicando a mudança no código>`. Importante: não esquecer do comando `-m`. |
| `git status` | Fornece algumas informações sobre a branch em que você estiver no momento, como seu nome, se ela está atualizada em relação à master/main e quais arquivos foram modificados. |
| `git log` | Apresenta todo o histórico de commits usando o formato padrão. |

<br>

### Git Branch

| Comando      | Descrição                                  |
| ------------ | ------------------------------------------ |
| `git branch` | Lista todas as branches no seu repositório |
| `git checkout <nome-da-branch>` | Move você para a branch escolhida |
| `git checkout -b <nome-da-branch>` | Cria e move você para a nova branch |
| `git branch -d <nome-da-branch>` | Exclui sua branch |
| `git push origin <nome-da-branch>` | Empurra a branch para o espaço remoto, juntamente com todos os commits e objetos. Também as branches no repositório remoto caso ainda não existam. |


---

## Autora

<table>
  <tr>
     <td align="center">
      <a href="https://github.com/sterx17">
        <img src="https://avatars.githubusercontent.com/u/70871620?v=4" width="100px;" alt="Foto da Stephany Pietra no GitHub"/><br>
        <sub>
          <b>@sterx17</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## Colaboradores

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

---

## Contribua com mais informações
Contribuições são sempre bem-vindas!

Clique [AQUI](contribuindo.md) para saber como colaborar.
