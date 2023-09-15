# Especificação do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 01: Doador(a) Regular</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Pessoas que já doaram sangue várias vezes e querem contribuir com frequência.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
⦁ Acompanhar seu histórico de doações para saber quando será a próxima doação elegível.<br>
⦁ Receber notificações regulares sobre datas de coleta e lembretes para agendar doações.<br>
⦁ Acesso a informações sobre seus resultados de exames e estatísticas de suas doações anteriores.
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 02: Novo Doador(a) </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Pessoas que estãointeressadas em doar sangue pela primeira vez.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
⦁ Instruções claras sobre como se tornar um doador, incluindo o processo de triagem e agendamento.<br>
⦁ Orientações sobre o que esperar antes, durante e após a doação.<br>
⦁ Incentivos para encorajar a primeira doação e reduzir a ansiedade
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 03: Possível Doador(a) </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Pessoas que estão interessadas na doação de sangue, mas ainda não se decidiram.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
⦁	Informações sobre os benefícios da doação de sangue e como ele impacta na saúde e na comunidade.<br>
⦁	Depoimentos e informações sobre como o processo de doação é seguro.<br>
⦁	Casos de sucesso e histórias que os façam querer doar.</td>
</tr>
</tbody>
</table>

## Histórias de Usuários

[Apresente aqui as histórias de usuários que são relevantes para o projeto da solução.]

> **Link Útil**:
> - [Como escrever boas histórias de usuário](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

[Utilize o modelo de tabela abaixo para apresentar as histórias de usuários.]

|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
| Novo Doador(a)     | cadastrar para realizar doação de sangue     | que eu possa doar.                            |
| Doador(a)          | responder questionário                       | verificar se é possível doar.                 |
| Doador(a)          | saber a importância da doação de sangue      | conscientizar.                                |
| Doador(a)          | consultar a quantidade de sangue em estoque  | verificar a emergência de cada tipo sanguíneo.|
| Doador(a)          | compartilhar conteúdo                        | que possa conscientizar outras pessoas        |
| Enfermeiro(a)      | visualizar cadastros de doadores             | que eu possa programar e planejar a consulta. |
| Enfermeiro(a)      | viar e-mail para doadores cadastrados        | informar algum imprevisto.                    |

## Requisitos do Projeto

### Requisitos Funcionais

[Utilize o modelo de tabela abaixo para apresentar os requisitos funcionais]

|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 |  O sistema deve permitir que o usuário faça um cadastro.                     | ALTA   | 
|  RF-02  |  O sistema deve possuir um formulário de triagem para avaliar a elegibilidade do doador antes de doar.                    | ALTA   |
|  RF-03  |  O sistema deve fornecer informações sobre a importância e os benefícios da doação de sangue.                     | ALTA   |
|  RF-04  |  O sistema deve mostrar a quantidade de cada tipo sanguíneo disponível.                    | ALTA   |
|  RF-05  |  O sistema deve permitir que enfermeiros visualizem os cadastros de doadores para planejar consultas e coletas de sangue.                     | MÉDIA   |
|  RF-06  |  O sistema deve permitir que enfermeiros enviem e-mails aos doadores cadastrados para informar sobre imprevistos ou atualizações.                    | MÉDIA   |
|  RF-07  |  O sistema deve permitir que usuários compartilhem informações educativas sobre doação de sangue em suas redes sociais.                     | BAIXA   |


**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais

[Utilize o modelo de tabela abaixo para apresentar os requisitos não-funcionais]

|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 | O sistema deve ser acessível em todos os navegadores.               | Alta   | 
| RNF-02 | O sistema deve conter somente front-end.                            | Média  | 
| RNF-03 | O sistema deve ser desenvolvido por HTML, CSS e Javascript.         | Média  | 
| RNF-04 | O sistema deve permitir que o cadastro seja feito em até 2 minutos. | Baixa  | 

**Prioridade: Alta / Média / Baixa. 

