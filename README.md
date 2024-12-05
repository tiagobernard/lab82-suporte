# Passo-apasso para acessar o webmail e configurar o Outlook dos e-mails da Lab82

## Verifique a senha pro visória enviada por Whatsapp.
 
## 1. Acessar o Webmail do cPanel
*1. Acesse o Webmail:*
   - No navegador, digite: https://webmail.seudominio.com.br ou [clique aqui](https://webmail.lab82.dev)

*2. Faça o login:*
   - Informe o endereço de e-mail completo (ex.: email@seudomio.com.br).
   - Insira a senha correspondente.

*3. Escolha a interface do Webmail:*
   - Após o login, será solicitado que escolha entre opções como Roundcube, Horde ou RainLoop. Escolha a interface preferida (normalmente o Roundcube é mais intuitivo). Para escolhe-lo, clique no botão em azul "Open".

## 2. Trocar a Senha do E-mail
1. Acesse o webmail conforme o passo anterior.
2. No canto superior direito, clique no endereco de e-mail.
3. Selecione Security & Password.
4. Insira a nova senha e confirme. Clique em Salvar.
---

 3. Configurar o Outlook
 Antes de Começar:
- Você precisará das configurações de servidor do e-mail:
  - Servidor de entrada (IMAP): `mail.nisano.com.br`
  - Servidor de saída (SMTP): `mail.nisano.com.br`
  - Portas:
    - IMAP: 993 (SSL/TLS ativo)
    - SMTP: 465 (SSL/TLS ativo) ou 587 (STARTTLS ativo)
  - Nome de usuário: Endereço de e-mail completo.
  - Senha: A senha configurada para o e-mail.

 No Outlook:
1. Adicione uma nova conta de e-mail:
   - Abra o Outlook.
   - Vá em Arquivo > Adicionar Conta.

2. Configuração automática:
   - Insira o e-mail e clique em Conectar.
   - Insira a senha e clique em Concluir.
   - Caso isso não funcione, siga para a configuração manual.

3. Configuração manual:
   - Escolha Configuração Avançada > IMAP/POP.
   - Preencha os dados:
     - Tipo de conta: IMAP (recomendado) ou POP3.
     - Servidor de entrada: mail.nisano.com.br | Porta: 993 (IMAP).
     - Servidor de saída: mail.nisano.com.br | Porta: 465 (SMTP).
     - Ative a opção Exigir autenticação do servidor de saída.

4. Teste as configurações:
   - Clique em Avançar. O Outlook verificará as configurações.
   - Se tudo estiver correto, clique em Concluir.
---

Caso precise de suporte adicional ou queira um tutorial mais específico, estou à disposição! 😊