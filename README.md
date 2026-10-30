# combine-seu-curriculo-com-a-descricao-da-vaga
Criação de uma landing page para combinar o seu currículo com a descrição da vaga de emprego

## Qual problema a minha aplicação resolve

A aplicação resolve o gargalo da triagem automatizada (ATS) no recrutamento moderno. 

Ela elimina a frustração dos candidatos ao diagnosticar de forma transparente o alinhamento com 

a vaga (match e palavras-chave) e automatizar a reescrita do currículo. Diferente de outras 

ferramentas, ela faz isso de forma ética e segura: otimiza a apresentação profissional do 

candidato sem nunca inventar experiências que ele não possui.

## O mega prompt utilizado

Crie uma aplicação web moderna, limpa e responsiva para matchmaking de vagas de emprego e otimização de currículos com foco em ATS (Applicant Tracking System), construída com React, Tailwind CSS e componentes do Shadcn/ui.

### 🎨 Identidade Visual e Paleta de Cores
A interface deve transmitir modernidade, acolhimento e clareza. Utilize rigorosamente a seguinte paleta de cores (baseada em tons pastéis suaves e elegantes sobre fundo limpo):
- **Branco (`#FFFFFF` ou `bg-white` / `bg-slate-50`):** Para áreas de fundo principal e cartões, garantindo respiro e legibilidade.
- **Rosa Bebê (`#FFD1DC` / tons suaves de `rose-200`/`rose-300`):** Utilizado em botões de destaque secundários, detalhes sutis, badges e elementos de atenção delicados.
- **Verde Água (`#A2E8DD` / tons pastéis de `teal-200`/`emerald-200`):** Utilizado para indicadores de sucesso, barras de progresso do *match*, tags de palavras-chave encontradas e botões de ação principal positivos.
- **Amarelo Claro (`#FFF3B0` / tons suaves de `amber-100`/`yellow-100`):** Utilizado para alertas, palavras-chave faltantes e avisos informativos.

### 📋 Funcionalidades e Fluxo Principal (Core)
A aplicação deve funcionar em uma interface fluida (layout em painel dividido ou abas limpas):

1. **Entrada de Dados (Inputs):**
   - **Campo 1:** Textarea ou input para a pessoa colar a **Descrição da Vaga**.
   - **Campo 2:** Textarea para a pessoa colar o seu **Currículo Atual**.

2. **Aviso Ético Obrigatório (Regra de Ouro):**
   - Exiba um card de destaque ou banner claro na interface com o texto: 
     > *"Nossa IA melhora a forma como você se apresenta, mas **nunca** inventa experiências que você não tem. Sua integridade profissional em primeiro lugar."*

3. **Processamento e Análise (Matchmaking):**
   - Um botão chamativo ("Analisar Currículo e Otimizar") que dispara a simulação da IA.
   - **Métrica de Match:** Exibição visual da porcentagem de compatibilidade (ex: componente circular ou barra de progresso em Verde Água).
   - **Análise de Palavras-Chave:**
     - Seção de **Palavras-Chave Encontradas** (badges em verde água).
     - Seção de **Palavras-Chave Faltantes** (badges em amarelo claro).

4. **Geração do Currículo ATS-Friendly:**
   - Exibição da versão ajustada do currículo em uma caixa de texto formatada ou pré-visualização limpa.
   - Botões de ação rápida: **"Copiar Texto"** e **"Exportar / Baixar"** (com feedback visual de sucesso).

### 🛠️ Requisitos Técnicos
- Utilize **Shadcn/ui** para todos os componentes (Botões, Cards, Badges, Progress bars, Textareas, Tabs).
- Design minimalista, elegante, com bordas arredondadas suaves (`rounded-xl` ou `rounded-2xl`) e tipografia limpa.
- Estado interativo funcional na interface (permitindo simular a análise ao colar os textos e clicar no botão).

## Mudanças trazidas ao markdown para adaptação e melhoria da versão

<img width="759" height="655" alt="image" src="https://github.com/user-attachments/assets/5b631360-9df4-480e-852f-56a5b7a874f8" />

Crie uma aplicação web moderna, limpa e responsiva para matchmaking de vagas de emprego e otimização de currículos com foco em ATS (Applicant Tracking System), construída com React, Tailwind CSS e componentes do Shadcn/ui.

---

### 🔐 Autenticação e Integração com Resend
A aplicação deve conter um fluxo de acesso seguro para os usuários:
- **Telas de Autenticação (Login & Cadastro):**
  - Formulário de login com e-mail e senha usando componentes do Shadcn/ui (`Form`, `Input`, `Button`).
  - Fluxo de criação de conta (Sign Up) com validação de campos.
- **E-mail de Confirmação (Resend):**
  - Configurar conector do **Resend** para disparar automaticamente um e-mail de verificação ao criar uma nova conta.
  - Exibir estado/tela de **"Verifique seu E-mail"** após o cadastro, com opção de reenviar o código/link de confirmação.
  - Template visual do e-mail com design limpo e alinhado à identidade visual da marca.
- **Gestão de Sessão:**
  - Proteger as rotas principais da aplicação (o gerador e analisador de currículo só devem ser acessíveis após o login/confirmação).

---

### 🎨 Identidade Visual e Paleta de Cores
A interface deve transmitir modernidade, acolhimento e clareza. Utilize rigorosamente a seguinte paleta de cores (baseada em tons pastéis suaves e elegantes sobre fundo limpo):
- **Branco (`#FFFFFF` ou `bg-white` / `bg-slate-50`):** Para áreas de fundo principal e cartões, garantindo respiro e legibilidade.
- **Rosa Bebê (`#FFD1DC` / tons suaves de `rose-200`/`rose-300`):** Utilizado em botões de destaque secundários, detalhes sutis, badges e elementos de atenção delicados.
- **Verde Água (`#A2E8DD` / tons pastéis de `teal-200`/`emerald-200`):** Utilizado para indicadores de sucesso, barras de progresso do *match*, tags de palavras-chave encontradas e botões de ação principal positivos.
- **Amarelo Claro (`#FFF3B0` / tons suaves de `amber-100`/`yellow-100`):** Utilizado para alertas, palavras-chave faltantes e avisos informativos.

---

### 📋 Funcionalidades e Fluxo Principal (Core)
Após o usuário estar autenticado, a aplicação exibe um painel fluido com o fluxo principal:

1. **Entrada de Dados (Inputs):**
   - **Campo 1:** Textarea ou input para a pessoa colar a **Descrição da Vaga**.
   - **Campo 2:** Textarea para a pessoa colar o seu **Currículo Atual**.

2. **Aviso Ético Obrigatório (Regra de Ouro):**
   - Exiba um card de destaque ou banner claro na interface com o texto:
     > *"Nossa IA melhora a forma como você se apresenta, mas **nunca** inventa experiências que você não tem. Sua integridade profissional em primeiro lugar."*

3. **Processamento e Análise (Matchmaking):**
   - Um botão chamativo ("Analisar Currículo e Otimizar") que dispara a simulação da IA.
   - **Métrica de Match:** Exibição visual da porcentagem de compatibilidade (componente circular ou barra de progresso em Verde Água).
   - **Análise de Palavras-Chave:**
     - Seção de **Palavras-Chave Encontradas** (badges em verde água).
     - Seção de **Palavras-Chave Faltantes** (badges em amarelo claro).

4. **Geração do Currículo ATS-Friendly:**
   - Exibição da versão ajustada do currículo em uma caixa de texto formatada ou pré-visualização limpa.
   - Botões de ação rápida: **"Copiar Texto"** e **"Exportar / Baixar"** (com feedback visual via Toast do Shadcn/ui).

---

### 🛠️ Requisitos Técnicos
- Utilize **Shadcn/ui** para todos os componentes (Botões, Cards, Badges, Progress bars, Textareas, Tabs, Forms e Toasts).
- Layout responsivo, minimalista e elegante, com bordas arredondadas suaves (`rounded-xl` ou `rounded-2xl`) e tipografia limpa.
- Integração funcional com o conector do **Resend** para envio de e-mails transacionais.

## No lovable

https://combine-seu-curriculo-com-a-vaga.lovable.app/

<img width="1912" height="1008" alt="image" src="https://github.com/user-attachments/assets/7d5da458-14dd-459a-8e34-e858c218e268" />

<img width="1912" height="1008" alt="image" src="https://github.com/user-attachments/assets/66229d79-35ae-4e21-a6f3-6c3aa565a19a" />


## Como a análise funciona, da vaga colada até o currículo ajustado

<img width="1185" height="813" alt="image" src="https://github.com/user-attachments/assets/abd90fb0-a5b7-4452-9182-7ba2b989c23b" />

<img width="1185" height="741" alt="image" src="https://github.com/user-attachments/assets/13734d69-f45f-4915-8005-19a4f3239b94" />

<img width="1185" height="700" alt="image" src="https://github.com/user-attachments/assets/fb135390-8fa6-4104-9026-ea5ed8d9884a" />

<img width="1185" height="930" alt="image" src="https://github.com/user-attachments/assets/fa86e5dd-094b-46b1-aec9-ea00fbe430ca" />

<img width="1185" height="930" alt="image" src="https://github.com/user-attachments/assets/455989de-8771-4d33-b5a3-caa600b6ed9f" />

<img width="1185" height="930" alt="image" src="https://github.com/user-attachments/assets/ea48b458-b8a3-45a5-9d1c-37bd5ab1f3b0" />

## Que ajustes você pediu depois da primeira geração, e por quê













