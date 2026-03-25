# 📌 Guia de Contribuição – GitHub Classroom

## Como fazer seu commit corretamente

### 1. Configure seu Git (apenas na primeira vez)

git config --global user.name "Seu Nome Completo"
git config --global user.email "[seu.email@escola.com](mailto:seu.email@escola.com)"

### 2. Padrão de commits por aula

Use o padrão abaixo para nomear seus commits:


| Situação          | Exemplo de mensagem                      |
| ----------------- | ---------------------------------------- |
| Concluiu uma aula | `aula07: dashboard criado`               |
| Corrigiu um erro  | `fix: corrige cálculo do saldo`          |
| Adicionou desafio | `desafio: card de quantidade adicionado` |
| Atualização geral | `update: README preenchido`              |


### 3. Sequência de comandos

git add .
git commit -m "aula08: cadastro de contas funcionando"
git push origin main

### 4. Boas práticas

- ✅ Faça commit ao final de cada aula
- ✅ Nunca suba arquivos de configuração locais
- ✅ Preencha o README com sua identificação
- ❌ Não apague o .gitignore
- ❌ Não compartilhe seu repositório com colegas

