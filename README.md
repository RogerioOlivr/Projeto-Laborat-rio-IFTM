# 🎓 Projeto IFTM – Aplicativo de Cadastro de Eventos, Atividades e Comitês

Este é um projeto desenvolvido em **React Native** utilizando a biblioteca **Gluestack UI**, com o objetivo de criar uma aplicação mobile moderna e acessível para o **IFTM (Instituto Federal do Triângulo Mineiro)**.  
O app permite o **cadastro de eventos, atividades e comitês**, integrando componentes visuais responsivos, formulários dinâmicos e navegação intuitiva entre as telas.

---

## 🚀 Tecnologias Utilizadas

- ⚛️ **React Native**
- 🧩 **Gluestack UI** (`@gluestack-ui/themed`)
---

## 🧠 Objetivo do Projeto

O propósito do aplicativo é **modernizar o processo de cadastro e gerenciamento de informações acadêmicas** do IFTM, tornando mais prática a inserção de:
- Eventos institucionais (nome, tipo, data, modalidade e áreas)
- Atividades vinculadas (descrição, tipo e data)
- Comitês de avaliação (membros, e-mails, instituição e ficha de avaliação)

O app foi desenvolvido com foco em **usabilidade, clareza e acessibilidade**, seguindo os padrões de design system do **Gluestack UI**.

---


---

## 📱 Funcionalidades Principais

### 🗓️ Cadastro de Eventos (`EventoForm`)
- Nome do evento  
- Tipo (Acadêmico, Científico, Extensão, etc.)  
- Datas de início e término com **DatePicker**  
- Modalidade (Online, Presencial, Híbrido)  
- Seleção múltipla de áreas de conhecimento  

### 🧾 Cadastro de Atividades (`AtividadeForm`)
- Título e descrição  
- Tipo da atividade (Oficina, Curso, Mostra, etc.)  
- Data de início e término  
- Inscrição (Gratuita ou Paga)

### 👥 Cadastro de Comitês (`ComiteForm`)
- Nome, e-mail e instituição do membro  
- Seleção da ficha de avaliação  
- Navegação fluida entre etapas  

---

## 🧭 Navegação entre Telas

O projeto utiliza o **React Navigation (Stack Navigator)** para organizar as etapas do cadastro:

| Rota  | Componente | Descrição |
|-------|-------------|-----------|
| `Crud1` | `EventoForm` | Cadastro de Evento |
| `Crud2` | `AtividadeForm` | Cadastro de Atividade |
| `Crud3` | `ComiteForm` | Cadastro de Comitê |

---

## 🧰 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Projeto-IFTM-Gluestack.git


Acesse o diretório do projeto:

cd Projeto-IFTM-Gluestack


Instale as dependências:

npm install


Execute o aplicativo:

npx expo start

