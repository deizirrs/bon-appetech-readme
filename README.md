# Bon AppéTech 🍽️ - Agente de IA Culinária

[![Status](https://img.shields.io/badge/Status-Online-brightgreen)](https://bon-appetech.onrender.com/)

**Bon AppéTech** é um assistente culinário inteligente movido a IA. Ele transforma ingredientes que você já tem em receitas criativas e personalizadas, com instruções detalhadas e dicas extras.

---

## 🌐 Acesse o site

Confira a aplicação em produção: [https://bon-appetech.onrender.com](https://bon-appetech.onrender.com/)

> **Digite um ingrediente ou o nome de uma receita e veja a mágica acontecer!**

---

## ✨ Funcionalidades

- 🗣️ **Chat Intuitivo:** Converse como se fosse um chef — pergunte e receba respostas em tempo real.
- 📋 **Formato Organizado:** Títulos, ingredientes, modo de preparo e sugestões extras, tudo à mão.
- 🎨 **Animações Fluídas:** Interface animada ao scroll com AOS, para uma experiência leve.
- 💬 **Markdown Rich:** Textos renderizados com `markdown` para uma apresentação elegante.
- 🔄 **Memória de Contexto:** A IA lembra etapas anteriores e evita repetições.
- 📱 **Design Responsivo:** interface adaptável para dispositivos móveis e desktops sem perder qualidade de experiência.

---
## 📊 Fluxo de Comunicação

```mermaid
graph LR
    A[Front End] -- Mensagem do Usuário --> B[Back End]
    B -- Prompt + Mensagem --> C[OpenAI API]
    C -- Resposta GPT --> B
    B -- Resposta formatada --> A
````
---

## 🚀 Tecnologias

| Camada       | Ferramentas                                        |
| ------------ | -------------------------------------------------- |
| **Frontend** | React • Vite • Tailwind CSS • AOS • react-markdown |
| **Backend**  | Node.js • Express • CORS • dotenv                  |
| **IA**       | OpenAI GPT-4o-mini                                 |
| **HTTP**     | Axios                                              |
| **Dev**      | Nodemon • ESLint                                   |

---

### 📊 Diagrama de Fluxo Bon AppéTech

```mermaid
graph LR
    A[Front End] --> B[Rota]
    B --> C[Controller]
    C --> D[Service]
    D --> E[OpenAI API]
    E --> D
    D --> C
    C --> B
    B --> A
```

## 🧑‍🍳 Como Usar

No [Bon AppéTech](https://bon-appetech.onrender.com), experimente:

* Colocar **"frango, arroz e curry"**
* Ou pedir **"Receita de bolo de cenoura"**
* Testar combinações inusitadas como **"abacaxi e pimenta"**

E veja as sugestões criadas pela IA em tempo real!

---

## 📣 Acesso Exclusivo ao repositório do projeto

Este projeto está em um **repositório privado** para manter nosso código seguro e exclusivo. Se você é recrutador e deseja avaliar o código:

* Envie um e-mail para **[deizianerodriguesdev@hotmail.com](mailto:deizianerodriguesdev@hotmail.com)**
   
* Ou conecte-se no LinkedIn e mande uma mensagem: **[@deizianer](https://www.linkedin.com/in/deizianer/).**

Prometo retorno rápido com o convite de acesso! 🚀

---

## ✨ Desenvolvido por

**[Deiziane Rodrigues](https://www.linkedin.com/in/deizianer/).**

---

*Aproveite o Bon AppéTech e transforme sua cozinha em um laboratório de sabores!*
