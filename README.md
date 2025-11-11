# 💰 App Agente Financeiro Pessoal com Vibe Coding

---

## 📌 Contexto

Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas em linguagem natural.  
A proposta é tornar o controle financeiro mais leve e intuitivo, eliminando formulários manuais e planilhas complicadas.

---

## ❗ Problema

Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e oferecem pouca personalização.  
Quero resolver isso com uma experiência conversacional e recomendações automáticas de economia, adaptadas ao perfil do usuário.

---

## 🎯 Público-Alvo

Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações, especialmente iniciantes que nunca usaram apps financeiros.

---

## 🔑 Funcionalidades-Chave

- Registrar gastos via chat em linguagem natural  
- Classificar automaticamente as transações por categoria  
- Definir e acompanhar metas financeiras personalizadas  
- Receber dicas de economia do “Agente Financeiro” com tom amigável e educativo  
- Visualizar relatórios simples e personalizados com gráficos e insights

---

## ♿ Design Universal

A solução deve seguir os princípios de Design Universal, garantindo uma experiência acessível e intuitiva para o maior número possível de usuários.  
Isso inclui interface clara, linguagem simples, suporte a leitores de tela, contraste adequado, navegação por voz e adaptação a diferentes perfis de uso.

---

## 🤖 Entregável da IA

Gerar um plano de MVP com:

- As principais telas do app  
- Recursos técnicos necessários  
- Esboço de validação inicial para testar se o app cumpre seu propósito  

Usar tom educativo e linguagem acessível, em português.

---

## 💬 Interações com o Copilot

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document)  
> Analise esse código e me dê dicas de como funcionar corretamente.

---

## 🌐 Resultado Final no Site: https://joyful-banoffee-e43ea5.netlify.app/

![Dashboard do Agente Financeiro](https://github.com/user-attachments/assets/3cb9b94f-d558-4a1b-a8c1-ad6c3954a963)

---

## 💰 Agente Financeiro — Resumo de Funcionalidades

### 🧠 Inteligência de Chat
- Interface de conversa com o agente financeiro
- Interpretação de comandos como:
  - `saldo R$ 3036,00` → define saldo inicial
  - `600,00 aluguel` → registra gasto
  - `678,41 mercado` → registra gasto
- Respostas automáticas com validação, dicas e alertas

### 📊 Gráfico de Gastos por Categoria
- Visualização em pizza com categorias:
  - Moradia, Alimentação, Transporte, Lazer, Pagamento, Outros
- Atualização dinâmica conforme os gastos são registrados
- Detalhamento com valores e porcentagens

### 📋 Histórico de Transações
- Lista das últimas 10 transações
- Exibe data, descrição, categoria e valor
- Inclui detalhes como tipo de pagamento (crédito, débito, Pix) e nome do cartão ou banco

### 💼 Controle de Saldo
- Exibição do saldo disponível
- Atualização automática após cada gasto
- Alerta quando o gasto excede o saldo

### 🧠 Dicas Financeiras
- Sugestões personalizadas com base nos seus hábitos
- Destaque para a categoria com maior gasto

### 💾 Persistência de Dados
- Todos os dados são salvos localmente via `localStorage`
- Mantém saldo, gráfico e histórico mesmo após fechar o navegador

---

## 🧠 Reflexão

### ✅ O que funcionou bem?
- A estrutura visual do dashboard ficou clara e acessível  
- A categorização automática dos gastos funcionou corretamente na maioria dos casos  
- O gráfico de pizza atualiza dinamicamente e ajuda na visualização dos gastos  
- A persistência via `localStorage` manteve os dados mesmo após fechar o navegador  
- A interação via chat trouxe uma experiência mais intuitiva para registrar transações

### ❌ O que não funcionou como o esperado?
- A IA inicialmente não seguiu as instruções com precisão, o que gerou retrabalho  
- Algumas categorias como "pagamento" não estavam sendo reconhecidas no gráfico  
- O tempo gasto para ajustar detalhes foi maior do que o previsto  
- A comunicação com a IA exigiu paciência e clareza para evitar interpretações erradas  
- Os gastos como alimentação insistem em ficar na categoria "outros"

### 💡 O que aprendi sobre conversar com IAs?
- É importante ser objetiva e específica ao dar comandos  
- A IA pode ser útil, mas precisa de orientação clara para não extrapolar ou reinventar  
- Nem sempre a primeira resposta será a ideal — é preciso iterar e ajustar  
- A IA pode acelerar o processo, mas também pode atrasar se não houver alinhamento  
- A melhor colaboração acontece quando há respeito mútuo entre humano e máquina
