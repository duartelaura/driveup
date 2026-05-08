# [cite_start]3.3.3 Processo 3 - Solicitar Aulas Práticas [cite: 55]

[cite_start]O processo 3 inicia-se com o aluno decidindo agendar suas aulas práticas. [cite: 59] [cite_start]Após comunicar seu interesse à autoescola, a mesma deverá verificar se o aluno pode cursar as aulas práticas, tendo como requisito ter cursado as 40 aulas obrigatórias do curso teórico e ter sido aprovado no exame teórico. [cite: 60] [cite_start]Caso o aluno cumpra com todos estes requisitos, será um usuário válido para seguir com o processo. [cite: 61] 

[cite_start]O atendente da autoescola deverá verificar as disponibilidades em aberto na agenda de instrutores e veículos e notificar o aluno. [cite: 62] [cite_start]Caso o aluno selecione um horário ainda disponível, o atendente confirma o horário da aula agendada e notifica o aluno; [cite: 63] [cite_start]caso contrário, o aluno é notificado dos novos horários disponíveis. [cite: 64] [cite_start]Após a confirmação, o atendente agenda oficialmente as aulas e notifica o instrutor. [cite: 65] [cite_start]Por fim, são emitidas as guias de pagamento referentes às aulas agendadas. [cite: 66]

## [cite_start]Detalhamento das atividades [cite: 56, 67]

* [cite_start]**Filtrar horário desejado**: o aluno escolhe o horário que mais se adequa a sua realidade. [cite: 69]
* [cite_start]**Escolher instrutor**: o aluno visualiza os instrutores disponíveis e escolhe um de acordo com suas preferências. [cite: 70]
* [cite_start]**Solicitar aula**: ao escolher o horário e o instrutor, o aluno deve confirmar a solicitação por meio de um botão de envio. [cite: 71]
* [cite_start]**Notificar aluno da necessidade de pagamento das aulas**: mensagem com aviso da liberação do processo de pagamento e instruções. [cite: 72]
* [cite_start]**Confirmar pagamento**: a autoescola atualiza o sistema com confirmação de pagamento. [cite: 73]
* [cite_start]**Notificar aluno da reserva de aula**: mensagem confirmando reserva do horário e do instrutor escolhidos. [cite: 74]
* [cite_start]**Enviar confirmação de aulas**: mensagem com a confirmação das aulas e instruções adicionais. [cite: 75]

## [cite_start]Filtrar horário desejado [cite: 76]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
[cite_start]| horários disponíveis | seleção única | campo de opções | [cite: 77] |

## [cite_start]Escolher instrutor [cite: 79]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
[cite_start]| horários disponíveis | seleção única | campo de opções | [cite: 80] |
| nome do aluno | [cite_start]Caixa de Texto | mínimo de 8 caracteres | [cite: 80] |
[cite_start]| nome do instrutor | seleção única | campo opções | [cite: 80] |
| data | data | dd-mm-aaaa | [cite_start]01/01/2001 [cite: 80] |
| horário | hora | hh:mm:ss | [cite_start]00:00:00 [cite: 80] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
[cite_start]| selecionar | fluxo agendar com instrutor | seleção [cite: 81] |

## [cite_start]Solicitar Aula [cite: 82]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
[cite_start]| horários disponíveis | seleção única | campo de opções | [cite: 83] |
| nome do aluno | [cite_start]Caixa de Texto | mínimo de 8 caracteres | [cite: 83] |
[cite_start]| nome do instrutor | seleção única | campo opções | [cite: 85, 86, 89] |
| data | data | dd-mm-aaaa | [cite_start]01/01/2001 [cite: 90, 91, 92, 93] |
| horário | hora | hh:mm:ss | [cite_start]00:00:00 [cite: 94, 95, 96, 97] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| agendar | [cite_start]Fim do Processo 3 | default [cite: 101, 102] |

## [cite_start]Confirmar pagamento [cite: 103]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Checkbox | Seleção única | required | [cite_start]Null [cite: 104] |
| Confirmação | Seleção única | required | [cite_start]Null [cite: 104] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| Selecionar pagamento | [cite_start]Enviar confirmação | [cite: 105] |
