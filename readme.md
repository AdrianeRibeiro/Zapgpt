# Fluxo

1. Enviar mensagem para o whatsapp pelo Twilio

2. Twilio faz uma chamada para o endpoint especificado (programa em go)

3. O programa Go recebe a notificação e manda para a API do chat, retornando a resposta para o twilio.

# Ferramentas

- aws, twilio, ChatGPT

# Deploy

1. `serverless create --template aws-go-mod`

2. `make build`

3. `serverless deploy`

4. `Após o deploy, configurar a url no twilio`
   - Quando a mensagem chegar, o twilio avisa a url configurada na aws


# Referência

https://www.youtube.com/watch?v=87iV8v2CRvU
