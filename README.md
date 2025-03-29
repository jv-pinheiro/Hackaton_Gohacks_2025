# GoHacks - Equipe 9 - MVP

## 📌 Descrição
Este projeto é um MVP desenvolvido durante o hackathon GoHacks 2025. O objetivo é criar uma automação no N8N para auxiliar a aquisição e qualificação de leads para a empresa Gocase, por meio de um chatbot interativo integrado ao site da marca.

## 🚀 Funcionalidades
- **Chatbot interativo**: Um assistente virtual responsivo para auxiliar os clientes a encontrar produtos na loja.
- **Processamento de linguagem natural**: Utiliza a API OpenAI (GPT-4o-mini) para entender e responder consultas.
- **Memória de conversa**: O chatbot armazena o histórico da conversa para uma interação mais fluida.
- **Webhooks**: Integração de mensagens em tempo real via Webhook.
- **Interface personalizada**: O chat está estilizado para se integrar ao site da Gocase.

## 🛠 Tecnologias Utilizadas
- **N8N**: Plataforma de automação de workflows.
- **OpenAI GPT-4o-mini**: Para processamento de linguagem natural.
- **HTML, CSS e JavaScript**: Para personalização da interface.


## 📖 Como Utilizar
1. **Importe o workflow** no N8N utilizando os arquivos JSON fornecidos.
2. **Configure as credenciais** do OpenAI caso necessário.
3. **Ative os Webhooks** para permitir a interação em tempo real.
4. **Teste o chatbot** simulando consultas no site.

## 📌 Fluxo do Workflow
1. O **usuário inicia uma conversa** no chat.
2. A mensagem é capturada pelo **gatilho de Webhook**.
3. A IA processa a consulta utilizando o **OpenAI GPT-4o-mini**.
4. A resposta é retornada ao chat.
5. O histórico da conversa é armazenado para referência futura.

## 🏆 Contribuição
Este projeto foi desenvolvido durante o **GoHacks**. Sinta-se à vontade para expandi-lo ou adaptá-lo a novas necessidades.

