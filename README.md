# 🧭 Guia: Como Criar um Copiloto – Agente de Viagens no Microsoft Copilot Studio

Este repositório fornece um passo a passo completo para criar um **Copiloto personalizado** usando o **Microsoft Copilot Studio**, ideal para empresas ou profissionais que desejam automatizar **assistentes de planejamento de viagens**.

---

## ✅ 1. Criar uma Conta no Microsoft 365 com Copilot

- Acesse: [Microsoft 365](https://www.microsoft.com/pt-br/microsoft-365)
- Inscreva-se com uma conta que possua uma licença válida para o **Microsoft 365 Copilot**.
- Verifique se a conta tem **permissões administrativas** para criar ambientes e soluções no Power Platform.

---

## 🔧 2. Configurar o Ambiente de Desenvolvedor no Power Platform

1. Vá para o [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/).
2. Crie um novo ambiente:
   - Clique em **Administração > Ambientes > Novo Ambiente**
   - Nome: `Dev Viagens`
   - Tipo: `Desenvolvedor`
   - Região: selecione sua região preferida
3. Confirme se o ambiente está ativo e vinculado à sua conta do Microsoft 365.

---

## 🧩 3. Criar uma Solução no Power Apps

1. Acesse: [Power Apps Studio](https://make.powerapps.com/)
2. No menu lateral, clique em **Soluções**
3. Crie uma nova solução:
   - Nome: `Agente de Viagens`
   - Ambiente: selecione o ambiente criado anteriormente
4. Clique em **Criar** e depois em **Publicar Tudo**

---

## 🤖 4. Criar e Configurar o Agente no Copilot Studio

### Opção 1: Agente Baseado em Modelo

- Acesse o [Copilot Studio](https://studio.web.powerva.microsoft.com/)
- Clique em **Criar Agente**
- Escolha: **Baseado em Modelo**
- Preencha:
  - Nome: `Agente de Viagens`
  - Descrição: `Assistente para planejamento de viagens nacionais e internacionais`
  - Adicione fontes de conhecimento, como:
    - Documentos no SharePoint
    - Conectores do Microsoft Graph

---

### Opção 2: Agente Baseado em Descrição com IA

- Clique em **Criar Agente**
- Selecione: **Baseado em Descrição**
- Descreva o objetivo do agente:
  > “Este agente ajuda os usuários a planejar viagens, oferecendo opções personalizadas com base no perfil do viajante, incluindo destino, orçamento, transporte e hospedagem.”
- O Copilot Studio irá gerar fluxos e tópicos automaticamente.
- Revise e edite os fluxos conforme necessário.

---

### Opção 3: Copiloto em Branco

- Clique em **Criar Agente**
- Selecione: **Copiloto em Branco**
- Configure manualmente:
  - Tópicos personalizados
  - Frases de gatilho como “Quero viajar”, “Planejar férias”, “Sugestões de destinos”
  - Fluxos de conversa com condições, respostas, APIs e chamadas externas se necessário

---

## 🧪 5. Testar e Publicar o Agente

- Use o **modo de teste interativo** no Copilot Studio
- Simule perguntas reais, como:
  - “Quais são os destinos recomendados para julho?”
  - “Planeje uma viagem com orçamento de R$ 3.000”
- Ajuste respostas e fluxos conforme o feedback
- Clique em **Publicar** para disponibilizar o agente à sua organização

---

## 📌 Requisitos Técnicos

- Microsoft 365 com Copilot habilitado
- Permissões de administrador no Power Platform
- Acesso ao Copilot Studio (Power Virtual Agents)
- Navegador compatível (Edge, Chrome, Firefox)

---

## 📂 Estrutura Recomendada do Projeto

