# Plano de Testes de Software


Pré-requisitos: Especificação do Projeto e Projeto de Interface

<span style="color:red">Pré-requisitos: <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/Amigo-Sangue-Bom/blob/main/documentos/02-Especifica%C3%A7%C3%A3o%20do%20Projeto.md"> Especificação do Projeto</a></span>, <a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/Amigo-Sangue-Bom/blob/main/documentos/04-Projeto%20de%20Interface.md"> Projeto de Interface</a>



Os testes funcionais a serem realizados na aplicação são descritos a seguir.

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-01: Identificar o funcionamento de links da página Principal</td>
  <td>
   <ul>
    <li>RF-01: O sistema deve permitir que o usuário faça um cadastro.</li>
   <li>RF-02: O sistema deve possuir um formulário de triagem para avaliar a elegibilidade do doador antes de doar.</li>
   <li>RF-03: O sistema deve fornecer informações sobre a importância e os benefícios da doação de sangue.</li>
    <li>RF-04: O sistema deve mostrar a quantidade de cada tipo sanguíneo disponível.</li>
    <li>RF-06: O sistema deve permitir que usuários compartilhem informações educativas sobre doação de sangue em suas redes sociais.</li>
   </ul>
  </td>
  <td>Verificar se os menus de navegação e butões estão funcionais e com o direcionamento correto.</td>
  <td>
   <ol>
    <li>Acessar o navegador</li>
    <li>Informar o endereço do site</li>
    <li>Visualizar a página principal.</li>
    <li>Clicar nos links e butões da página.</li>
   </ol>
   </td>
  <td>Todos os links da página principal devem encaminhar os usuários para as respectivas páginas.</td>
  <td>Brian</td>
 </tr>
</table>


<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-02: Identificar os níveis atuais de Estoque de Sangue</td>
  <td>
   <ul>
    <li>RF-04: O sistema deve mostrar a quantidade de cada tipo sanguíneo disponível.</li>
   </ul>
  </td>
  <td>Verificar se a tela principal traz informações atuais sobre os níveis de estoque de sangue para que o doador saiba o melhor momento para doar</td>
  <td>
   <ol>
    <li>Acessar o navegador</li>
    <li>Informar o endereço do site</li>
    <li>Acessar página principal</li>
    <li>Rolar o scroll do mouse para a área de estoque de sangue</li>
   </ol>
   </td>
  <td>A área de estoque de sangue deve conter todos os tipos sanguíneos e o nível atual de estoque para cada um deles.</td>
  <td>Brian</td>
 </tr>
</table>

 
<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-02: Verificar o formulario de triagem  r</td>
  <td>
   <ul>
    <li>RF-02: O sistema deve possuir um formulário de triagem para avaliar a elegibilidade do doador antes de doar .</li>
   </ul>
  </td>
  <td> O fomulario de triagem deve abranger questionamentos essenciais para eleger ou não um doador </td>
  <td> 
   <ol>
    <li>Acessar o navegador</li>
    <li>Informar o endereço do site</li>
    <li>Acessar página principal</li>
    <li>Acessar a area de Como Doar</li>
    <li>Clicar na opção "Validar"</li>
   </ol>
   </td>
  <td>Após o preenchimento do formlário ele devera retornar com um resposta se é ou não elegivel.</td>
  <td>Ranan</td>
 </tr>
</table>
