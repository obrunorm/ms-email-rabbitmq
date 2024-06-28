# Microserviço email

Uma API desenvolvida em Java que utiliza do spring para enviar emails, foi criada para estudos sobre comunucação assíncrona e mensageria.


## Documentação da API

#### Retorna todos os itens

```http
  POST /sending-email
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `ownerRef` | `string` | **Obrigatório**. Uma referencia de quem está enviando o email |
| `emailFrom` | `string` | **Obrigatório**. O email que vai enviar a mensagem |
| `emailTo` | `string` | **Obrigatório**. O email que vai receber a mensagem |
| `subject` | `string` | **Obrigatório**. Assunto do email |
| `text` | `string` | **Obrigatório**. Corpo do email |


#### Retorna se o email foi enviado ou não



