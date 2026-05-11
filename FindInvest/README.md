# 🚀 FinEdu AI - Gestão Financeira com IA

> **Status do Projeto:** Em desenvolvimento / Estudo acadêmico (UNICID)

Plataforma Full-stack de gestão financeira pessoal desenvolvida para auxiliar usuários iniciantes na organização de gastos e introdução ao mundo dos investimentos, com arquitetura preparada para integração com Inteligência Artificial.

---

## 🌟 Destaques e Funcionalidades

O **FinEdu AI** foi projetado com os padrões modernos de uma fintech:

* **📊 Dashboard Completo:** Visualização em tempo real de receitas, despesas e saldo mensal com gráficos interativos (Recharts).
* **🔐 Autenticação Segura:** Sistema de login com JWT (cookies HttpOnly), criptografia de senha com Bcrypt e proteção de rotas.
* **💡 Recomendações Inteligentes:** Algoritmo educativo que sugere investimentos (CDB, Selic, FIIs) com base no perfil e saldo do usuário.
* **🤖 Chatbot Financeiro:** Interface moderna para tirar dúvidas sobre finanças, preparada para conexão com a API da OpenAI (GPT-4o).
* **📱 Responsividade:** Layout totalmente adaptável para dispositivos móveis e desktop usando Tailwind CSS.

---

## 🛠️ Stack Tecnológica

### **Frontend**
* **Framework:** Next.js 14 (App Router)
* **Linguagem:** TypeScript
* **Estilização:** Tailwind CSS
* **Biblioteca de Gráficos:** Recharts
* **Ícones:** Lucide React

### **Backend & Infraestrutura**
* **Runtime:** Node.js
* **ORM:** Prisma (PostgreSQL)
* **Segurança:** JWT, BcryptJS, Zod (validação)
* **Containerização:** Docker & Docker Compose

---

## 📁 Arquitetura do Sistema

O projeto utiliza uma arquitetura full stack moderna, separando responsabilidades por camadas:

```txt
src/
 ├── app/             # Rotas, Páginas e API Routes (Next.js)
 ├── components/      # Componentes de UI e Reutilizáveis
 ├── lib/             # Configurações globais e Utilitários
 ├── services/        # Lógica de IA e Regras de Negócio
 └── prisma/          # Modelagem do Banco de Dados
