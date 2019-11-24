## **MOSCOW**
<p align="justify">&emsp;
O MoSCoW é uma técnica de priorização de requisitos, onde todos os requisitos são analisados e, a cada um é mensurado um grau de importância, dado por uma letra das 4 palavras que compõem o MoSCoW:</p>  

* <p align="justify">Must: são as funcionalidades mais importantes do projeto, aquelas que mais agregam valor e que, sem elas, o projeto não pode ser entregue.</p>
* <p align="justify">Should: funcionalidades que também são importantes, mas não necessárias para entrega (pelo menos inicialmente).</p>
* <p align="justify">Could: funcionalidades desejáveis, que agregam valor ao produto e melhoram a experiência com o cliente.</p>
* <p align="justify">Would: todas as funcionalidades que não serão desenvolvidas no momento pois não agregam valor ao produto.</p>
  
<p align="justify">&emsp;
Essa técnica será utilizada para checar a importância de cada requisito levantado da aplicação Rico. A metodologia utilizada para o levantamento de priorização de requisitos é análoga à técnica de Planning poker onde cada integrante dá um valor à um requisito e então é comparado com o valor de prioridade dos outros membros da equipe. O valor do requisito é definido quando todos os integrantes da equipe entram em consenso.</p>

### **MoSCoW - Requisitos Funcionais**

| Identificador | Descrição                                                                                                                         | Valor  |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------ |
| RF01          | O usuário deve ser capaz de criar uma nova conta com os dados da sua conta bancária, CPF e comprovante de residência              | Must   |
| RF02          | O usuário deve ser capaz de logar utilizando o seu nome de usuário e uma senha definida por ele no momento do cadastro            | Must   |
| RF03          | O Rico deve apresentar para o usuário os dados dos investimentos já realizados                                                    | Should |
| RF04          | O usuário deve ser capaz de escolher dentre várias opções e tipos de investimento                                                 | Must   |
| RF05          | O usuário deve poder agendar a data que deseja para comprar os investimentos/ações                                                | Could  |
| RF06          | O usuário deve ser capaz de visualizar o retorno dos seus investimentos                                                           | Must   |
| RF07          | O usuário deve ser capaz de visualizar o saldo                                                                                    | Must   |
| RF08          | O usuário deve ser capaz de receber e realizar transferências                                                                     | Must   |
| RF09          | O usuário deve ter acesso ao histórico de transações                                                                              | Should |
| RF10          | O usuário deve ter acesso ao histórico de rentabilidade em gráfico de linha                                                       | Should |
| RF11          | O usuário deve ter acesso ao próprio perfil                                                                                       | Must   |
| RF12          | O usuário deve ter acesso à funcionalidade de alterar senha                                                                       | Must   |
| RF13          | O usuário deve ter acesso à àrea de ajuda                                                                                         | Should |
| RF14          | O usuário deve ter acesso ao questionário que define seu perfil de investidor                                                     | Could  |
| RF15          | Proporcionar um simulador de investimentos                                                                                        | Could  |
| RF16          | Proporcionar que o usuário aprenda sobre investimento                                                                             | Could  |
| RF17          | Indicação de investimento realizado por analistas                                                                                 | Could  |
| RF18          | Informar o risco do investimento por meio de categorias                                                                           | Could  |
| RF19          | Filtrar uma lista de investimentos por categorias, risco, rentabilidade e valor                                                   | Should |
| RF20          | Indicar a porcentagem de variação do valor do investimento no dia                                                                 | Should |
| RF21          | Atualizar de forma constante o valor do investimento, de maneira que o usuário veja a variação em tempo real                      | Could  |
| RF22          | Prover informações para o usuário sobre como determinado investimento variou seu valor ao longo dos últimos dias                  | Should |
| RF23          | Dar a possibilidade pro usuário selecionar seus investimentos favoritos, os colocando em uma lista disponibilizada para o usuário | Could  |

### MoSCoW - Requisitos Não Funcionais

| Identificador | Descrição                                                                                                             | Valor  |
| ------------- | --------------------------------------------------------------------------------------------------------------------- | ------ |
| RNF01         | Proporcionar uma boa experiência de usuário                                                                           | Should |
| RNF02         | As funcionalidades devem operar igualmente em todas as plataformas suportadas pela Rico                               | Must   |
| RNF03         | Segurança ao guardar os dados do usuário                                                                              | Must   |
| RNF04         | Aplicação deve ser eficiente no que diz respeito ao seu desempenho e velocidade na hora de executar as funcionalidade | Must   |
| RNF05         | O sistema deve ficar sempre online para que transferências sejam feitas                                               | Must   |

## **First Things First**
<p align="justify">&emsp;
O First Things First é uma técnica de priorização de requisitos que visa definir as tarefas que devem ser feitas primeiro (mais importantes) e as que devem ser feitas posteriormente (menos importantes).</p>

**Metodologia:**     
**1 -** Uma lista com todos os requisitos é feita e os requisitos que estão logicamente ligados são retirados da lista.

**2 -** O benefício que cada recurso oferece ao cliente/negócio é estimado.

**3 -** A penalidade que o negócio sofreria caso o recurso não seja incluído é estimada.

**4 -** A coluna de valor total é preenchida, sendo a soma do benefício e da penalidade, junto aos pesos.

**5 -** O custo de implementação com base na complexidade de implementação é estimado.

**6 -** O grau de risco com base na viabilidade, conhecimento, uso de tecnologias desconhecidas é estimado.

**7 -** A prioridade (p) é calculada: p = valor% = (custo% * peso custo + risco% * peso risco).

**8 -** A lista é ordenada em ordem decrescente de prioridade.

**Observação:** Todos os valores estimados são entre 1 e 9.

**Conclusão:** As funcionalidades no topo da lista têm o melhor equilíbrio entre valor, custo e risco e devem ser priorizadas.

| Requisito | Benefício | Penalidade | Valor Total | Valor%  | Custo Relativo | Custo%  | Risco Relativo | Risco%  | Prioridade |
| --------- | --------- | ---------- | ----------- | ------- | -------------- | ------- | -------------- | ------- | ---------- |
| RF11      | 8         | 9          | 17          | 17,34   | 2              | 6,66    | 1              | 3,44    | 1,71       |
| RF01      | 9         | 9          | 18          | 18,36   | 5              | 16,66   | 3              | 10,34   | 0,68       |
| RF16      | 5         | 4          | 9           | 9,18    | 3              | 10      | 1              | 3,44    | 0,68       |
| RF04      | 8         | 9          | 17          | 17,34   | 3              | 10      | 7              | 24,13   | 0,50       |
| RF08      | 9         | 9          | 18          | 18,36   | 7              | 23,3    | 9              | 31,03   | 0,33       |
| RF14      | 6         | 4          | 10          | 10,20   | 5              | 16,66   | 4              | 13,79   | 0,33       |
| RF15      | 6         | 3          | 9           | 9,18    | 5              | 16,66   | 4              | 13,79   | 0,30       |
| **TOTAL** | **51**    | **47**     | **98**      | **100** | **30**         | **100** | **29**         | **100** | **-**      |

**RF01** - O usuário deve ser capaz de criar uma nova conta com os dados da sua conta bancária, CPF e comprovante de residência

**RF04** - O usuário deve ser capaz de escolher dentre várias opções e tipos de investimento

**RF08** - O usuário deve ser capaz de receber e realizar transferências

**RF11** - O usuário deve ter acesso ao próprio perfil

**RF14** - O usuário deve ter acesso ao questionário que define seu perfil de investidor

**RF15** - Proporcionar um simulador de investimentos

**RF16** - Proporcionar que o usuário aprenda sobre investimento


### **First Things First v2.0**

<p align="center">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTY8OVTEamJ7fkYhvMQuNsfhM1CPcORV5AyC_4-vYOtxNVDz68xkIrH1oPwB3DRYkLK-oxQyJxgdkEJ/pubhtml?widget=true&amp;headers=false" frameborder="0" width="3000" height="600" allowfullscreen="true"e mozallowfullscreen="tru" webkitallowfullscreen="true"></iframe>
</p>


### **Histórico de Revisões**
| Data       | Responsável                                        | Versão | Alteração                           |
| ---------- | -------------------------------------------------- | ------ | ----------------------------------- |
| 27/09/2019 | [@lbrunofidelis](https://github.com/lbrunofidelis) | 1      | Adicionando tabela do MoSCoW        |
| 27/09/2019 | [@lbrunofidelis](https://github.com/lbrunofidelis) | 1.1    | Adicionando First Things First      |
| 30/09/2019 | [@dansousamelo](https://github.com/dansousamelo)   | 1.2    | Adicionando Correções               |
| 23/11/2019 | [@lbrunofidelis](https://github.com/lbrunofidelis) | 1.3    | Adicionando First Things First v2.0 |

## **Referências**
* <p align="justify">SERRANO, Maurício; SERRANO, Milene. Aula de elicitação, modelagem e análise de requisitos. Requisitos de Software Aula 7, [S. l.], p. 31-40, 3 abr. 2018. E-book.</p>
