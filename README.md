# DIO | Resumos Git e Github

Repositório para armazenar resumos sobre Git e Github do curso versionamento de código com Git e Github da [Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/docs/git/pt_BR)
- [Documentação GitHub](https://docs.github.com/)

## 💻 Resumos das Aulas

| Aulas                                     | Resumos                                                                 |
|-------------------------------------------|-------------------------------------------------------------------------|
| Gravando alterações no repositório local | Veja abaixo os comandos essenciais para iniciar e versionar um projeto |

### 🔸 Gravando alterações no repositório local

```bash
# Navegar até a pasta onde ficará o repositório
cd documents
cd dio_git_github

# Criar a pasta do repositório local
mkdir repo-local
cd repo-local/

# Inicializar o repositório Git
git init

# Adicionar arquivos ao controle de versão
git add README.md   # Ou git add . para adicionar todos os arquivos

# Configurar nome e e-mail do autor (se necessário)
git config --global user.email "jossaneoliveira.cardoso@gmail.com"
git config --global user.name "J0ssan3"

# Realizar o commit
git commit -m "first commit"

# Renomear a branch principal
git branch -M main

# Conectar o repositório local ao repositório remoto no GitHub
git remote add origin https://github.com/J0ssan3/estudo_git_dio.git

# Criar o arquivo README.md (caso não exista)
touch README.md

# Verificar o status dos arquivos
git status

# Adicionar e commitar o README.md
git add README.md
git commit -m "commit inicial"

# Verificar o histórico de commits
git log

# Para inserir o código readme dentro de README.md
cat > README.md
```

## 🔎 Referências

- [Curso na DIO](https://www.dio.me/)
- [Documentação oficial do Git](https://git-scm.com/docs/git/pt_BR)
- [Documentação GitHub](https://docs.github.com/)
