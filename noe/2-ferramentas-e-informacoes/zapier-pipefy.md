# 2.5 Pipefy e Zapier

## Como funcionam as automações no Zapier e Pipefy

Em 2019 o Pipefy junto com o Zapier foram utilizados para automatizar processos de coleta de indicadores, cobrança de pagamentos e atualização da casa da moeda.

## Os Pipes
### Pipe de Reembolsos

Pipe criado para pedidos de reembolso, onde cada um pode criar um card pedindo o que foi gasto e anexando a nota fiscal do mesmo.
Passa pela fase de triagem, aprovado ou recusado, quando recusado com o motivo do recuso sendo enviado pro email da pessoa. Quando aprovado vai pra fase
de recibo onde um recibo é gerado e enviado por email.

### Automações

Zap - Reembolso aprovado deduz da tabela de Casa da Moeda

### Pipe de Cobrança de Pagamentos

### Automações

### Pipe de Projetos

Pipe criado para gerenciamento dos projetos. Quando um projeto é aceito, seu card é adicionado nesse pipe, contendo as seguintes informações:
- Nome do projeto;
- Cliente;
- Negociador;
- Se o projeto é fidelizado e/ou conectado;
- Gerente e desenvolvedores alocados.

Quando um projeto é finalizado ele deve ser movido para NPS1.

### Automações

Zap - Alocação de membros: quando o card do projeto é criado, a planilha de membros do Planejamento Estratégico 2019 com a coluna "Alocado atualmente?" de cada desenvolvedor e gerente tendo seu valor atualizado para "Alocado". 
Zap - Desaloca membro: quando o card é movido para NPS1, a planilha de membros do Planejamento Estratégico 2019 com a coluna "Alocado atualmente?" de cada desenvolvedor e gerente tendo seu valor atualizado para "Desalocado". 
