# 💰 FluxoCash — Controle Financeiro Pessoal

Sistema completo de controle financeiro pessoal. Hospede gratuitamente no Netlify!

---

## 🚀 Como hospedar no Netlify (gratuito)

### Opção 1 — Arrastar e soltar (mais fácil)
1. Acesse [app.netlify.com](https://app.netlify.com) e crie uma conta grátis
2. No painel, vá em **"Add new site" → "Deploy manually"**
3. Arraste a **pasta** `financeapp` inteira para a área indicada
4. Pronto! Seu site estará no ar em segundos com uma URL grátis.

### Opção 2 — Via GitHub (recomendado para atualizações)
1. Crie um repositório no GitHub e suba os arquivos
2. No Netlify: **"Add new site" → "Import an existing project"**
3. Conecte seu GitHub e selecione o repositório
4. Build settings: deixe tudo em branco (é um site estático)
5. Clique em **Deploy**

---

## 📁 Arquivos

```
financeapp/
├── index.html     ← Aplicação completa (único arquivo necessário)
└── netlify.toml   ← Configuração do Netlify
```

---

## 💾 Sobre o banco de dados

O FluxoCash usa o **localStorage do navegador** para armazenar seus dados — a solução ideal para uma aplicação pessoal:

✅ **Totalmente gratuito** — sem custos de servidor  
✅ **Sem configuração** — funciona instantaneamente  
✅ **Privado** — seus dados ficam apenas no seu dispositivo  
✅ **Rápido** — sem latência de rede  

> **Dica:** Para fazer backup dos seus dados, use a função **"⬇ Exportar CSV"** na página de Transações.

---

## ✨ Funcionalidades

| Módulo | Recursos |
|--------|----------|
| **Dashboard** | Saldo total, receitas/despesas do mês, taxa de poupança, gráfico de tendência 6/12 meses, categorias do mês |
| **Transações** | Adicionar/editar/excluir, filtros por tipo/categoria/mês/busca, exportar CSV, forma de pagamento |
| **Metas** | Criar metas com ícone e cor, prazo, progresso, sugestão de poupança mensal, adicionar valor |
| **Orçamento** | Limites mensais por categoria, alertas de 90% e excedido, resumo total |
| **Relatórios** | Comparativo anual, evolução do patrimônio, distribuição por categoria, resumo consolidado |
| **Configurações** | Nome de usuário, moeda (R$/$/€), limpar dados |

---

## 📱 Responsividade

- **Desktop:** Sidebar lateral com navegação completa
- **Mobile:** Header fixo + barra de navegação inferior (estilo app nativo)
- Totalmente adaptado para todos os tamanhos de tela

---

## 🎨 Categorias disponíveis

**Despesas:** Moradia, Alimentação, Transporte, Saúde, Educação, Lazer, Vestuário, Dívidas, Tecnologia, Assinaturas, Investimentos, Presentes, Pets, Viagens, Beleza, Outros

**Receitas:** Salário, Freelance, Rendimentos, Aluguel, Bônus/13°, Reembolso, Presente recebido, Outros
