[Notice] This RTF export has limited fidelity for advanced formatting and images. Use DOCX for best results.

#  Sistema Financeiro com PHP e Bootstrap






> Projeto didático desenvolvido nas aulas de Programação Web II.  
> Instituição: **E031 - Etec Antonio Devisate de Marília**  
> Componente Curricular: **Programação Web II**  
> 2o. Mtec PI Desenvolvimetno de Sistemas

---

##  Identificação do Aluno

| Campo | Preencher |
|---|---|
| **Nome completo** | |
| **Turma** | |
| **Número / RA** | |
| **Professor(a)** | |
| **Data de entrega** | |

> Preencha sua identificação antes de fazer o commit final.

---

##  Sobre o Projeto

Sistema Financeiro desenvolvido com **PHP puro** e **Bootstrap 5**, com funcionalidades de login, controle de sessão, dashboard e CRUD completo de contas a pagar e receber.

Este repositório é utilizado como atividade avaliativa na disciplina **Programação Web II** da **E031 - Etec Antonio Devisate de Marília**, por meio do **GitHub Classroom**.

---

## ️ Estrutura de Pastas
text
sistema-financeiro/
│
├── config/
│   └── config.php              # Configurações gerais do sistema
│
├── data/
│   └── dados.php               # "Base de dados" simulada (arrays PHP)
│
├── includes/
│   ├── auth.php                # Controle de autenticação/sessão
│   ├── header.php              # Cabeçalho padrão do sistema
│   └── menu.php                # Menu de navegação por perfil
│
├── pages/
│   ├── dashboard.php           # Tela inicial com indicadores
│   └── contas/
│       ├── cadastrar.php       # CREATE – Cadastro de contas
│       ├── listar.php          # READ – Listagem de contas
│       ├── editar.php          # UPDATE – Edição de contas
│       └── excluir.php         # DELETE – Exclusão de contas
│
└── README.md
---

## ✅ Checklist de Entregas

O aluno deve marcar cada item concluído antes de fazer o envio final (push).

### Aulas Concluídas

- [ ] Aula 01 – Introdução e ambiente configurado
- [ ] Aula 02 – Estrutura de pastas criada
- [ ] Aula 03 – Configuração e includes funcionando
- [ ] Aula 04 – Login e autenticação com Session
- [ ] Aula 05 – Menu dinâmico por perfil
- [ ] Aula 06 – Proteção de páginas com auth.php
- [ ] Aula 07 – Dashboard com PHP + Bootstrap
- [ ] Aula 08 – CRUD CREATE (Cadastro de Contas)
- [ ] Aula 09 – CRUD READ (Listagem de Contas)

### Funcionalidades Implementadas

- [ ] Login funcionando
- [ ] Logout funcionando
- [ ] Dashboard exibindo totais corretamente
- [ ] Cadastro de contas funcionando
- [ ] Listagem de contas funcionando
- [ ] Edição de contas funcionando
- [ ] Exclusão de contas funcionando
- [ ] Menu muda conforme o perfil do usuário
- [ ] Páginas protegidas por autenticação

### Desafios Extras (opcional)

- [ ] Aula 07 – Card com quantidade de contas a pagar
- [ ] Aula 07 – Mensagem de “Situação positiva/negativa” conforme saldo
- [ ] Aula 08 – Campo de status selecionável (Pendente/Pago)
- [ ] Aula 08 – Redirecionamento após cadastro para `listar.php`

---

## ️ Tecnologias Utilizadas

| Tecnologia | Versão | Finalidade |
|---|---|---|
| PHP | 7.4+ | Lógica e manipulação de dados |
| Bootstrap | 5 | Interface visual e responsividade |
| HTML5 | – | Estrutura das páginas |
| CSS | – | Customização visual |
| Sessions PHP | – | Controle de login e perfis de usuário |
| Git / GitHub | – | Controle de versão e entrega via GitHub Classroom |

---

##  Conceitos Envolvidos

### Dashboard

Tela inicial do sistema que exibe:

- Total de contas a receber
- Total de contas a pagar
- Saldo final
- Dados do usuário logado (nome e perfil)

Os dados são calculados em PHP a partir de arrays e exibidos com **Cards do Bootstrap**.

### CRUD

| Letra | Significado | Ação no sistema |
|---|---|---|
| C | Create | Cadastrar nova conta |
| R | Read | Listar contas cadastradas |
| U | Update | Editar uma conta existente |
| D | Delete | Excluir uma conta |

Cada conta possui:
php
$conta = [
"id"        => 1,
"descricao" => "Mensalidade",
"valor"     => 200,
"tipo"      => "Receber",  // ou "Pagar"
"status"    => "Pendente"  // ou "Pago"
];
---

## ▶️ Como Executar o Projeto em Ambiente Local

### Pré-requisitos

- PHP 7.4 ou superior
- Servidor local (XAMPP, WAMP, Laragon ou similar)
- Navegador atualizado (Chrome, Firefox, Edge etc.)

### Passo a passo
bash
1. Clone o repositório (com o link fornecido pelo GitHub Classroom)
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
2. Copie a pasta do projeto para a pasta do servidor local
Exemplo com XAMPP (Windows):
Mova a pasta do projeto para:
C:/xampp/htdocs/sistema-financeiro/
3. Inicie o Apache (no XAMPP, WAMP ou Laragon)
4. Acesse no navegador:
http://localhost/sistema-financeiro/pages/login.php
Se a pasta tiver outro nome, ajuste a URL conforme o nome que foi utilizado.

---

##  Credenciais de Teste (Didáticas)

| Usuário | Senha | Perfil |
|---|---|---|
| admin | 1234 | Administrador |
| usuario | 1234 | Usuário |

Essas credenciais são apenas para fins didáticos, para facilitar os testes durante as aulas de **Programação Web II**.

---

##  Critérios de Avaliação (Sugestão)

| Critério | Descrição | Peso |
|---|---|---|
| Estrutura de pastas correta | Arquivos organizados conforme a apostila | 10% |
| Login e sessão | Login, logout e proteção de páginas funcionando | 20% |
| Dashboard | Cálculos corretos e uso de Bootstrap Cards | 20% |
| CRUD de contas | Create, Read, Update e Delete funcionando | 30% |
| Organização do código | Legibilidade, identação, nomes de variáveis | 10% |
| Desafios extras | Implementação dos desafios propostos | 10% |

---

##  Observações do Aluno

Use este espaço para registrar dificuldades encontradas, decisões de implementação, melhorias feitas ou partes do sistema que não conseguiu concluir.
text
Escreva aqui suas observações…
---

##  Licença de Uso Educacional

Este material é destinado ao uso **educacional e institucional** nas aulas de **Programação Web II** da **E031 - Etec Antonio Devisate de Marília**.  
É permitida a reprodução para fins didáticos, desde que mantidas as referências à instituição e ao componente curricular.
