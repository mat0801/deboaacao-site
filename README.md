# Projeto - De Boa Ação

"Doar é um ato de empatia e solidariedade! Nossa página conecta quem quer ajudar e quem mais precisa, promovendo esperança e dignidade."

Se quiser olhar o site, acesse pelo link: https://deboaacao.vercel.app/

Espero que goste

**De Boa Ação** é um projeto web que conecta pessoas a pontos de doação e serviços sociais gratuitos em São Paulo, promovendo empatia, solidariedade e inclusão social. Nosso foco está nos Objetivos de Desenvolvimento Sustentável da ONU (ODS 1, 2 e 10)

## 🗺️ Funcionalidade principal

- **Mapa interativo** com pontos de doação e serviços sociais.
- Navegação simples entre diferentes locais.
- Layout responsivo e acessível para diversas telas.

## 💬 Chatbot Interativo

O site conta com um chatbot inspirado em **Carolina Maria de Jesus**, uma figura histórica que representa a força das comunidades periféricas. Esse chatbot responde dúvidas sobre:

- ONGs e instituições sociais
- Cozinhas comunitárias
- Bancos de alimentos
- Serviços gratuitos
- A própria história de Carolina Maria de Jesus

As respostas são geradas dinamicamente, com base em um histórico de conversa e sugestões automáticas, utilizando integração com backend via API.

## 🧠 Tecnologias usadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- PYTHON (Flask)
- OpenRouter API
- CORS configurado para permitir chamadas apenas do domínio do frontend

##🔐 Segurança

O chatbot é acessado apenas por origens permitidas (https://deboaacao.vercel.app).

As requisições precisam de header Authorization: Bearer <key> (A chave é definida via variável de ambiente).

As mensagens são validadas antes de enviar ao OpenRouter.

## 📁 Estrutura de arquivos

```plaintext
📁 deboaacao/
│   ├── index.html          # Página principal
│   ├── style.css           # Estilo visual do site
│   ├── script.js           # Mapas, Interações e Lógica do chatbot
│   └── img/                # Ícones e imagens do projeto
    └── 📁 api/
        └── chat.js             # Endpoint para comunicação com o bot
│
├── 📁 backend/
│   ├── chatbot.py          # API Flask para servir o chatbot
│   ├── requirements.txt
     
      
      
      


```
Projeto acadêmico desenvolvido por estudantes engajados em transformar realidades com tecnologia e empatia.
