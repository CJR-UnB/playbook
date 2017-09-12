# Nota fiscal

### O Que é?
A nota fiscal é documento essêncial para contabilidade da CJR. A CJR precisa emitir nota fiscal para TODO o dinheiro que passou pela conta corrente dela(mesmo que ele apenas passe pela conta). Nesse tutorial falarei sobre o processo de emitir nota com o sistema ja configurado e as configurações do zero.

OBS: É necessário ter um certificado digital
OBS2: As instruções serão baseadas no sistema [Omie](https://app.omie.com.br/login/), o email de login será: noe@cjr.org.br, a senha deve ser dada pelo atual NOE.
OBS3: Caso quando você estiver fazendo, o Omie não ser mais o sistema usado, acredito que as configurações da nota, do zero, ainda poderá ser util a você.
OBS4: Caso ainda reste maiores duvidas, o contador e responsável por tirá-las.

### Emissão de nota com  sistema ja configurado:
1) Apos fazer o login no sistema, clique em "Empresa junior de Computação CJR".

2) Vá em "Serviços e NFS-e"

3) caso a nota seja referente a um cliente novo, clique em cadastrar cliente, e siga os seguintes passos:

- Clique em incluir, na side bar
- Clique em pesquisar por CNPJ, ou em pesquisa autônoma, digite o cnpj e boa parte dos dados já seŕa preenchido, mas ainda será necessário preencher manualmente alguns dados.
- É necessario que todas as partes do endereço estejam preenchidas
- Na aba telefones e email, é necessario ter o email tb. caso você não tenha o email do cliente, coloque o email da noe msm.
- Na aba inscrições, CNAE e Outros, é necessário colocar a inscrição estadual e municipal do cliente, caso o cliente seja do DF, as duas serão a msm(estadual).
- Confira os dados novamente(não vai ser legal caso eles estejam errados)
- OBS: Nos contratos é colocado a inscrição estadual e o cnpj dos clientes, basta olhar lá. caso você não saiba qual a inscrição estudual, e não esteja no contrato, é possível encontra-la no site do cfdf.

- OBS2: Caso o cliente seja estrangeiro, basta colocar EX, na opição de escolha de estado. Só será necessário o email, o endereço e o telefone.

4) Com o cliente ja cadastrado, vá em "Cadastrar Ordens de serviço e Faturar"

5) Vá na aba de faturados e cliquem em duplicar OS.
- OBS: Os valores de impostos já esarão todos configurados na nota.
- OBS2: Caso o cliente seja do exterior, duplique uma nota do exterior, pois não pagamos impostos para exportação de serviço. 

6) Vá na nota duplicada e clique na lupa para alterar o cliente, selecione o cliente desejado e altere o preço para o proço do projeto.

7) Confira os dados para garantir que tudo está em ordem
- OBS: A quantidade de items e ISS fica igual, apenas mudar o valor

8) Após terminar clique em conferir, se estiver tudo ok, arraste a nova nota até faturar, altomaticamente a nota será faturada. Espere por volta de 5min, e clique em "Verificar se a prefeitura respondeu". caso a nota esteja verde, otimo! Ela foi emitida.

9) Caso a nota esteja vermelha:
- Entre na nota
- Clique em "Nota Fiscal Rejeitada!".
- Clique na mensagem que possuir um clipes de papel.
- Olhe o XML de retorno(procure la falando onde houve o erro(geralmente fica no final))
- Conserte o erro e reenvie a nota ;)
- OBS: Notas enviadas mas não faturadas podem dar ruim, o Omie para CJR é de graça até 100mil de faturamento, porem esses 100mil estão inclusos com as notas que foram falhadas. Logo: caso voce precise enviar uma nota de 6mil 3 vezes até ela ser aprovada, o Omie já considerou 18mil de faturamento. fique esperto!

10) Após terminar esse processo, entre no email da noe, pegue a nota recebida, pdf e xml, e coloque no drive em:
Financeiro/Seu Ano/Notas fiscais emitidas/Seu mês, coloque a pdf dentro dessa pasta e a xml na pasta xml(ainda dentro da pagina).

####FIM!

### Configuração dos impostos, manual:

1) Valores dos impostos:
- ISS: 5%
- Cofins: 7.6%
- OBS: Projeto do exterior não paga impóstos

2) Ao abrir a nota fiscal, ao lado do local do valor, há o campo "Alíquota ISS(%)", coloque "5"

3) Logo abaixo tem uma lupa escrito "Visualizar impostos e retenções", clique e coloque "7.6" em "% Alíquota do COFINS"
- NÃO MARCAR RETIDO

####FIM!


### Configuração do sistema todo:

1) No canto superior você verá uma engrenagem, clique nela.

2) Vá em dados da Minha empresa, então coloque:
- CNPJ: 03.632.310/0001-17
- Telefone de contato(Presidente ou NOE)
- Endereço(caso não tenha sido preenchido altomáticamente)
- "Telefones e Emails", coloque email da NOE: noe@cjr.org.br
- "Mapa", caso o local não tenha sido marcado sozinho, marque você mesmo.
- "Inscrições CNAE e Outros"
	- Inscrição Estadual e Municipal: 0740743300169
	- Tipo de atividade: Prestação de Serviços
	- Regime Tributário: Regime Normal - Lucro Real
	- CNAE: 8550302 Atividades de apoio á educação, exceto caixas escolares

- "Nota fiscal e produto", as notas fiscais não podem ter numeros repetidos, Procure no Drive ou pergunte ao contador quando foi a ultima nota emitida. Se não encontrar, troque a série da nota(apenas se precisar msm), e recomeçe pela 1.
	- OBS: Atualmente(12/09/2017) estamos na série 2.

- "Notas fiscais e serviços"
	- marque: Gerar Notas Fiscais Eletrônicas de Serviço (NFS-e) na Prefeitura

3) Em Categorias, selecione: "Receitas Diretas"

4) Em Departamentos, coloque o Organograma da CJR, caso seja de interesse.

5) Em Certificado Digital, adicione o seu certificado A1.

6) vendedores e projetos são apenas caso você queira cadastrar algum vendedor específico, para definir quel fechou a negociação.

####FIM DAS PRINCIPAIS CONFIGURAÇÕES
####QUALQUER OUTRA DÚVIDA, O CONTADOR DEVE SEER CAPAZ DE RESOLVER
