![](../img/arrow_direita.jpg)

## **Introdução**
<p align="justify">&emsp; O rastreamento de requisitos é utilizado para prover relacionamentos entre requisitos, arquitetura e implementação final do sistema e possibilita uma adequada compreensão dos relacionamentos de dependência entre requisitos e através dos artefatos de requisitos, de arquitetura e de implementação. A rastreabilidade pode ser implementada por um conjunto de <b>elos</b> ou <b>ligações</b> (links) entre requisitos inter-relacionados, entre requisitos e suas fontes, e entre requisitos e os componentes que os implementam. </p>

<p align="justify">&emsp;Para o estabelecimento da rastreabilidade <b>forward-from</b>, iremos criar uma tabela que mostre desde artefatos que abrangem vários requisitos até ser mostrado, para cada requisito, os seus critérios de aceitação e a(s) sua(s) tela(s) da funcionalidade implantada(s).</p>

## **Objetivo**

<p align="justify">&emsp;Para o estabelecimento da rastreabilidade forward-from, iremos criar uma tabela que mostre desde artefatos que abragem vários requisitos até ser mostrado, para cada requisito, os seus critérios de aceitação e a(s) sua(s) tela(s) da funcionalidade implantada(s).</p>

## Requisitos Funcionais

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID</th>
            <th>Descrição</th>
            <th>Critérios de Aceitação</th>
            <th>Tela da Funcionalidade</th>
        </tr>
    </thead>
    <tbody >
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="6">Acesso a aplicação</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Cadastro</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF01</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de criar uma nova conta </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US01">US01</a></td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US01#imagem-representativa">T01</a></td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="5">Login</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF02</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de logar utilizando o seu nome de usuário e uma senha definida por ele no momento do cadastro</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US02">US02</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US02#imagem-representativa">T02</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF03</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O sistema deve proporcionar segurança por meio de digital</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US03">US03</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US03#imagem-representativa">T03</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF04</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O sistema deve recuperar o nome do usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US04">US04</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US04#imagem-representativa">T04</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF05</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O sistema deve recuperar a senha do usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-oftware.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US05">US05</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US05#imagem-representativa">T05</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF06</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de sair do sistema</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US06">US06</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US06#imagem-representativa">T06</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="10">Área do usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3">Informação de Usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF07</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de visualizar as informações da conta</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US07">US07</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US07#imagem-representativa">T07</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF08</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário do sistema desejo visualizar os relatórios extras</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US08">US08</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US08#imagem-representativa">T08</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF09</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O sistema deve proporcionar o histórico de termos de contas</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US09">US09</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US09#imagem-representativa">T09</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3">Alterar dados de usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF10</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve definir ou alterar o seu perfil de investidor</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US10">US10</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US10#imagem-representativa">T10</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF11</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário pode alterar sua senha de acesso</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US11">US11</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US11#imagem-representativa">T11</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF12</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve alterar assinatura eletrônica</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US12">US12</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US12#imagem-representativa">T12</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="4">Área financeira</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF13</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar informações para declarar Imposto de Renda</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US13">US13</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US13#imagem-representativa">T13</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF14</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve retirar o seu informe de Rendimentos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US14">US14</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US14#imagem-representativa">T14</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF15</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve retirar dinheiro da minha conta rico</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US15">US15</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US15#imagem-representativa">T15</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF16</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar notas de corretagem</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US16">US16</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US16#imagem-representativa">T16</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="6">Apoio ao Usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="6">Atendimento ao Usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF17</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve falar com o atendimento da Rico</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US17">US17</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US17#imagem-representativa">T17</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">R53</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ter o suporte via FAQ</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US53">US53</td>
           <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US53#imagem-representativa">T53</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">R54</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ter o suporte via chat online</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US54">US54</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US54#imagem-representativa">T54</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">R55</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ter o suporte por telefone</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US55">US55</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US55#imagem-representativa">T55</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">R56</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ter o suporte por meio das mídias sociais</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US56">US56</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US53#imagem-representativa">T56</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF18</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve tirar dúvidas do sistema</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US18">US18</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US18#imagem-representativa">T18</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="34">Gerenciamento de Investimento</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="12">Informações Financeiras</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF19</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar o patrimônio na rico</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US19">US19</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US19#imagem-representativa">T19</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF20</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os valores da tela inicial</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US20">US20</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US20#imagem-representativa">T20</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF21</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar a distribuição de investimentos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US21">US21</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US21#imagem-representativa">T21</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF22</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar as ultimas ordens realizadas no tesouro direto</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US22">US22</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US22#imagem-representativa">T22</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF23</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar informações da ordem realizada no tesouro direto</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US23">US23</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US23#imagem-representativa">T23</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF24</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário do deve visualizar as ultimas ordens realizadas em renda fixa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US24">US24</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US24#imagem-representativa">T24</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF25</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar as informações de ordem realizada no tesouro direto</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US25">US25</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US25#imagem-representativa">T25</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF26</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar as ultimas ordens realizadas para fundo de investimento</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US26">US26</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US26#imagem-representativa">T26</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF27</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar informações da ordem realizada para fundo de investimentos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US27">US27</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US27#imagem-representativa">T27</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF28</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US28">US28</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US28#imagem-representativa">T28</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF29</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os titulos de renda variavel </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US29">US29</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US29#imagem-representativa">T29</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF30</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar o extrato de movimentação</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US30">US30</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US30#imagem-representativa">T30</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="5">Visualização de investimentos em grupos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF31</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar as modalidades de investimentos disponíveis</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US31">US31</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US31#imagem-representativa">T31</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF32</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os investimentos para Tesouro Direto</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US32">US32</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US32#imagem-representativa">T32</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF33</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os títulos de Renda Fixa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US33">US33</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US33#imagem-representativa">T33</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF34</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os fundos de investimento disponíveis</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US34">US34</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US34#imagem-representativa">T34</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF35</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US35">US35</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US35#imagem-representativa">T35</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="4">Visualização de detalhes de títulos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF36</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar os detalhes de um Tesouro Direto</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US36">US36</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US36#imagem-representativa">T36</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF37</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar detalhes de um título de Renda Fixa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US37">US37</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US37#imagem-representativa">T37</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF38</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar detalhes de um fundo de investimento</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US38">US38</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US38#imagem-representativa">T38</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF39</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve visualizar detalhes de ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US39">US39</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US39#imagem-representativa">T39</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="4">Filtrar investimentos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF40</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve procurar um título de Renda Fixa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US40">US40</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US40#imagem-representativa">T40</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF41</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve filtrar títulos de Renda Fixa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US41">US41</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US41#imagem-representativa">T41</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF42</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve procurar fundos de investimentos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US42">US42</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US42#imagem-representativa">T42</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF43</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve filtrar fundo de investimentos disponiveis</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US43">US43</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US43#imagem-representativa">T43</td>
        </tr> 
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="4">Personalização para investimento</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF44</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve gerenciar ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US44">US44</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US44#imagem-representativa">T44</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF45</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de adicionar ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US45">US45</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US45#imagem-representativa">T45</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF46</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de remover os ativos de lista de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US46">US46</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US46#imagem-representativa">T46</td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF47</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de ativar/desativar operação de alavancada</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US47">US47</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US47#imagem-representativa">T47</td>
        </tr>  
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="5">Compra / venda de ativos</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF48</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de realizar aplicação em um título do Tesouro Dieto</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US48">US48</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US48#imagem-representativa">T48</td>
        </tr>  
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF49</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de realizar aplicação em um título de Renda Fixa</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US49">US49</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US49#imagem-representativa">T49</td>
        </tr> 
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF50</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de  realizar aplicação em um fundo de investimentos </td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US50">US50</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US50#imagem-representativa">T50</td>
        </tr>  
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF51</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de comprar ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US51">US51</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US51#imagem-representativa">T51</td>
        </tr>          
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF52</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">O usuário deve ser capaz de vender seus ativos de renda variável</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US52">US52</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US52#imagem-representativa">T52</td>
        </tr> 
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);" rowspan="3">Sistema</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Suportabilidade</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF57</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">As funcionalidades devem operar igualmente em todas as plataformas suportadas pela Rico</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US57">US57</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US57#imagem-representativa"><p align="center">-</p></td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">UX</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF58</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Proporcionar uma boa experiência de usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US58">US58</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US58#imagem-representativa"><p align="center">-</p></td>
        </tr>
        <tr>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Segurança</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">RF59</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);">Segurança ao guardar os dados do usuário</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US59">US59</td>
            <td style="vertical-align: middle;text-align:center;border: 0.5px solid rgbargba(0,0,0,0.2);"><a href="https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/Ágil/Histórias de Usuário/US59#imagem-representativa"><p align="center">-</p></td>
        </tr>
    </tbody>
</table>

## **Histórico de Revisões**

| Data       | Responsável                                                                                   | Versão | Alteração                                         |
| ---------- | --------------------------------------------------------------------------------------------- | ------ | ------------------------------------------------- |
| 19/11/2019 | [@pedroMiranda7410](https://github.com/pedroMiranda7410)| 1      | Adicionando Itens de 0 a 55 de requisitos elicitados e colocados no excel|
|23/11/2019 | [@dansousamelo](https://github.com/dansousamelo)| 1.1      | Ajustando formatação|

