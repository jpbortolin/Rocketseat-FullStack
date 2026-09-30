# Stage 02 - Git e GitHub

## Comandos Git

Inicia o *git* (repositório) no seu projeto:
```bash
git init
```

Verifica alterações de pastas e arquivos no projeto:
```bash
git status
```

Adiciona TODOS os arquivos (dentro da pasta que você está) modificados ao *Stage Area*:
```bash
git add .
```
Remove TODOS os arquivos dentro da pasta que você está e os remove do disco:
```bash
git rm .
```

Desfaz alterações e recupera arquivos da *Stage Area*:
```bash
git rm .
```

Cria e descreve um *commit* (modificação) no projeto:
```bash
git commit -m "message here"
```

Histórico de commits do projeto:
```bash
git log
```

Voltar para um commit anterior:
```bash
git checkout ID_COMMIT_DESEJADO
```

Recuperar um arquivo antes do commit ter sido efetuado:
```bash
git checkout ID_COMMIT_DESEJADO -- NOME_ARQUIVO
```

---

### Comandos para trabalhar com repositório remoto

Puxa modificações do repositório remoto para o repositório local:
```bash
git pull
```

Envia as modificações locais para o repositório remoto:
```bash
git push
```