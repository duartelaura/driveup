# CH Manager - Processo 3 - Exemplo

imcathalatUpdate processo-3-solicitar-aula-pratica.md 0f073a0 · 4 months agoICEI-PUC-Minas-PMGES-TI /
pmg-es-2024-1-ti2-3687100-cnh-manager
Code Issues1 Pull requests Actions Projects Security I
 main
pmg-es-2024-1-ti2-3687100-cnh-manager/docs
/processo-3-solicitar-aula-pratica.md
87 lines (54 loc) · 5.13 KB
3.3.3 Processo 3 – Solicitar Aulas Práticas
Detalhamento das atividadesPreview Code Blame Raw

O processo 3 inicia-se com o aluno decidindo agendar suas aulas práticas. Após
comunicar seu interesse à autoescola, a mesma deverá, logo a seguir, veriﬁcar se o
aluno em questão trata-se de um aluno que pode cursar as aulas práticas, tendo como
requisito ter cursado as 40 aulas obrigatórias do curso teórico e ter sido aprovado no
exame teórico. Caso o aluno cumpra com todos estes requisitos, será um usuário
válido para seguir com o processo. O atendente da autoescola, então, deverá após
veriﬁcar as disponibilidades em aberto na agenda de instrutores e veículos e notiﬁcar o
aluno dos mesmos. Caso o aluno selecione um horário e o mesmo ainda esteja
disponível após sua análise, o atendente deverá conﬁrmar o horário da aula agendada
e notiﬁcar o aluno desta conﬁrmação; caso contrário, o aluno será notiﬁcado
novamente dos novos horários disponíveis, podendo optar a seguir ou não com o
processo. Após a conﬁrmação, o atendente agenda oﬁcialmente as aulas na agenda e
deverá notiﬁcar o instrutor em questão para que este esteja a par de sua nova agenda
de serviço. Por ﬁm, será emitido pelo atendente as guias de pagamento referentes às
aulas agendadas que serão encaminhadas ao aluno.
Os tipos de dados a serem utilizados são:
* Filtrar horário desejado - o aluno escolhe o horário que mais se adequa a sua
realidade
* Escolher instrutor - o aluno visualiza os instrutores disponíveis e escolhe um de
acordo com suas preferências
* Solicitar aula - ao escolher o horário e o instrutor, o aluno deve conﬁrmar a
solicitação por meio de um botão de envio.
* Notiﬁcar aluno da necessidade de pagamento das aulas - mensagem com aviso
da liberação do processo de pagamento e intruções.
* Conﬁrmar pagamento - a autoescola atualiza o sistema com conﬁrmação de
pagamento.
* Notiﬁcar aluno da reserva de aula - mensagem conﬁrmando reserva do horário e
do intrutor escolhidos.
* Enviar conﬁrmação de aulas - mensagem com a conﬁrmação das aulas e
instruções adicionais.
Filtrar horário desejado
Campo Tipo Restrições Valor default
horários
disponíveisseleção
únicacampo de opçõesDetalhamento das atividades

Campo Tipo Restrições Valor default
nome do alunoCaixa de
Textomínimo de 8
caracteres
nome do
instrutorseleção
únicacampo opções
data data dd-mm-aaaadata ao momento de
solicitação
horário hora hh:mm:sshora ao momento da
solicitação
Comandos Destino Tipo
selecionar escolher instrutor default
Escolher instrutor
Campo Tipo RestriçõesValor
default
horários
disponíveisseleção única campo de opções
nome do alunoCaixa de
Textomínimo de 8
caracteres
nome do instrutor seleção única campo opções
data data dd-mm-aaaa 01/01/2001
horário hora hh:mm:ss 00:00:00
Comandos Destino Tipo
selecionar fluxo agendar com instrutor seleção
Solicitar Aula
Campo Tipo RestriçõesValor
default
horários
disponíveisseleção única campo de opções
nome do alunoCaixa de
Textomínimo de 8
caracteres

Campo Tipo RestriçõesValor
default
nome do instrutor seleção única campo opções
data data dd-mm-aaaa 01/01/2001
horário hora hh:mm:ss 00:00:00
Comandos Destino Tipo
agendar Fim do Processo 3 default
Confirmar pagamento
Campo Tipo Restrições Valor default
Checkbox Seleção única required Null
Confirmação Seleção única required Null
Comandos Destino Tipo
Selecionar pagamento Enviar confirmação -
