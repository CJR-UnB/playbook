# 3.4 Nota Fiscal

## O que é?

A nota fiscal é um documento essencial para a contabilidade da CJR. A CJR precisa emitir notas fiscais para TODO o dinheiro que passar pela sua conta corrente \(mesmo que este apenas passe pela conta\). Nesse tutorial falarei sobre o processo de emissão da nota através do sistema já configurado ou começando a configuração do zero.

OBS: É necessário ter um certificado digital. OBS2: As instruções serão baseadas no sistema [Omie](https://app.omie.com.br/login/). O email de login será: noe@cjr.org.br e a senha deve ser escolhida pelo atual NOE. OBS3: Se o sistema utilizado não for mais o Omie acredito que a parte "Configuração do sistema todo" ainda possa ser útil para você. OBS4: Caso ainda reste maiores dúvidas o contador deve auxiliá-lo.

## Emissão de nota com  sistema já configurado:

1\) Após fazer o login no sistema clique em "Empresa Júnior de Computação CJR".

2\) Vá em "Serviços e NFS-e".

3\) Caso a nota seja referente a um cliente novo, clique em cadastrar cliente e siga os seguintes passos:

* Clique em incluir na side bar.
* Clique em pesquisar por CNPJ ou em pesquisa autônoma. Digite o CNPJ, boa parte dos dados será preenchida automaticamente, preencha manualmente os que sobrarem.
* OBS: A pesquisa pode ser feita pelo CPF caso o cliente seja pessoa física.
* É necessário que todas as partes do endereço estejam preenchidas.
* Na aba telefones e email, é preciso informar o email, caso você não tenha o email do cliente use o email da NOE.
* Na aba inscrições, CNAE e Outros, é necessário colocar a inscrição estadual e municipal do cliente. Se este for do DF, as duas serão a mesma \(estadual\).
* OBS: Nos contratos é colocado a inscrição estadual e o CNPJ dos clientes, basta procurar. Se a inscrição estadual não constar no contrato, procure no site do CF/DF.
* OBS2: Se o cliente for pessoa física, tanto a inscrição estadual quanto a municipal devem ser preenchidas com a palavra: 'ISENTO'.
* OBS3: Quando o cliente for estrangeiro coloque EX na opção de escolha do estado. Nesse caso será necessário o email, o endereço e o telefone.
* Confira os dados novamente \(é sério confira mesmo\).

4\) Com o cliente ja cadastrado vá em "Cadastrar Ordens de serviço e Faturar".

5\) Vá na aba de faturados e clique em duplicar OS.

* OBS: Os valores dos impostos já estarão todos configurados na nota.
* OBS2: Caso o cliente seja do exterior, duplique uma nota do exterior, pois não pagamos impostos para exportação de serviço. 

6\) Vá na nota duplicada e clique na lupa para alterar o cliente, selecione o cliente desejado e altere o preço para o preço do projeto.

7\) Confira os dados para garantir que tudo está em ordem.

* OBS: A quantidade de items e ISS fica igual apenas mude o valor.

8\) Após terminar clique em conferir, se estiver tudo ok arraste a nova nota até faturar, automaticamente a nota será faturada. Espere por volta de 5 minutos e clique em "Verificar se a prefeitura respondeu". SE a nota estiver verde, ótimo! Ela foi emitida.

9\) Se a nota estiver vermelha:

* Entre na nota.
* Clique em "Nota Fiscal Rejeitada!".
* Clique na mensagem que possuir um clipes de papel.
* Olhe o XML de retorno \(procure o local que explica o erro este geralmente está no final\).
* Conserte o erro e reenvie a nota.
* OBS: Notas enviadas, porém não faturadas, podem trazer problemas. O Omie é de graça para até 100 mil de faturamento, entretanto esses 100 mil imcluem as notas que falharam, então considerando que você precise enviar uma nota de 6 mil reais 3 vezes até esta ser aprovada, o Omie irá considerar 18mil de faturamento, fique esperto!
* OBS2: Clique varias vezes no primeiro campo html para aparecer o xml de retorno, onde será possível ver qual foi o erro cometido.

10\) Após terminar este processo entre no email da NOE, pegue a nota recebida \(pdf e xml\) e coloque no drive em: Financeiro/Seu Ano/Notas fiscais emitidas/Seu mês, coloque o pdf dentro dessa pasta e a xml na pasta xml \(na mesma página\).

### FIM!

## Configuração dos impostos manual:

1\) Valores dos impostos:

* ISS: 5%
* Cofins: 7.6%
* OBS: Projetos do exterior não pagam impostos.

2\) Ao abrir a nota fiscal, ao lado do local do valor há o campo "Alíquota ISS\(%\)", coloque "5".

3\) Logo abaixo tem uma lupa com a frase "Visualizar impostos e retenções" clique e coloque "7.6" em "% Alíquota do COFINS".

* NÃO MARCAR RETIDO.

### FIM!

## Configuração do sistema todo:

1\) No canto superior você verá uma engrenagem então clique nela.

2\) Vá em dados da Minha empresa, coloque:

* CNPJ: 03.632.310/0001-17
* Telefone de contato \(Presidente ou NOE\).
* Endereço \(caso não tenha sido preenchido automaticamente\).
* "Telefones e Emails", coloque email da NOE: noe@cjr.org.br
* "Mapa" caso o local não tenha sido marcado sozinho, marque você mesmo.
* "Inscrições CNAE e Outros"
  * Inscrição Estadual e Municipal: 0740743300169
  * Tipo de atividade: Prestação de Serviços
  * Regime Tributário: Regime Normal - Lucro Real
  * CNAE: 8550302 Atividades de apoio á educação, exceto caixas escolares
* Em "Nota fiscal e produto" as notas fiscais não podem conter números repetidos. Procure no Drive ou pergunte ao contador quando foi a última nota emitida. Se não encontrar, troque a série da nota \(apenas se for necessario\) e recomeçe pela 1.
  * OBS: Atualmente \(12/09/2017\) estamos na série 2.
* "Notas fiscais e serviços"
  * marque: Gerar Notas Fiscais Eletrônicas de Serviço \(NFS-e\) na Prefeitura

3\) Em Categorias, selecione: "Receitas Diretas"

4\) Em Departamentos, coloque o Organograma da CJR, caso seja de interesse.

5\) Em Certificado Digital, adicione o seu certificado A1.

6\) Vendedores e projetos são apenas quando quiserem cadastrar algum vendedor específico \(para definir quem fechou a negociação\).

### FIM DAS PRINCIPAIS CONFIGURAÇÕES

### QUALQUER OUTRA DÚVIDA, O CONTADOR DEVE SER CAPAZ DE RESOLVER

