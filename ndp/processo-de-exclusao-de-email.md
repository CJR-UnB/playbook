# Processo de Exclusão de Email

Para realizar este processo o membro deve ter acesso de administrador das contas da CJR. Ele deve requisitar ao Líder de Desenvolvimento e Pesquisa esse acesso.

Antes da exclusão da conta do usuário deve-se realizar uma série de passos.

### Redefinindo a Senha

O primeiro passo para a exclusão do usuário é a redefinição da senha do mesmo. Para isso, acesse [o painel de administração do Google Suite](http://admin.google.com), vá em **Usuários**, clique em **Redefinir senha** no usuário escolhido.

Defina a senha como `backup123` e confirme a mesma. Deixe a opção **Solicitar alteração de senha no próximo acesso** desmarcada. Clique em **Redefinir** e depois em **Concluído**.

### Fazendo backup dos dados

O próximo passo é realizar o backup dos dados do usuário, para o caso do mesmo necessitar de uma consulta posterior.

Acesse o [Google Takeout](https://takeout.google.com/settings/takeout) com o e-mail da conta do usuário e a senha que acabou de ser redefinida.

Na seção **Selecionar dados a serem incluídos** clique no botão **Não selecionar nenhum** e após isso selecione os serviços:

- Agenda
- Drive
- E-mail

Clique em **Próxima**.

Na seção **Personalizar formato de arquivo** deixe o **Tipo de arquivo** como `.zip`, o **Tamanho de arquivo (máx)** como `2 GB` e o **Método de exibição** como `Enviar link de download por e-mail`. Após isso, clique em **Criar arquivo**.

O processo de criação de arquivo geralmente demora alguns minutos, porém, de acordo com o tamanho dos dados do usuário, pode demorar horas ou até dias. Fique de olho no e-mail do usuário, a Google notificará quando o(s) arquivo(s) estiver(em) pronto(s) para download.

Quando for notificado, baixe o arquivo acessando o link enviado por e-mail ou através [deste link](https://takeout.google.com/settings/takeout/downloads).

Ao finalizar o download do arquivo, o renomeie para `email.zip`, onde `email` é o email da conta do usuário. No caso de haver mais de um arquivo renome para `email(i).zip`, onde `i` é o número da parte do arquivo e coloque todos numa pasta de nome `email`. Esses arquivos devem estar no HD externo da CJR.

### Exclusão da conta

Agora que o backup dos dados já foi feito, retorne ao [o painel de administração do Google Suite](http://admin.google.com), vá em **Usuários** e clique nos três pontos, selecionando a opção **Excluir** do usuário em questão.

Antes da exclusão, os arquivos do membro devem ser transferidos para uma outra conta. A princípio, os arquivos serão passados para a conta do seu núcleo antes de deixar a empresa.

Marque a opção **Drive and Docs** e deixe a opção **Também incluir dados não compartilhados com outras pessoas** desmarcada. Clique em **Atribuir um novo proprietário destes dados**. Em **Atribuir um novo proprietário** coloque o e-mail do núcleo.

- Núcleo de Atendimento e Marketing: nam@cjr.org.br
- Núcleo de Desenvolvimento e Pesquisa: ndp@cjr.org.br
- Núcleo de Organização Empresarial: noe@cjr.org.br
- Núcleo de Talentos: nut@cjr.org.br
- Presidência: presidencia@cjr.org.br

Temos também as diretorias antigas. Neste caso usaremos também os e-mails dos núcleos relativos:

- Diretoria Administrativo Financeira -> Núcleo de Organização Empresarial
- Diretoria de Negócios -> Núcleo de Atendimento e Marketing
- Diretoria de Projetos -> Núcleo de Desenvolvimento e Pesquisa
- Diretoria de Tecnologia de Informação -> Núcleo de Desenvolvimento e Pesquisa
- Presidência Organizacional/Presidência Institucional -> Presidência

Após inserir o e-mail do núcleo, clique em **Transferir dados e excluir conta**.