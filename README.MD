# Mini Curso de Git

## 📌 Introdução
Git é um sistema de controle de versão distribuído amplamente utilizado por desenvolvedores. Este mini curso cobre os comandos mais essenciais do Git.

## 🛠 Instalação
### Linux (Ubuntu/Debian)
```bash
sudo apt install git
```

### MacOS
```bash
brew install git
```

### Arch Linux
```bash
sudo pacman -S git
```

### Windows
[Baixe aqui](https://git-scm.com/downloads)

## ⚙️ Configuração Inicial
```bash
# Configurar nome de usuário
git config --global user.name "Seu Nome"

# Configurar email
git config --global user.email "seuemail@example.com"

# Verificar configuração
git config --list
```

## 🚀 Comandos Essenciais

### 📂 Criando e Inicializando um Repositório
```bash
# Criar um repositório
mkdir meu-projeto && cd meu-projeto

git init  # Inicializa um repositório Git na pasta atual
```

### 📄 Trabalhando com Arquivos
```bash
# Adicionar arquivos para serem versionados
git add arquivo.txt  # Adiciona um arquivo

git add .  # Adiciona todos os arquivos modificados

# Criar um commit
git commit -m "Mensagem do commit"
```

### 🔍 Visualizando o Status do Repositório
```bash
git status  # Mostra arquivos modificados, adicionados e não rastreados
```

### 🌿 Trabalhando com Branches
```bash
# Criar uma nova branch
git branch minha-branch

# Alternar para a nova branch
git checkout minha-branch

git switch minha-branch  # Alternativa mais moderna

# Criar e mudar para a branch diretamente
git checkout -b nova-branch
```

### 🔗 Trabalhando com Repositórios Remotos
```bash
# Adicionar um repositório remoto
git remote add origin https://github.com/seu-usuario/seu-repo.git

# Enviar alterações para o repositório remoto
git push origin minha-branch
```

### 📥 Atualizando o Repositório
```bash
# Baixar alterações do repositório remoto
git pull origin main  # Atualiza com as mudanças do repositório remoto
```

### 🔀 Mesclando Branches
```bash
# Voltar para a branch principal
git checkout main

# Mesclar outra branch na main
git merge minha-branch
```

### 🔄 Revertendo Mudanças
```bash
# Desfazer todas as mudanças locais
git reset --hard HEAD

# Remover arquivo do stage
git reset arquivo.txt

# Voltar a um commit anterior
git checkout 123abc456  # Use o hash do commit
```

### 📜 Histórico de Commits
```bash
git log  # Exibe o histórico de commits

git log --oneline --graph --decorate  # Histórico resumido
```

## 📚 Conclusão
Este mini curso fornece os conceitos básicos para começar a trabalhar com Git. Para mais detalhes, consulte a [documentação oficial](https://git-scm.com/doc).

