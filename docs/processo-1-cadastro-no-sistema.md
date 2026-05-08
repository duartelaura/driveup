# [cite_start]3.3.1 Processo 1 - Solicitar comprovante de presença [cite: 165]

[cite_start]O Processo de ter a presença comprovada nas aulas teóricas e práticas pode ser melhorado através da oportunidade de fornecer ao aluno uma visualização automatizada do progresso realizado por ele durante a etapa de aulas, tanto práticas quanto teóricas, necessárias para a obtenção da CNH. [cite: 166]

## [cite_start]Detalhamento das atividades [cite: 180]

* [cite_start]**Solicitar comprovante de presença**: Através da interface do sistema, o aluno solicita validação de presença em uma aula específica. [cite: 181]
* [cite_start]**Visualizar solicitação do aluno**: Através de um procedimento automatizado do sistema, uma mensagem informa à autoescola a respeito da solicitação do aluno. [cite: 182]
* [cite_start]**Verificar lista de presença da aula prática**: A autoescola verifica manualmente a presença do aluno na lista de presença fornecida pelo instrutor responsável. [cite: 183]
* [cite_start]**Validar presença no site**: A autoescola valida a presença do aluno no site, caso o aluno esteja presente na lista de presença fornecida pelo instrutor responsável. [cite: 184]
* [cite_start]**Negar solicitação de presença**: A autoescola nega a solicitação do aluno, caso o aluno não esteja presente na lista de presença fornecida pelo instrutor responsável. [cite: 185]
* [cite_start]**Enviar resposta a solicitação do aluno**: O sistema envia a resposta da solicitação vinda da autoescola para o aluno. [cite: 186]
* [cite_start]**Visualizar resultado da solicitação**: O aluno visualiza a resposta da autoescola quanto à solicitação que ele fez (Aprovada ou Negada). [cite: 187]
    * [cite_start]Caso aprovada, o dashboard pessoal do aluno é atualizado com a presença confirmada. [cite: 188]
    * [cite_start]Caso negado, o aluno recebe uma mensagem alegando ausência dele na lista de presença da aula solicitada. [cite: 189]

## [cite_start]Solicitar comprovante de presença [cite: 190]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Nome | [cite_start]Caixa de Texto | mínimo de 5 caracteres | [cite: 191] |
| Email | [cite_start]Caixa de Texto | formato de e-mail | [cite: 191] |
| Tipo da aula | [cite_start]Área de texto | required | [cite: 191] |
| Data da aula | Data | required | [cite_start]01/01/2001 [cite: 191] |
| Horário da aula | Hora | required | [cite_start]00:00:00 [cite: 191] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| Solicitar | [cite_start]Envio da solicitação à autoescola | default [cite: 192] |

## [cite_start]Validar presença no site [cite: 193]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Nome | [cite_start]Caixa de Texto | mínimo de 5 caracteres | [cite: 194] |
| Email | [cite_start]Caixa de Texto | formato de e-mail | [cite: 194] |
| Tipo da aula | [cite_start]Área de texto | required | [cite: 194] |
| Data da aula | Data | required | [cite_start]01/01/2001 [cite: 194] |
| Horário da aula | Hora | required | [cite_start]00:00:00 [cite: 195] |
| Mensagem | Área de texto | [cite_start]| [cite: 195] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| Validar presença | [cite_start]Confirmar presença do aluno | [cite: 195] |

## [cite_start]Negar presença no site [cite: 196]

| Campo | Tipo | Restrições | Valor default |
| :--- | :--- | :--- | :--- |
| Nome | [cite_start]Caixa de Texto | mínimo de 5 caracteres | [cite: 197] |
| Email | [cite_start]Caixa de Texto | formato de e-mail | [cite: 197] |
| Tipo da aula | [cite_start]Área de texto | required | [cite: 197] |
| Data da aula | Data | required | [cite_start]01/01/2001 [cite: 197] |
| Horário da aula | Hora | required | [cite_start]00:00:00 [cite: 197] |
| Mensagem | Área de texto | [cite_start]| [cite: 197] |

| Comandos | Destino | Tipo |
| :--- | :--- | :--- |
| Negar presença | [cite_start]Confirmar presença do aluno | [cite: 198] |
