# 📝 Avaliação – Sistema Financeiro com PHP e Bootstrap

Instituição: **E031 - Etec Antonio Devisate de Marília**  
Componente Curricular: **Programação Web II**  

---

## 👨‍🎓 Dados do Aluno

| Campo | Informação |
|---|---|
| Nome do(a) aluno(a) | |
| Turma | |
| Número / RA | |
| Professor(a) | |
| Data da correção | |

---

## 📊 Rubrica de Avaliação por Critério

> Sugestão de escala: **0 a 10** para cada critério.  
> A coluna “Peso” indica a importância de cada item na nota final.

| Critério | Descrição | Peso | Nota (0–10) | Nota × Peso |
|---|---|:---:|:---:|:---:|
| Estrutura de pastas | Organização conforme apostila (config, data, includes, pages, etc.) | 1,0 |  |  |
| Login e sessão | Login, logout e proteção de páginas (auth.php) | 2,0 |  |  |
| Dashboard | Cálculo correto de totais, saldo e exibição com Bootstrap | 2,0 |  |  |
| CRUD – Create | Cadastro de contas funcionando (cadastrar.php, POST, array) | 2,0 |  |  |
| CRUD – Read | Listagem das contas (listar.php) com dados dinâmicos | 1,0 |  |  |
| Organização do código | Identação, nomes de variáveis, comentários quando necessário | 1,0 |  |  |
| Desafios extras | Implementação dos desafios das Aulas 07 e 08 (se aplicável) | 1,0 |  |  |

**Cálculo sugerido:**  
> Nota Final = (Soma de “Nota × Peso”) ÷ Soma dos Pesos

---

## ✅ Checklist Técnico (Professor)

Marque conforme o que foi verificado no repositório do aluno.

### Estrutura e Execução

- [ ] Projeto abre normalmente em `http://localhost/...`
- [ ] Não há erros fatais de PHP (Fatal error / Parse error)
- [ ] Includes funcionando (`config.php`, `auth.php`, `header.php`, `menu.php`)
- [ ] `dados.php` existe e contém o array de contas

### Autenticação e Sessão

- [ ] Página de login acessível
- [ ] Login com usuário de teste (ex.: `admin` / `1234`) funciona
- [ ] Logout encerra a sessão e redireciona
- [ ] Páginas protegidas redirecionam para login se não houver sessão

### Dashboard (Aula 07)

- [ ] Total de contas a receber calculado corretamente
- [ ] Total de contas a pagar calculado corretamente
- [ ] Saldo calculado corretamente
- [ ] Cards Bootstrap exibindo os valores
- [ ] Exibição do usuário logado e do perfil via `$_SESSION`

### CRUD – Create (Aula 08)

- [ ] Formulário de cadastro com campos: descrição, valor, tipo
- [ ] Envio via método POST
- [ ] Dados são adicionados ao array de contas
- [ ] Mensagem de sucesso (ou feedback) após cadastro

### Desafios (se cobrados)

- [ ] Card com quantidade de contas a pagar no dashboard
- [ ] Mensagem “Situação positiva/negativa” conforme o saldo
- [ ] Campo status selecionável no cadastro (Pendente/Pago)
- [ ] Redirecionamento após cadastro para `listar.php`

---

## 💬 Comentários Qualitativos do Professor

> Pontos fortes do trabalho, conquistas do aluno, aspectos em que se destacou.

```text
Escreva aqui os pontos positivos observados no projeto do aluno.
```

---

## 🔍 Pontos a Melhorar

> Sugestões para evolução do aluno em Programação Web II.

```text
Escreva aqui as principais dificuldades e sugestões de melhoria.
```

---

## 🏁 Síntese da Avaliação

| Item | Informação |
|---|---|
| Nota final | |
| Situação | ( ) Aprovado  ( ) Reprovado  ( ) Recuperação / Reentrega |
| Necessita refazer alguma parte? | ( ) Sim  ( ) Não |
| Qual parte (se sim)? | |

---

_Assinatura do(a) professor(a):_ ______________________________________