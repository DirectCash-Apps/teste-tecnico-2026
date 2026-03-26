# Teste Técnico — DirectAds

## Sobre nós

A DirectAds é uma plataforma de gestão de anúncios construída com auxílio de inteligência artificial. Acreditamos que ferramentas de IA são aliadas poderosas no desenvolvimento de software e fazem parte do nosso dia a dia.

Estamos buscando **desenvolvedores Pleno/Sênior** que saibam utilizar essas ferramentas com consciência — que entendam cada linha do código que entregam, cada dependência que instalam e cada decisão arquitetural que tomam.

---

## Objetivo

Construir uma **aplicação full-stack funcional (MVP)** com tema livre em **48 horas**.

Queremos avaliar sua capacidade de:

- Tomar decisões técnicas sólidas e justificá-las
- Estruturar um projeto escalável desde o início
- Utilizar ferramentas de IA de forma produtiva e consciente
- Entregar código limpo, organizado e pronto para evoluir

---

## Regras Gerais

| Item | Detalhe |
| --- | --- |
| **Prazo** | 48 horas a partir do recebimento deste documento |
| **Tema** | Livre — escolha o domínio que preferir (e-commerce, task manager, blog, SaaS, etc.) |
| **Ferramentas de IA** | Permitido e encorajado (Cursor, Antigravity, Windsurf, Copilot ou qualquer outra) |
| **Entrega** | Repositório GitHub **público** + deploy online funcionando |
| **Deploy** | Sugerimos [Railway](https://railway.app) — ao criar a conta você ganha $5 de crédito gratuito, suficiente para este teste |
| **Entrevista** | Candidatos selecionados farão uma entrevista técnica de defesa do projeto (~15–30 min) |

---

## Stack Obrigatória

| Camada | Tecnologia |
| --- | --- |
| **Frontend** | Next.js (App Router) |
| **Backend** | NestJS |
| **Banco de Dados** | PostgreSQL |
| **ORM** | Prisma |
| **Linguagem** | TypeScript (em ambos os projetos) |

---

## Requisitos Obrigatórios

### Funcionalidades

- **Autenticação:** sistema de login e registro funcional com JWT
- **CRUD completo:** pelo menos uma entidade com Create, Read, Update e Delete implementados de ponta a ponta (front + back + banco)

### Qualidade de Código

Esperamos que o projeto tenha um **pipeline de qualidade configurado**:

- Linting funcional e sem erros/warnings ignorados
- Formatação automática de código
- Git hooks que validem o código antes do commit
- Padrão de commits consistente ao longo do projeto

Você escolhe as ferramentas. O importante é que o workflow funcione e que você saiba explicar por que escolheu cada uma. Conhecer alternativas ao convencional será visto como diferencial.

### Documentação

- **README.md** contendo:
  - Como rodar o projeto localmente (passo a passo)
  - Decisões técnicas e arquiteturais tomadas
  - Lista de **todas** as dependências instaladas com uma breve justificativa de por que cada uma foi escolhida
- **Swagger** no backend acessível via `/api/docs`

### Design e Interface

- Interface **responsiva** (mobile e desktop)
- Layout **limpo e funcional** — não precisa ser obra de designer, mas a UX deve ser pensada
- Navegação intuitiva e estados visuais claros (loading, erro, vazio, sucesso)

### TypeScript

- Tipagem correta em todo o projeto
- Sem `any` desnecessário — se precisar usar, justifique no código com um comentário

---

## Diferenciais (Bônus)

Estes itens não são obrigatórios, mas demonstram maturidade técnica e podem destacar sua candidatura:

- Containerização do ambiente de desenvolvimento
- Testes automatizados (unitários e/ou e2e)
- Pipeline de CI/CD
- Validação de dados no frontend e no backend
- Seed de dados para facilitar avaliação
- Dark mode
- Internacionalização (i18n)
- Cache ou filas assíncronas
- Monitoramento ou logging estruturado

---

## O que NÃO queremos ver

- **Dependências em excesso sem justificativa** — instale apenas o que faz sentido para o MVP. Na entrevista, você precisará explicar por que cada pacote está no projeto
- **Código gerado por IA sem entendimento** — usar IA é permitido e incentivado, mas você será questionado sobre cada trecho do código na entrevista
- **Projeto sem README** ou sem instruções de como rodar

---

## Critérios de Avaliação

| Critério | Peso | O que avaliamos |
| --- | --- | --- |
| **Arquitetura e organização** | 20% | Estrutura de pastas, separação de responsabilidades, padrões de projeto |
| **Qualidade de código** | 20% | Linting limpo, tipagem TypeScript, clean code, tratamento de erros |
| **Git workflow** | 15% | Hooks configurados, padrão de commits, histórico coerente |
| **Design e UX** | 15% | Responsividade, usabilidade, estados da interface, consistência visual |
| **Funcionalidades** | 15% | Auth + CRUD funcionando corretamente de ponta a ponta |
| **README e documentação** | 10% | Clareza, completude, justificativa de dependências |
| **Diferenciais** | 5% | Containerização, testes, CI/CD, e demais bônus listados acima |

---

## Como Entregar

1. Crie um repositório **público** no GitHub
2. Faça o deploy da aplicação (sugestão: [Railway](https://railway.app))
3. Preencha o formulário de entrega: **[DirectAds - Envio de Teste Técnico](https://forms.gle/wpyga7rZMxbxZmbR8)**
   - Email
   - LinkedIn
   - Link do repositório GitHub
   - Link da aplicação em produção (deploy)
4. Certifique-se de que:
   - O README está completo e claro
   - O deploy está funcional e acessível
   - O Swagger do backend está acessível em `/api/docs`

> Você pode entregar antes das 48 horas. O prazo é um limite, não uma meta.

---

## Entrevista Técnica (pós-entrega)

Caso seja selecionado, você será convidado para uma **entrevista técnica de ~15–30 minutos** onde irá:

- **Demonstrar** o projeto funcionando (compartilhamento de tela)
- **Explicar** a arquitetura escolhida e a organização do projeto
- **Justificar** cada dependência instalada — por que escolheu, o que ela resolve, se considerou alternativas
- **Responder** perguntas técnicas sobre decisões tomadas no código
- **Explicar** como utilizou ferramentas de IA — quais usou, em quais partes, e onde precisou intervir manualmente

> Esta etapa é tão importante quanto o código. Queremos entender seu raciocínio, não apenas o resultado final.

---

## Dúvidas

Se algo não ficou claro neste documento, entre em contato com o recrutador. Preferimos responder dúvidas antes do que avaliar entregas baseadas em suposições.

Boa sorte!
