
<div align="center">
  <img src="LINK_DA_SUA_IMAGEM_AQUI" width="600px" />
  <h1>💰 FinEdu AI</h1>
  <p>Plataforma Full-stack de Gestão Financeira e Educação</p>
  
  <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite" />
</div>

# 🚀 FinEdu AI - Gestão Financeira Local com IA

> **Status:** Full-stack | Foco em Educação Financeira | Estudo Acadêmico (UNICID)

O **FinEdu AI** é uma plataforma de gestão financeira pessoal que ajuda iniciantes a controlarem gastos e entenderem sobre investimentos. Diferente de aplicações complexas, esta versão foi projetada para rodar **localmente de forma simples**, utilizando SQLite para persistência de dados, eliminando a necessidade de configurações pesadas de banco de dados.

---

## 🌟 Funcionalidades Principais

* **📊 Dashboard Inteligente:** Gráficos de despesas por categoria e evolução financeira usando **Recharts**.
* **💸 Controle Total:** CRUD completo de receitas e despesas (fixas e variáveis) com cálculo automático de saldo.
* **🧠 Recomendações Educativas:** Sugestões baseadas em dados reais de investimentos (Tesouro Selic, CDB, LCI/LCA, FIIs e ETFs).
* **🤖 Chatbot Financeiro:** Assistente para dúvidas financeiras com suporte a IA (OpenAI) e modo de fallback local.
* **🔒 Segurança:** Autenticação com JWT em cookies HttpOnly e criptografia de senhas com Bcrypt.
* **📱 Interface Moderna:** Design estilo fintech, responsivo e com suporte a Skeletons e Toasts para melhor UX.

---

## 🛠️ Tecnologias Utilizadas

* **Framework:** Next.js (App Router) + React + TypeScript
* **Estilização:** Tailwind CSS + Lucide React
* **Banco de Dados:** SQLite (Prisma ORM) - *Roda localmente sem configuração externa*
* **Validação:** Zod
* **IA:** OpenAI SDK (Integrado)

----


---

## 📸 Screenshots
<p align="center">
  <img src="<img width="1864" height="947" alt="Image" src="https://github.com/user-attachments/assets/8aced04c-dbcc-438e-abb6-3f23a9a52c4d" />" width="45%" />
  <img src="<img width="1867" height="948" alt="Image" src="https://github.com/user-attachments/assets/bf2de9b6-fbf7-475d-8192-d7265c7c24d0" />
" width="45%" />
</p>

---

## 📁 Estrutura de Pastas

```txt
finedu-ai/
  ├── prisma/          # Schema do banco e scripts de setup (SQLite)
  ├── src/app/         # Rotas da aplicação e API Routes
  ├── src/components/  # UI Components (Dashboards, Forms, Layout)
  ├── src/services/    # Lógica do Chatbot e Recomendações de IA
  └── src/lib/         # Utilitários, autenticação e validações
  
