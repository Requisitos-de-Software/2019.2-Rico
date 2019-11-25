## Diagramas de caso de uso

### Login

![Diagram de login](../img/login.png)

### Login - V2

![Diagram de login V2](../img/Acesso-aplicacao-v2.jpeg)

### Área do usuário

![Área do usuário](../img/area_do_usuario.png)

### Área do usuário - V2

![Área do usuário V2](../img/Area-usuario-v2.jpeg)

### Área de investimento

![Área de investimento](../img/area_investimento.png)

### Área de investimento - V2

![Área de investimento V2](../img/Area-investimento-v2.jpeg)

## UC01 - Realizar o cadastro de uma nova conta

#### Descrição:
<p align="justify">&emsp;
Este caso deve ser realizado por pessoas que desejam utilizar o aplicativo da Rico e ainda não possuem conta.
</p>

#### Ator principal:
<p align="justify">&emsp;
Não usuário e sistema
</p>

#### Pré-requisito:
1. O usuário deve estar deslogado de alguma conta no aplicativo da Rico.

#### Fluxo principal:
1.  O usuário não cadastrado acessa a Rico;
2.  No canto inferior da tela aparece a opção “Ainda não tem conta? Abra a sua gratuitamente”;
3.  O novo usuário é redirecionado para o site onde é solicitado todas as informações necessárias para o cadastro.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
Após avaliação da equipe da Rico, o cadastro do usuário é criado.
</p>


## UC02 - Realizar Login

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário da aplicação a entrar na sua conta Rico. 
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário
</p>

#### Pré-requisito:
1.  O usuário deve estar deslogado de alguma conta no aplicativo da Rico.

#### Fluxo principal:
1.  O usuário acessa o aplicativo da Rico;
2.  Seleciona a opção “Acessar minha conta”;
3.  Insere o nome do usuário;
4.  Pressiona o botão “Avançar”;
5.  Digita a senha em um teclado numérico com agrupamento de 2 dígitos em cada opção;
6.  Selecionando a opção “Entrar”.

#### Fluxo alternativo 1:
<p align="justify">&emsp;
O usuário já fez Login uma vez neste dispositivo e autorizou o login por digital.
</p>

1.  O usuário acessa o aplicativo da Rico;
2.  Seleciona a opção “Acessar minha conta”;
3.  Insere o nome do usuário;
4.  Pressiona o botão “Avançar”;
5.  Seleciona a opção “Entrar com impressão digital”;
6.  Pressiona o sensor de digital do aplicativo com o dedo cadastrado.

#### Fluxo de exceção 1:
<p align="justify">&emsp;
Nome de usuário inválido.
</p>

1.  O usuário acessa o aplicativo da Rico;
2.  Seleciona a opção “Acessar minha conta”;
3.  Insere um nome de usuário inválido;
4.  Pressiona o botão “Avançar”;
5.  Recebe a mensagem de erro “Oops, usuário incorreto”.

#### Fluxo de exceção 2:
<p align="justify">&emsp;
Senha incorreta.
</p>

1.  O usuário acessa o aplicativo da Rico;
2.  Seleciona a opção “Acessar minha conta”;
3.  Insere o nome do usuário;
4.  Pressiona o botão “Avançar”;
5.  Digita a senha em um teclado numérico com agrupamento de 2 dígitos em cada opção;
6.  Selecionando a opção “Entrar”;
7.  Recebe a mensagem de erro “Senha incorreta”.


#### Pós-condição:
<p align="justify">&emsp;
O usuário será redirecionado para a página principal para visualizar seu dashboard.
</p>


## UC03 - Esqueci meu usuário

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário obter o seu nome de usuário na utilizando as suas informações pessoais.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar deslogado de alguma conta no aplicativo da Rico.

#### Fluxo principal:
1.  O usuário acessa o aplicativo da Rico;
2.  O usuário seleciona a opção “Acessar minha conta”;
3.  O usuário seleciona a opção “Esqueci meu usuário”;
4.  O usuário digita o seu CPF;
5.  O usuário pressiona o botão avançar;
6.  O usuário seleciona a maneira que deseja recuperar o seu usuário, selecionando uma opção entre e-mail e telefone;
7.  O usuário pressiona o botão “Concluir”;
8.  O sistema realiza o envio de um e-mail informando o usuário do sistema.

#### Regras de negócio 1:
Campo | Formato | Obrigatoriedade | Valor
----- | ------- | --------------- | -----
CPF | 999.999.999-99 | Sim | CPF Válido

#### Fluxo alternativo:
--

#### Fluxo de exceção:
<p align="justify">&emsp;
O usuário não possui conta na Rico.
</p>

1.  O usuário acessa o aplicativo da Rico;
2.  O usuário seleciona a opção “Acessar minha conta”;
3.  O usuário seleciona a opção “Esqueci meu usuário”;
4.  O usuário digita o seu CPF;
5.  O usuário pressiona o botão avançar;
6.  O sistema mostra a mensagem de erro “Desculpe, não foi possível realizar a ação devido a uma instabilidade”;
<p align="justify">&emsp;
**Sugestão:** Seria correto que o sistema informasse que não possui nenhum usuário no sistema vinculado a tal CPF.
</p>

#### Pós-condição:
<p align="justify">&emsp;
O usuário recupera o seu nome de usuário para poder fazer login na Rico.
</p>


## UC04 - Esqueci minha senha

#### Descrição:
<p align="justify">&emsp;
Caso o usuário queira acessar a conta mas se esqueceu da senha de acesso.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e sistema
</p>

#### Pré-requisito:
1. O usuário deve estar deslogado de alguma conta no aplicativo da Rico.O usuário deve estar deslogado de alguma conta no aplicativo da Rico.

#### Fluxo principal:
1. O usuário acessa o aplicativo da Rico;
2. O usuário seleciona a opção “Acessar minha conta”;
3. O usuário digita o seu Usuário;
4. O usuário pressiona o botão avançar;
5. O usuário seleciona a opção “Esqueci”;
6. O usuário digita e seu CPF;
7. O usuário pressiona o botão avançar;
8. O usuário seleciona a maneira que gostaria de receber o código de recuperação da senha;
9. O usuário pressiona avançar;

#### Regra de negócio 1:
Campo | Formato | Obrigatoriedade | Valor
----- | ------- | --------------- | -----
CPF | 999.999.999-99 | Sim | CPF Válido

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O usuário receberá um email para redefinir a senha
</p>


## UC05 - Visualizar patrimônio na Rico

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário que ele visualize a quantidade de dinheiro que ele possui na Rico.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter saldo na conta da Rico ou realizado aplicação em algum investimento.


#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar o valor total (investimentos + saldo em conta), total investido e saldo disponível.
</p>


## UC06 - Visualizar / ocultar valores da tela inicial

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize ou oculte os valores da tela inicial. 
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter saldo na conta da Rico ou realizado aplicação em algum investimento.


#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. Pressiona um ícone de olho presente na tela.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar ou ocultar o valores da tela.
</p>


## UC07 - Visualizar distribuição dos investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize a distribuição dos seus investimentos por etapa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter aplicação em algum investimento da Rico.


#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar um gráfico de pilha ocupando toda a tela, mostrando o valor investido em cada etapa e seu % em relação ao investimento total.
</p>


## UC08 - Visualizar últimas ordens realizadas no Tesouro Direto

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize as últimas ordens realizadas para o Tesouro direto
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Tesouro Direto utilizando a Rico.

#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Tesouro Direto” no gráfico de pilha.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar o valor investido, rendimento, valor acomulado e uma relação das últimas ordens realizadas para investimento em Tesouro Direto.
</p>


## UC09 - Visualizar informações da ordem realizada no Tesouro Direto

#### Descrição:
<p align="justify">&emsp;
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Tesouro Direto utilizando a Rico.

#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Tesouro Direto” no gráfico de pilha;
4. O usuário seleciona alguma ordem realizada no Tesouro Direto.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar o nome do título, tipo da ordem, valor da compra, status e data de emissão.
</p>


## UC10 - Visualizar últimas ordens realizadas para títulos de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize as últimas ordens realizadas para a Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
O usuário deve ter realizado algum investimento em Renda Fixa utilizando a Rico.


#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Renda Fixa” no gráfico de pilha.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar uma relação das últimas ordens realizadas para investimento em Renda Fixa.
</p>


## UC11 - Visualizar informações da ordem realizada no título de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize informações da ordem realizada na Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Renda Fixa utilizando a Rico.


#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Renda Fixa” no gráfico de pilha;
4. O usuário seleciona alguma ordem realizada em Renda Fixa.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar o nome do título, tipo da ordem, valor da compra, status e data de emissão.
</p>


## UC12 - Visualizar últimas ordens realizadas para Fundos de Investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize as últimas ordens realizadas em Fundos de Investimentos.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Fundos de Investimento utilizando a Rico.

#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Fundo de Investimento” no gráfico de pilha.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar uma relação das últimas ordens realizadas para investimento em Fundos de Investimentos.
</p>

## UC13 - Visualizar informações da ordem realizada no Fundo de Investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize informações da ordem realizada no Fundo de Investimentos.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Fundo de Investimento utilizando a Rico.


#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Fundo de Investimentos” no gráfico de pilha;
4. O usuário seleciona alguma ordem realizada em Fundo de Investimentos.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
 O sistema irá mostrar o nome do título, tipo da ordem, valor da compra, status e data de emissão.
</p>

## UC14 - Visualizar ativos de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize as últimas ordens realizadas em Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Renda Fixa utilizando a Rico.

#### Fluxo principal:
1. O usuário acessa o menu “consultar” no aplicativo da Rico;
2. O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3. O usuário seleciona a opção “Renda Fixa” no gráfico de pilha.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar uma relação das últimas ordens realizadas para investimento em Renda Fixa.
</p>


## UC14 - Visualizar ativos de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize as últimas ordens realizadas em Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Renda Fixa utilizando a Rico.

#### Fluxo principal:
1.  O usuário acessa o menu “consultar” no aplicativo da Rico;
2.  O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3.  O usuário seleciona a opção “Renda Fixa” no gráfico de pilha.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar uma relação das últimas ordens realizadas para investimento em Renda Fixa.
</p>


## UC15 - Visualizar informações do título de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize informações da ordem realizada em Renda Variável
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado algum investimento em Renda Variável utilizando a Rico.

#### Fluxo principal:
1.  O usuário acessa o menu “consultar” no aplicativo da Rico;
2.  O usuário desliza o dedo da borda direita da tela em direção ao centro da tela;
3.  O usuário seleciona a opção “Renda Variável” no gráfico de pilha;
4.  O usuário seleciona alguma ordem realizada em Renda Variável.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar o nome do título, tipo da ordem, valor da compra, valor por ação, quantidade, status e validade.
</p>


## UC16 - Visualizar informações da conta

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário visualizar aspectos gerais relacionados a conta na Rico.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1.  O usuário acessa o menu “Perfil” no aplicativo Rico;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Minha conta”.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar as principais informações do usuário, como saldo disponível, agencia e conta bancária fornecida e extrato.
</p>


## UC17 - Visulizar extrato de movimentação

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize o extrato das transações realizadas em um certo período.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve ter realizado alguma movimentação bancária usado o aplicativo Rico

#### Fluxo principal:
1.  O usuário acessa o menu “Perfil” no aplicativo;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Extrato”;
4.  O usuário seleciona o intervalo de tempo desejado;

#### Fluxo alternativo:
1.  O usuário acessa o menu “Perfil” no aplicativo Rico;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Minha conta”;
4.  O usuário seleciona a opção “Meu extrato”;
5.  O usuário seleciona o intervalo de tempo desejado.

#### Fluxo de exceção:
<p align="justify">&emsp;
O usuário não realizou nenhuma transação utilizando o aplicativo Rico.
</p>

1.  O usuário acessa o menu “Perfil” no aplicativo Rico;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Minha conta”;
4.  O usuário seleciona a opção “Meu extrato”;
5.  O usuário seleciona o intervalo de tempo desejado;
6.  O aplicativo apresenta a mensagem “Você não realizou movimentações no período selecionado”.

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar uma relação das últimas transaçõese realizadas pelo usuário
</p>


## UC18 - Definir/alterar perfil do investidor

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário definir seu perfil de investidor.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1.  O usuário entra no menu “Perfil”;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Perfil do investidor”;
4.  O usuário pressiona “Refazer perfil de investidor”;
5.  O usuário responde o questionário.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá reavaliar o perfil do usuário e apresentar o resultado que melhor descreve o usuário.
</p>


## UC19 - Retirar dinheiro da conta Rico

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário transferir dinheiro da conta Rico para a conta pessoal.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo Rico;
2. O usuário deve ter dinheiro em conta para realizar a transferência.

#### Fluxo principal:
1.  O usuário entra no menu “Consultar”;
2.  O usuário pressiona o botão “Retirar”;
3.  O usuário informa o valor a ser retirado;
4.  O usuário pressiona o botão avançar;
5.  O usuário seleciona a conta para qual deseja realizar a transferência;
6.  O usuário pressiona o botão “Retirar”.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
<p align="justify">&emsp;
O usuário tenta retirar mais dinheiro do que está disponível na conta.
</p>

1.  O usuário entra no menu “Consultar”;
2.  O usuário pressiona o botão “Retirar”;
3.  O usuário informa o valor a ser retirado;
4.  O usuário pressiona o botão avançar;
5.  O sistema apresenta a mensagem “Valor indisponível”;

#### Pós-condição:
<p align="justify">&emsp;
O usuário recebe o valor definido na conta selecionada
</p>


## UC20 - Informações para declarar imposto de renda

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário coletar informações para declarar imposto de renda
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo

#### Fluxo principal:
1.  O usuário entra no menu “Perfil”;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Imposto de renda”.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá apresentar as principais opções relevantes relacionadas a declarar imposto de renda.
</p>


## UC21 - Informe de rendimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário obter informações do seu rendimento anual.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1.  O usuário entra no menu “Perfil”;
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Imposto de renda”;
4.  O usuário seleciona a opção “Informe de rendimentos”;

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá gerar um relatório de rendimentos para a Declaração de Imposto Sobre a Renda da Pessoa Física (IRPF) relativo ao ano anterior.
</p>


## UC22 - Relatórios extras

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário obter relatórios complementares para declarar imposto sobre renda de pessoa física.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo Rico.

#### Fluxo principal:
1.  O usuário entra no menu “Perfil”;
2.  
2.  
2.  O usuário seleciona a opção “Conta Rico”;
3.  O usuário seleciona a opção “Imposto de Renda”;
4.  O usuário seleciona a opção “Relatórios extras”.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O usuário poderá fazer o download de documentos que auxiliam no preenchimento de sua declaração de Imposto de Renda, tais como, Extrato completo, Operações normais, Day Trade, entre outros.
</p>


## UC23 - Notas de corretagem

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário obter informações sobre suas operações em Renda Variável
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo Rico

#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Conta Rico”
3. O usuário seleciona a opção “Imposto de Renda”
4. O usuário seleciona a opção “Notas de corretagem”

#### Fluxo alternativo:
--

#### Fluxo de exceção:
<p align="justify">&emsp;
Caso o usuário não tenha realizado nenhum investimento em algum mês o valor da informação será inexistente.
</p>

#### Pós-condição:
<p align="justify">&emsp;
O usuário poderá acessar as notas de corretagem vinculadas a sua conta ordenadas por mês que foram geradas.
</p>


## UC24 - Visualizar histórico de termos da conta

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário visualizar todos os contratos já assinados dentro do aplicativo Rico.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo Rico

#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Histórico de termos”


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O usuário pode visualizar os contratos e termos assinado ao utilizar o aplicativo Rico.
</p>


## UC25 - Alterar senha de acesso

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário alterar a senha de acesso no aplicativo
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo Rico.

#### Fluxo principal:
1.  O usuário entra no menu “Perfil”;
2.  O usuário seleciona a opção “Configurações”;
3.  O usuário seleciona a opção “Senha de acesso”;
4.  O usuário digita a senha atual;
5.  O usuário digita a nova senha;
6.  O usuário repete a nova senha;
7.  O usuário pressiona “Concluir”.

#### Regra de negócio 1:
Campo | Formato | Obrigatoriedade | Valor
----- | ------- | --------------- | -----
Senha atual | 6 a 8 números | Sim | Senha correta
Nova senha | 6 a 8 números | Sim | Senha correta
Confirmar senha | 6 a 8 números | Sim | Senha compatível com a novanovanova

#### Fluxo alternativo:
--

#### Fluxo de exceção 1:
<p align="justify">&emsp;
O usuário informou uma senha inválida.
</p>

1.  O usuário entra no menu “Perfil”;
2.  O usuário seleciona a opção “Configurações”;
3.  O usuário seleciona a opção “Senha de acesso”;
4.  O usuário digita a senha atual;
5.  O usuário digita a nova senha;
6.  O usuário repete a nova senha;
7.  O usuário pressiona “Concluir”;
8.  O sistema apresenta a mensagem “Senha inválida”.

#### Fluxo de exceção 2:
<p align="justify">&emsp;
O usuário informou uma senha inválida.
</p>

1.  O usuário entra no menu “Perfil”;
2.  O usuário seleciona a opção “Configurações”;
3.  O usuário seleciona a opção “Senha de acesso”;
4.  O usuário digita a senha atual;
5.  O usuário digita a nova senha;
6.  O usuário repete a nova senha;
7.  O usuário pressiona “Concluir”;
8.  O sistema apresenta um mensagem mostrando qual regra de negócio foi quebrada.

#### Pós-condição:
<p align="justify">&emsp;
O usuário vai ser capaz de acessar o aplicativo da Rico com a nova senha.
</p>


## UC26 - Alterar assinatura eletrônica

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário alterar a  sua assinatura eletrônica.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo Rico

#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Configurações”
3. O usuário seleciona a opção “Assinatura eletrônica”
4. O usuário digita a assinatura atual
5. O usuário digita a nova assinatura
6. O usuário repete a nova assinatura
7. O usuário pressiona “Concluir”


#### Fluxo alternativo:
--

#### Fluxo de exceção 1:
<p align="justify">&emsp;
O usuário informou uma assinatura inválida.
</p>

1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Configurações”
3. O usuário seleciona a opção “Assinatura eletrônica”
4. O usuário digita a assinatura atual
5. O usuário digita a nova assinatura
6. O usuário repete a nova assinatura
7. O usuário pressiona “Concluir”
8. O sistema apresenta a mensagem “Assinatura eletrônica inválida”

#### Fluxo de exceção 2:
<p align="justify">&emsp;
O usuário insere uma assinatura de confirmação que não é igual a nova assinatura.
</p>

1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Configurações”
3. O usuário seleciona a opção “Assinatura eletrônica”
4. O usuário digita a senha assinatura
5. O usuário digita a nova assinatura
6. O usuário repete a nova assinatura
7. O usuário pressiona “Concluir”
8. O sistema apresenta a mensagem “Confirmação de assinatura diferente”

#### Pós-condição:
<p align="justify">&emsp;
O usuário vai poder usar a nova assinatura eletrônica para realizar as operações.
</p>


## UC27 - Habilita login por digital

#### Descrição:
<p align="justify">&emsp;
Este caso de uso habilita a opção de acessar a conta do usuário utilizando o leitor de digital.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo Rico
2. O dispositivo do usuário deve ser compatível com esta função


#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Configurações”
3. O usuário seleciona a opção “Login por digital”
4. O usuário ativa a opção “Ativar login por digital”


#### Fluxo alternativo:
--

#### Fluxo de exceção:
<p align="justify">&emsp;
O dispositivo do usuário não é compatível.
</p>

1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Configurações”
3. A opção “Login por digital” não aparece para o usuário


#### Pós-condição:
<p align="justify">&emsp;
O usuário poderá acessar a conta no aplicativo sem digitar a senha.
</p>


## UC28 - Falar com o atendimento

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário obter assistência da equipe do aplicativo Rico.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo Rico

#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Atendimento”
3 .O usuário seleciona a opção “Fale conosco”


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O usuário vai ter acesso aos diferentes números que podem ser utilizados para entrar em contato com a equipe do aplicativo Rico
</p>


## UC29 - Tirar dúvidas

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário tirar dúvidas sobre o aplicativo.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo Rico

#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Atendimento”
3. O usuário seleciona a opção “Tire suas dúvidas”


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O usuário é redirecionado para uma página web onde pode enviar suas dúvidas à equipe da Rico
</p>


## UC30 - Sair da conta

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite ao usuário sair do aplicativo.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo Rico

#### Fluxo principal:
1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Sair”
3. O usuário deve confirmar a opção de sair
4. O usuário pressiona o botão “Sim”


#### Fluxo alternativo:
--

#### Fluxo de exceção:
<p align="justify">&emsp;
 usuário cancela o logout da conta.
</p>

1. O usuário entra no menu “Perfil”
2. O usuário seleciona a opção “Sair”
3. O usuário deve confirmar a opção de sair
4. O usuário pressiona o botão “Cancelar”


#### Pós-condição:
<p align="justify">&emsp;
</p>


## UC31 - Visualizar investimentos disponíveis por modalidade

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize as modalidades de investimentos disponíveis para investimento na Rico.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1.  O usuário acessa o menu “Investir” no aplicativo da Rico

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar 4 opções para acesso, sendo cada opção representada pelo nome e uma breve descrição.
</p>


## UC32 - Visualizar os investimentos do Tesouro Direto

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os investimentos disponíveis em tesouro direto.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.


#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Tesouro Direto.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar um resumo sobre Tesouro Direto e uma lista com os investimentos disponíveis contendo as seguintes informações de cada investimento: nome, características, valor mínimo, rentabilidade e data de vencimento.
</p>


## UC33 - Visualizar detalhes de um título do Tesouro Direto

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os detalhes para o investimento em um título do Tesouro Direto.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Tesouro Direto;
3. O usuário seleciona o título do Tesouro Direto que ele deseja obter mais informações.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar as seguintes informações deste título detalhes do Tesouro Direto:
</p>

* Nome;
* Características;
* Rentabilidade;
* Taxa BM&F Bovespa;
* Imposto de Renda;
* Taxa de IOF;
* Valor mínimo;
* Vencimento;
* Tempo para processar o investimento;
* Horário limite para realizar solicitações;
* Liquidez;
* Emissor do produto.

## UC34 - Realizar aplicação em um título do Tesouro Direto

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize aplicação de valores em um título do Tesouro Direto.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve possuir saldo em conta.


#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Tesouro Direto;3
3. O usuário seleciona o título do Tesouro Direto que ele deseja obter mais informações;
4. O usuário seleciona a opção “Investir”;
5. O usuário deve inserir o valor para investimento ou quantidade de cotas e data para realizar a operação;
6. O usuário seleciona a opção “Avançar”;
7. O usuário deve conferir as informações do investimento e selecionar a opção “Confirmar agendamento”;
8. O usuário deve inserir a sua assinatura eletrônica;
9. O usuário seleciona a opção “Confirmar”.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar mandar a solicitação de investimento para a BM&F Bovespa e informar na tela de resumo de investimentos que a operação está sendo processada.
</p>


## UC35 - Visualizar os título de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os investimentos disponíveis para Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Fixa.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar um resumo sobre investimento em Renda Fixa e uma lista com os investimentos disponíveis contendo as seguintes informações de cada investimento:
</p>

* Categoria do investimento (LC, LCI e CDB)
* Nome;
* Características;
* Valor mínimo;
* Rentabilidade;
* Data de vencimento.


## UC36 - Procurar título de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário busque por nome investimentos disponíveis para Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Fixa;
3. O usuário seleciona a lupa;
4. O usuário realiza a pesquisa através do nome do título de Renda Fixa.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar retornar os títulos com o nome correspondente ao texto digitado, mostrando as seguintes informações do título de Renda Fixa:
</p>

* Categoria do investimento (LC, LCI e CDB)
* Nome;
* Características;
* Valor mínimo;
* Rentabilidade;
* Data de vencimento.


## UC37 - Filtrar título de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize filtros nos investimentos disponíveis para Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1.  O usuário acessa o menu “Investir” no aplicativo da Rico;
2.  O usuário seleciona a opção Renda Fixa;
3.  O usuário seleciona a opção filtro;
4.  O usuário seleciona os itens que ele deseja incluir no filtro.

#### Regras de negócio 1:
Campo | Formato | Obrigatoriedade | Valor
----- | ------- | --------------- | -----
Ordenação | Radio Bottom | Não | Maior rentabilidade por indexador / Data de vencimento (crescente) / Tipo de indexador (alfabética) / Por emissor (alfabética) / Por categoria (alfabética)
Categoria | Checkbox | Não | CDB / LC / LCI
Indexador | Checkbox | Não | Pós-Fixado
Risco | Checkbox | Não | Conservador
Vencimento | Slider | Não | 0 a 1827 dias
Liquidez diária | Booleano  | Não | Sim / Não
Garantido pelo FGC | Booleano  | Não | Sim / Não
Investidor qualificado | Booleano  | Não | Sim / Não

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar retornar os títulos de Renda Fixa com características correspondentes as opções selecionadas no filtro, mostrando as seguintes informações do título de Renda Fixa:
</p>

*  Categoria do investimento (LC, LCI e CDB)
*  Nome;
*  Características;
*  Valor mínimo;
*  Rentabilidade;
*  Data de vencimento.


## UC38 - Visualizar detalhes de um título de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os detalhes para o investimento em um título de Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Fixa;
3. O usuário seleciona o título de Renda Fixa que ele deseja obter mais informações.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar as seguintes informações deste título detalhes do Tesouro Direto:
</p>

*******Categoria;
*******Nome;
*******Características;
*******Rentabilidade;
*******Imposto de Renda;
*******Taxa de IOF;
*******Valor mínimo;
*******Valor unitário;
*******Vencimento;
*******Tempo para processar o investimento;
*******Horário limite para realizar solicitações do investimento;
*******Liquidez;
*******Horário limite para realizar solicitações para resgate;
*******Órgão de garantia;
*******Emissor do produto;
*******Nota de crédito do emissor (rating).

## UC39 - Realizar aplicação em um título de Renda Fixa

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize aplicação de valores em um título de Renda Fixa.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve possuir saldo em conta.


#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Fixa;
3. O usuário seleciona o título de Renda Fixa;
4. O usuário seleciona a opção “Investir”;
5. O usuário deve inserir o valor para investimento ou quantidade de cotas e data para realizar a operação;
6. O usuário seleciona a opção “Avançar”;
7. O usuário deve inserir a sua assinatura eletrônica;
8. O usuário seleciona a opção “Confirmar”.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mandar a solicitação de investimento para a instituição bancária emissora do produto e informar na tela de resumo de investimentos o valor aplicado na Renda Fixa.
</p>

## UC40 - Visualizar os Fundos Investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os Fundos de Investimentos disponíveis.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Fundos de Investimentos.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar um resumo sobre Fundos de Investimentos disponíveis contendo as seguintes informações de cada investimento:
</p>

* Categoria do investimento;
* Nome;
* Características;
* Aplicação inicial;
* Rentabilidade nos últimos 12 meses.


## UC41 - Procurar Fundos de Investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário busque por nome os Fundos de Investimentos disponíveis.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Fundos de Investimentos;
3. O usuário seleciona a lupa;
4. O usuário realiza a pesquisa através do nome do Fundo de Investimento.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar retornar os títulos com o nome correspondente ao texto digitado, mostrando as seguintes informações do Fundo de Investimentos:
</p>

* Categoria do investimento;
* Nome;
* Características;
* Aplicação inicial;
* Rentabilidade nos últimos 12 meses.


## UC42 - Filtrar Fundos de Investimentos disponíveis 

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize filtros nos Fundos de Investimentos.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1.  O usuário acessa o menu “Investir” no aplicativo da Rico;
2.  O usuário seleciona a opção Fundos de Investimentos;
3.  O usuário seleciona a opção filtro;
4.  O usuário seleciona os itens que ele deseja incluir no filtro.

#### Regras de negócio 1:
Campo | Formato | Obrigatoriedade | Valor
----- | ------- | --------------- | -----
Ordenação | Radio Buttom | Não | Menor Risco / Valor mínimo para investir / Maior rentabilidade últimos 12 meses
Valor mínimo para investir | Slider | Não | 0 a 200.000
Risco | Checkbox | Não | Conservador / Moderado / Agressivo
Categoria | Checkbox | Não | Cambial / No exterior / Ações / Multimercado / Renda Fixa
Prazo de Resgate | Slider | Não | 0 a 361
Benchmark | Checkbox | Não | Opções de índeces
Tempo de abertura | Slider | Não | 1993 a 2019
Taxa de administração | Slider | Não | 0,10% até 4%
Sem taxa de performance | Booleano | Não | Sim / Não
Aberto para investimento | Booleano | Não | Sim / Não
Investidor qualificado | Booleano | Não | Sim / Não

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar retornar os Fundos de Investimentos com características correspondentes as opções selecionadas no filtro, mostrando as seguintes informações do Fundo de Investimentos:
</p>

*  Categoria do investimento (LC, LCI e CDB)
*  Nome;
*  Características;
*  Valor mínimo;
*  Rentabilidade;
*  Data de vencimento.



## UC43 - Visualizar detalhes de um Fundo de investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os detalhes de um Fundo de Investimento.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Fundos de Investimentos;
3. O usuário seleciona Fundo de Investimento que ele deseja obter mais informações.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar as seguintes informações deste título detalhes do Fundo de Investimentos:
</p>

* Nome;
* Características;
* Rentabilidade no mês;
* Rentabilidade no ano;
* Rentabilidade últimos 12 meses;
* Taxa de administração;
* Taxa de performance;
* Aplicação inicial;
* Movimentação mínima;
* Prazo de aplicação;
* Horário limite para realizar investimento;
* Saldo mínimo de permanência;
* Movimentação mínima;
* Prazo de cotização;
* Prazo de liquidação após o resgate;
* Horário limite para solicitar resgate;
* Categoria;
* Risco;
* Indexador de referência (benchmark);
* Objetivo;
* Gestora;
* Administradora;
* Patrimônio líquido atual;
* Patrimônio líquido médio (últimos 12 meses);
* Público alvo;
* Classificação de risco (rating Morning Star);
* Característica;
* Regulamento;
* Prospecto;
* Lamina;
* Regulamento;
* Prospecto.

## UC44 - Realizar aplicação em um Fundo de Investimentos

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize aplicação de valores em um Fundo de Investimentos.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve possuir saldo em conta.


#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Fundos de Investimentos;
3. O usuário seleciona um Fundo de Investimento disponível;
4. O usuário seleciona a opção “Investir”;
5. O usuário deve inserir o valor para investimento;;
6. O usuário seleciona a opção “Avançar”;
7. O usuário deve inserir a sua assinatura eletrônica;
8. O usuário seleciona a opção “Confirmar”.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mandar a solicitação de investimento para a instituição bancária emissora do produto e informar na tela de resumo de investimentos o valor aplicado no Fundo de Investimentos.
</p>


## UC45 - Visualizar os ativos de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário os ativos desejados.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar um resumo dos ativos selecionados pelo usuário, contendo as seguintes informações de cada ativo:
</p>

* Categoria do ativo;
* Código - Nome da empresa;
* Valor por ativo unitário;
* Variação do dia.

## UC46 - Ativar/Desativar Operação alavancada

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário ative/desative a operação alavancada para day-trade.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona a opção “Operação alavancada”;
4. O usuário confirma a opção selecionada.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;

</p>


## UC47 - Gerenciar ativos de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário gerencie os seus ativos selecionados para acompanhamento.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona a opção Gerenciar.


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá mostrar uma lista com todos os ativos selecionados pelo usuário.
</p>

## UC48 - Adicionar ativos de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário adicione seus ativos para o seu acompanhamento
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona a opção “Adicionar Ativos”;
4. O usuário realiza a busca do ativo por código ou nome da empresa;
5. O usuário seleciona o ativo desejado.


#### Fluxo alternativo 1:
<p align="justify">&emsp;
O usuário adiciona ativo pela tela de gerenciar ativos.
</p>

1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona a opção Gerenciar;
4. O usuário seleciona a opção “Adicionar”;
5. O usuário realiza a busca do ativo por código ou nome da empresa;
6. O usuário seleciona o ativo desejado.


#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá adicionar o ativo selecionado na lista de ativos do usuário.
</p>

## UC49 - Remover ativos da lista de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário remova um ativo da lista de acompanhamento.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona a opção Gerenciar;
4. O usuário pressiona a opção de remover no ativo listado


#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema irá remover este ativo da lista de ativos do usuário.
</p>

## UC50 - Visualizar detalhes de ativo de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário visualize os detalhes de um ativo da lista de acompanhamento.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema.
</p>

#### Pré-requisito:
1.  O usuário deve estar com um usuário no aplicativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona um ativo da lista.

#### Fluxo alternativo:
--

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
O sistema mostrar as seguintes informações do ativo selecionado:
</p>

* Categoria do ativo;
* Código - Empresa;
* Valor da ação
* Variação do dia;
* Fechamento dia anterior;
* Abertura do dia;
* Máxima do dia;
* Mínima do dia.
* Lote padrão;
* Tipo de ação;
* Perfil de risco;
* Emissor do produto

## UC51 - Comprar ativo de Renda Variável

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize operação de compra para ativos. 
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema. 
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve possuir limite para realizar a operação.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona um ativo da lista;
4. O usuário seleciona a opção Comprar;
5. O usuário seleciona a quantidade, preço por ação e validade da ordem de compra;
6. O usuário seleciona a opção Avançar;
7. O usuário seleciona a opção “Gerar ordem de compra”;
8. O usuário digita sua Assinatura Eletrônica;
9. O usuário seleciona a opção Confirmar.


#### Fluxo alternativo 1:
<p align="justify">&emsp;
O usuário deseja realizar uma “Ordem start”.
</p>

1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona um ativo da lista;
4. O usuário seleciona a opção Comprar;
5. O usuário seleciona a quantidade e validade da ordem;
6. O usuário seleciona a opção Avançar;
7. O usuário seleciona a opção “Gerar ordem de compra”;
8. O usuário digita sua Assinatura Eletrônica;
9. O usuário seleciona a opção Confirmar.


#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
A ordem de compra será enviada para a B3 e a informação referente a ordem ficará listada nas ordens de Renda Variável.
</p>

## UC52 - Vender ativo de Renda Variável 

#### Descrição:
<p align="justify">&emsp;
Este caso de uso permite que o usuário realize operação de venda para ativos.
</p>

#### Ator principal:
<p align="justify">&emsp;
Usuário e Sistema
</p>

#### Pré-requisito:
1. O usuário deve estar com um usuário no aplicativo;
2. O usuário deve possuir ações deste ativo.

#### Fluxo principal:
1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona um ativo da lista;
4. O usuário seleciona a opção Vender;
5. O usuário seleciona a quantidade, preço por ação e validade da ordem de compra;
6. O usuário seleciona a opção Avançar;
7. O usuário seleciona a opção “Gerar ordem de compra”;
8. O usuário digita sua Assinatura Eletrônica;
9. O usuário seleciona a opção Confirmar.


#### Fluxo alternativo 1:
<p align="justify">&emsp;
O usuário deseja realizar uma “Ordem start”.
</p>

1. O usuário acessa o menu “Investir” no aplicativo da Rico;
2. O usuário seleciona a opção Renda Variável;
3. O usuário seleciona um ativo da lista;
4. O usuário seleciona a opção Vender;
5. O usuário seleciona a quantidade e validade da ordem;
6. O usuário seleciona a opção Avançar;
7. O usuário seleciona a opção “Gerar ordem de compra”;
8. O usuário digita sua Assinatura Eletrônica;
9. O usuário seleciona a opção Confirmar.

#### Fluxo de exceção:
--

#### Pós-condição:
<p align="justify">&emsp;
A ordem de venda será enviada para a B3 e a informação referente a ordem ficará listada nas ordens de Renda Variável.
</p>


## **Histórico de Revisões**

Data | Responsável | Versão | Alteração 
---- | ----------- | ------ | ---------
29/09/2019 | [@tmcstiago](https://github.com/tmcstiago) e [@medeiroslucas](https://github.com/medeiroslucas) | 1 | Adiciona os Casos de Uso
21/10/2019 | [@tmcstiago](https://github.com/tmcstiago) e [@medeiroslucas](https://github.com/medeiroslucas) | 2 | Adicionar diagramas de caso de uso
25/11/2019 | [@tmcstiago](https://github.com/tmcstiago) e [@medeiroslucas](https://github.com/medeiroslucas) | 3 | Atualizar diagramas de caso de uso

## **Referências**
 * <p align="justify">SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 11; Disponível em https://aprender.ead.unb.br/pluginfile.php/727236/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf.</p>
