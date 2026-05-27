# Briefing — Projeto BI App

## Contexto geral

Tenho dois projetos separados:

### 1. Projeto Pessoal (já pronto)
- Repositório: `fortesindicadores-byte/dash-financeiro`
- Arquivo: `dashboard-financeiro.html`
- Painel de controle financeiro pessoal (Renan & Tati)
- GitHub Pages: `https://fortesindicadores-byte.github.io/dash-financeiro/dashboard-financeiro.html`

### 2. Projeto Corporativo (este repositório — `Projeto-BI-App`)
- Objetivo: trazer todo o BI do Looker Studio para o formato de painel HTML que já criei
- Referências visuais já existentes:
  - `https://fortesindicadores-byte.github.io/dash-custofrota/` → repo: `fortesindicadores-byte/dash-custofrota`
  - `https://fortesindicadores-byte.github.io/arvore-comb/` → repo: `fortesindicadores-byte/arvore-comb`

---

## O que precisa ser feito nesta sessão

### 1. Criar a estrutura de pastas no repositório

```
1. Visão Financeira/
2. Painel Km/
3. Eficiência Ativação/
4. Combustível/
5. R$ por km/
6. Disponibilidade/
7. Reunião Mensal/
8. Auditorias/
9. FCA/
10. Painel de Metas/
```

### 2. Popular as pastas com os índices existentes

- `1. Visão Financeira/` → copiar o conteúdo do repositório `fortesindicadores-byte/dash-custofrota`
- `4. Combustível/` → copiar o conteúdo do repositório `fortesindicadores-byte/arvore-comb`
- Demais pastas → ficam vazias por enquanto (usar `.gitkeep`)

### 3. Configurar GitHub Pages
- Apontar para a branch `main`
- O projeto não tem uma capa/index raiz por enquanto

---

## Padrão visual dos painéis
- Fundo escuro (`#0C1017`)
- Laranja como cor primária (`#F97316`)
- HTML puro + Chart.js — sem framework, sem backend
- Responsivo, dados embutidos no próprio arquivo

---

## Observações importantes
- O nome correto da pasta 4 é **"Combustível"** (não "Consumo Combustível"), pois terá outros painéis além de consumo
- Cada seção terá seu próprio `index.html` independente
- Futuramente será implementado controle de acesso (login, níveis de usuário, log de sessões) via Supabase
