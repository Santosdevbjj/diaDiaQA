## Projeto: O Dia a Dia de um QA: A Prática de Testes Manuais Funcionais.

![Screenshot_20250619-155415](https://github.com/user-attachments/assets/a826781a-106a-4400-b248-30c2e36f832b)

  
**Bootcamp, WEX - End to End Engineering.**



# 🧪 O Dia a Dia de um QA - Testes Manuais Funcionais

Projeto desenvolvido durante o **Bootcamp WEX - End to End Engineering**, com foco na prática de **testes manuais funcionais** em um ambiente ágil utilizando **Scrum**, **JIRA** e **Confluence**.

## 📌 Objetivo

- Compreender e aplicar conceitos essenciais de testes manuais.
- Executar atividades típicas da rotina de um QA.
- Realizar testes funcionais manuais no sistema SwagLabs.
- Documentar fluxos de trabalho e user stories.
- Criar e executar casos de teste utilizando técnicas **Step-by-Step** e **BDD** com linguagem **Gherkin**.

## 🛠️ Tecnologias e Ferramentas Utilizadas

- 🔹 SwagLabs: https://www.saucedemo.com/v1/
- 🔹 JIRA: Gerenciamento ágil de tarefas e testes
- 🔹 Confluence: Documentação colaborativa
- 🔹 Zephyr Scale: Gerenciamento de testes manuais
- 🔹 PDF (FPDF Python): Geração de relatórios
- 🔹 XMind / Miro: Mind-map

## 📂 Estrutura do Projeto

📁 docs/
 ┣ 📄 Documentacao_QA_SwagLabs.pdf         
 ┣ 📄 Casos_Teste_QA_SwagLabs.pdf          
 ┣ 🖼️ Fluxograma_Login_QA.png   
 ┗ 🧠 Login_MindMap.xmind

## 🧾 User Stories Criadas

### ✅ Story 1 - Login com sucesso
> Como usuário, desejo acessar o sistema com credenciais válidas para acessar meu inventário.

### ❌ Story 2 - Login com erro
> Como usuário, desejo ser informado quando inserir dados incorretos para tentar novamente.

## 🧪 Casos de Teste

### 🎯 Step-by-Step
- Login com sucesso
- Login com usuário inválido

### 📘 BDD (Gherkin)
```gherkin
Feature: Validação de Login
Scenario: Login com credenciais válidas
  Given que estou na tela de login
  When insiro "standard_user" e "secret_sauce"
  Then sou redirecionado à tela de inventário
```

## 🔄 Fluxo de Trabalho no JIRA

- 📌 Backlog
- 🚧 To Do
- 👨‍💻 In Progress
- 🧪 Em Teste
- ✅ Done
- 🐞 Bugs: [Reportado → Em correção → Validado → Fechado]

## 📌 Como Executar os Testes

1. Acesse o ambiente de testes: https://www.saucedemo.com/v1/
2. Use os dados fornecidos (usuário/senha)
3. Execute os casos conforme descrito nos PDFs
4. Registre os resultados no JIRA/Zephyr

## 📚 Conclusão

Este projeto representa uma simulação prática e profissional do papel do QA em ambientes ágeis, com documentação clara, testes bem definidos e integração de ferramentas reais de mercado.

## 👤 Autor

**Sérgio Santos**  
📧 [LinkedIn](https://www.linkedin.com/in/seu-usuario-linkedin/)  
📘 Projeto QA | Bootcamp WEX End to End Engineering. 


 
