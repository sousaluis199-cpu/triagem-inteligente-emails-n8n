📧 Triagem Inteligente de E-mails com n8n e IA

Automação de triagem de e-mails utilizando n8n, Gmail, JavaScript e Inteligência Artificial.

📌 Sobre o projeto

Este projeto tem como objetivo desenvolver uma automação capaz de auxiliar na triagem de e-mails recebidos pelo Gmail, utilizando regras de processamento e um modelo de IA.

A proposta é identificar mensagens que merecem atenção prioritária com base no contexto, nos prazos e nas possíveis consequências de atrasos, sem depender exclusivamente de palavras como "urgente" ou "urgência".

🎯 Objetivo

Explorar como a automação e a IA podem ajudar a organizar e-mails, reduzir tarefas manuais e facilitar a identificação de mensagens importantes.

🛠️ Tecnologias utilizadas

- n8n: criação e execução de workflows de automação.
- Gmail: integração para receber e enviar mensagens.
- JavaScript: processamento e tratamento de dados.
- Inteligência Artificial: análise contextual, conforme a integração configurada.

⚙️ Fluxo de automação

O workflow inclui os seguintes componentes:

1. Gmail Trigger: inicia o fluxo a partir do recebimento de e-mails, conforme a configuração.
2. Code in JavaScript: processa os dados da mensagem.
3. Code in JavaScript1: executa outra etapa de processamento.
4. If: avalia uma condição e direciona a execução.
5. Send a message: envia uma mensagem pelo Gmail quando o caminho configurado é acionado.

🧪 Status do projeto

Em desenvolvimento e validação.

O workflow foi exportado do n8n e publicado neste repositório. A classificação de urgência pelo contexto ainda precisa ser testada com diferentes exemplos de e-mails para verificar sua precisão.

🔒 Segurança e privacidade

- Não publique senhas, tokens ou credenciais.
- Não compartilhe dados pessoais nem conteúdo real de e-mails.
- Revise o JSON exportado antes de disponibilizá-lo publicamente.
- Utilize dados fictícios para demonstrações e testes.

📚 Aprendizados

Este projeto faz parte do meu aprendizado prático em automação de processos, integração de serviços, JavaScript e Inteligência Artificial.

🚀 Próximas melhorias

- Validar a identificação de mensagens prioritárias sem palavras-chave explícitas.
- Testar diferentes cenários de e-mails.
- Melhorar as regras de classificação.
- Documentar os resultados dos testes.
- Adicionar capturas de tela do workflow.

---

Desenvolvido como projeto prático de automação com n8n e IA.
