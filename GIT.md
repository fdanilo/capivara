#Git Bash

## Configurações

#### Nome
```
git config --global user.name "João Paulo S. de Araújo"
```

#### Login
```
git config --global user.email a.joao1988@gmail.com
```

### 1. Clonar repositório
```
git clone url_repo_forkado
```
### 2. Adicionar repositório remoto
```
git remote add upstream url_repo_original
```
### 3. Atualizar repositório local
```
git fetch upstream
```

### 4. Mesclar fetch com repo local
```
git merge upstream/master
```



## Após qualquer atualização

### 1. Adicionar arquivo para commit
```
git add seu_arquivo.md
```

### 2. Dar commit
```
git commit -am "descricao do commit"
```

### 3. Puxar atualizações do grupo rede local
```
git pull
```

### 3. Subir atualização para repositório forkado
```
git push origin master
```

### 4. Dar Pull Request para repo original
- Acessar endereço do repositório original
- Clicar no botão: "Create pull Request"
- Clicar no link "Compare accross forks"
- No base fork deixar original e no "head fork" escolher seu usuário.

## Comandos diversos

- `git status`: Lista estado do repo local, arquivos alterados, adicionados para commit e etc.
