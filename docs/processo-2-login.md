# [cite_start]3.3.2 Processo 2 - Solicitar Prova [cite: 122]

[cite_start]Planejamos otimizar a solicitação de prova automatizando as atividades e tornando mais objetiva a comunicação do aluno com a autoescola. [cite: 123] [cite_start]Por parte do estudante será apenas necessário solicitar a prova (diretamente pelo sistema), receber a autorização da autoescola, em seguida pagar as taxas requeridas e por fim receber seu local e data de prova. [cite: 124] [cite_start]Por outro lado, o funcionário da autoescola irá pelo sistema checar os requisitos necessários para marcar a prova e enviar a resposta ao aluno, dessa forma simplificando todo o processo. [cite: 125]

## [cite_start]Detalhamento das atividades [cite: 126]

* [cite_start]**Solicitar a prova**: O aluno solicita a prova que deseja realizar. [cite: 127]
* [cite_start]**Receber solicitação do aluno**: A autoescola recebe a solicitação feita pelo aluno. [cite: 128]
* [cite_start]**Verificar carga horária de aulas teóricas**: A autoescola verifica a carga horária das aulas teóricas. [cite: 129]
* [cite_start]**Verificar carga horária de aulas práticas**: A autoescola verifica a carga horária das aulas práticas. [cite: 130]
* [cite_start]**Solicitar pagamento das taxas da prova**: A autoescola envia a solicitação do pagamento das taxas para realização da prova. [cite: 131]
* [cite_start]**Negar solicitação do aluno**: A autoescola nega a solicitação feita pelo aluno. [cite: 132]
* [cite_start]**Visualizar resposta da solicitação**: O aluno visualiza a resposta dada pela autoescola. [cite: 133]
* [cite_start]**Pagar taxas da prova**: O aluno paga as taxas da prova. [cite: 134]
* [cite_start]**Receber pagamento**: A autoescola recebe o pagamento das taxas. [cite: 135]
* [cite_start]**Marcar prova do aluno**: A autoescola marca a prova do aluno. [cite: 136]
* [cite_start]**Informar aluno local e data da prova**: A autoescola informa o aluno o local e data da prova. [cite: 137]
* [cite_start]**Visualizar local e data da prova**: O aluno visualiza o local e data da prova. [cite: 138]

## [cite_start]Solicitar a prova [cite: 139]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Nome | [cite_start]Caixa de Texto | mínimo de 5 caracteres | [cite: 140] |
| Email | [cite_start]Caixa de Texto | formato de e-mail | [cite: 140] |
| Tipo de prova | [cite_start]Seleção Única | required | [cite: 140] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| Solicitar prova | [cite_start]Enviar solicitação à autoescola | default [cite: 141] |

## [cite_start]Verificar carga horária de aulas [cite: 142]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Nome | [cite_start]Caixa de Texto | mínimo de 5 caracteres | [cite: 143] |
| Email | [cite_start]Caixa de Texto | formato de e-mail | [cite: 143] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| Verificar carga horária | [cite_start]Visualizar carga horária | [cite: 144] |

## [cite_start]Informar ao aluno local e data da prova [cite: 145]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Nome | [cite_start]Área de Texto | mínimo de 5 caracteres | [cite: 146] |
| Local | Área de Texto | formato de local | [cite_start]Endereço [cite: 146] |
| Data | Área de texto | formato de data | [cite_start]01/01/2001 [cite: 146] |
| Hora | Área de texto | formato de hora | [cite_start]00:00:00 [cite: 146] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| [cite_start]Enviar informações | visualização das informações pelo aluno | default [cite: 147] |
