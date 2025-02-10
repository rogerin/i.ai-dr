Aqui está a versão atualizada da descrição do projeto para o GitHub, incluindo a funcionalidade de integração com o Google Drive e o uso do Supabase para armazenar e gerenciar os documentos utilizados no treinamento do modelo:

i.ai Dr – Agente RAG para n8n e WhatsApp

🚀 i.ai Dr é um agente conversacional baseado em RAG (Retrieval-Augmented Generation), desenvolvido para integrar o n8n e WhatsApp, trazendo respostas mais inteligentes e contextuais a partir de uma base de conhecimento específica.

🛠️ Criado durante o HackaHealth, o projeto visa facilitar o acesso a informações médicas e aprimorar a comunicação automatizada, utilizando modelos de IA e fluxos de automação no n8n.

✨ Principais Recursos
	•	🔍 RAG (Retrieval-Augmented Generation) – Melhoria na precisão das respostas, combinando recuperação de dados com geração de texto.
	•	🤖 Integração com n8n – Automação flexível para gerenciar interações no WhatsApp.
	•	📲 WhatsApp Bot – Comunicação em tempo real com pacientes ou usuários.
	•	🗂 Integração com Google Drive – O agente acessa arquivos armazenados em uma pasta no Google Drive para treinar o modelo e enriquecer a base de conhecimento.
	•	💾 Supabase como Database – O Supabase é utilizado para armazenar os documentos recuperados do Google Drive, permitindo downloads e consultas rápidas.
	•	🔄 Extensível e Personalizável – Pode ser ajustado para diferentes bases de conhecimento e necessidades.

🚀 Como Funciona?

1️⃣ O usuário envia uma pergunta pelo WhatsApp.
2️⃣ O agente consulta uma base de conhecimento treinada a partir de documentos armazenados no Google Drive e salvos no Supabase.
3️⃣ O modelo de IA processa as informações e combina os dados recuperados com uma resposta gerada.
4️⃣ O n8n gerencia o fluxo da conversa e envia a resposta pelo WhatsApp.

🛠 Tecnologias Utilizadas
	•	n8n – Para automação e orquestração dos fluxos de conversa.
	•	OpenAI API – Para processamento e geração de linguagem.
	•	Vector Database – Para armazenamento e recuperação eficiente de informações.
	•	WhatsApp API – Para interação com os usuários.
	•	Google Drive API – Para acessar e baixar documentos usados no treinamento do modelo.
	•	Supabase – Para armazenar os arquivos e permitir o download eficiente dos documentos.

📌 Contribuindo

O projeto está aberto para melhorias! Sinta-se à vontade para abrir issues, enviar PRs ou sugerir novas funcionalidades.

🎯 Sobre o HackaHealth

Este projeto foi desenvolvido durante o HackaHealth, um evento focado em soluções tecnológicas para a área da saúde.

💡 Quer colaborar ou testar? Explore o repositório e contribua! 🚀

Se precisar de mais ajustes ou quiser adicionar instruções de instalação e configuração, me avise! 🔥
