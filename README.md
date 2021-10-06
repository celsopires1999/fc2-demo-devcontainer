## Descrição

Versão do Demo fc2-java com devcontainer.

### Motivação
Implementar os conceitos da parte "Pontapé Inicial" do módulo "Microsserviço: Catálogo de vídeos com Java (Back-end)", sem a necessidade de instalar componentes na máquina local.

## Rodar a aplicação

#### Criação do container
Abra o projeto no VSCode usando a opção "Open Folder in Container..." através do painel de comandos (Ctrl+Shift+P). Acompanhe a execução do build do container no terminal integrado. A extensão do Grade lançará um erro (The Gradle client was unable to connect. Try re-connecting.) e na barra de mensagem "Initializing Gradle Language Server". Esse comportamento somente é observado ao criar o container. Feche o projeto usando "Close Remote Connection" no painel de comandos.

Agora que temos o container criado, podemos abrir o projeto normalmente.

#### Acesse no browser

```
http://localhost:8080/hello
```

### Observação
O arquivo .gitignore foi renomeado para .gitignore.example para que todos os arquivos ficassem disponíveis no GitHub.
