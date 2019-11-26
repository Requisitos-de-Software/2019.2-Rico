## Login Pela Digital
| **Título**  | **Login Pela Digital** |
| ------------- | ------------- |
| **Objetivo**  | Carregar e recuperar informações de uma [conta](../lexicos/#conta) da rico com base na digital do [usuário](../lexicos/#usuario)|
| **Contexto** |<p> **Pré-condição:** [usuário](../lexicos/#usuario) não logado no aplicativo </p><p>**Pós-condição:** [usuário](../lexicos/#usuario) logado no aplicativo</p>|
| **Atores** |<p>1. Não Usuário</p><p>2. [usuário](../lexicos/#usuario)</p><p>3. Sistema</p>|
| **Recursos** |<p>Acesso a internet</p><p> Smartphone com recurso de digital</p>|
| **Episódios** |<p>1. O [usuário](../lexicos/#usuario) não cadastrado acessa a Rico</p><p>2. O [usuário](../lexicos/#usuario) não cadastrado deve [criar uma conta](./#criar-conta)</p><p>3. O [usuário](../lexicos/#usuario) deve ter uma [conta](../lexicos/#conta)</p><p>4. O [usuário](../lexicos/#usuario) deve ter uma digital cadastrada</p><p>5. O sistema permite o [usuário](../lexicos/#usuario) acessar a sua [conta](../lexicos/#conta)</p>|
| **Restrições** |<p>Digital cadastrada</p>|
| **Exceção** |<p>1. Digital não funcionando</p><p>2. A internet para de funcionar no meio da ação</p><p>3. O [usuário](../lexicos/#usuario) fechar o aplicativo antes de terminar a ação</p><p>4. O [usuário](../lexicos/#usuario) não deve usar o celular de luvas</p>|
 
##  Criar Conta
| **Título**  | **Criar Conta** |
| ------------- | ------------- |
| **Objetivo**  | Criar uma [conta](../lexicos/#conta-corrente) bancária com [agência](../lexicos/#agencia) e número de [conta](../lexicos/#conta-corrente) para realização de [depósitos](../lexicos/#deposito) e transferências |
| **Contexto** | <p> **Pré-condição:** [usuário](../lexicos/#usuario) não possui [conta](../lexicos/#conta) </p><p>**Pós-condição:**É criado um perfil através do e-mail e da senha do usuário, podendo também conter um [login pela digital](#login-pela-digital)</p> |
| **Atores** |<p>1. Não Usuário</p><p>2. Usuário</p><p>3. Sistema</p>|
| **Recursos** |<p>Acesso a internet</p><p> Computador desktop ou smartphone</p>|
| **Episódios** |1. O usuário não cadastrado acessa a Rico</p><p>2. O usuário não cadastrado deve criar uma [conta](../lexicos/#conta)</p><p>3. O usuário que já tem uma [conta](../lexicos/#conta) deve logar no sistema</p><p>4. O sistema permite, o usuário que tem uma [conta](../lexicos/#conta), acessar a sua [conta](../lexicos/#conta)</p><p>5. O sistema deve criar uma [conta](../lexicos/#conta) ao usuário que a solicitou</p>|
| **Restrições** |<p>Interface agradável para o usuário</p>|
| **Exceção** |<p>O usuário deve ser maior de 18 anos</p>|
 
 
##  Acessar Configurações
| **Título**  | **Acessar Configurações** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode acessar as configurações |
| **Contexto** | <p> **Pré-condição:** Estar logado</p><p>**Pós-condição:** A tela de configurações será exibida</p>  |
| **Atores** | [usuário](../lexicos/#usuario) |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) abre o aplicativo</p><p>2. O [usuário](../lexicos/#usuario) vai para aba de perfil</p><p>3. O [usuário](../lexicos/#usuario) seleciona a opção de configurações</p> |
| **Restrições** | Fluxo interativo |
| **Exceção** | <p>1. A internet parar de funcionar no meio da ação</p><p>2. O [usuário](../lexicos/#usuario) fechar o aplicativo durante a ação</p> |
 
 
 
##  Investir por Categoria
| **Título**  | **Investir por Categoria** |
| ------------- | ------------- |
| **Objetivo**  | Possibilitar o [usuário](../lexicos/#usuario) de escolher por categoria o tipo de [investimento](../lexicos/#investimento) que quer realizar e, dentro da categoria selecionada, escolher o que [comprar](#comprar-acao) |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) tem uma quantidade de [dinheiro](../lexicos/#dinheiro) para [comprar uma ação](#comprar-acao)</p><p>**Pós-condição:**    O [usuário](../lexicos/#usuario) investe seu [dinheiro](../lexicos/#dinheiro) em alguma ação</p>  |
| **Atores** | <p>1. [usuário](../lexicos/#usuario)</p><p>2. Sistema</p> |
| **Recursos** | <p>1. Acesso a internet</p><p>2. [Dinheiro](../lexicos/#dinheiro) necessário depositado na conta</p> |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) acessa sua [conta](../lexicos/#conta)</p><p>2. O [usuário](../lexicos/#usuario) visualiza sua quantidade de [dinheiro](../lexicos/#dinheiro) X</p><p>3. O [usuário](../lexicos/#usuario) não quer deixar seu [dinheiro](../lexicos/#dinheiro) parado</p><p>4. O [usuário](../lexicos/#usuario), por ser [conservador](../lexicos/#conservador), quer procurar nas categorias os de renda fixa</p><p>5. o [usuário](../lexicos/#usuario) encontra o que quer [comprar](#comprar-acao) e investe seu [dinheiro](../lexicos/#dinheiro) </p> |
| **Restrições** | <p>[usuário](../lexicos/#usuario) que possui [dinheiro](../lexicos/#dinheiro) na carteira</p><p>[usuário](../lexicos/#usuario) que não quer deixar o [dinheiro](../lexicos/#dinheiro) parado</p> |
| **Exceção** | <p>1. A internet parar de funcionar no meio da ação</p><p>2. O [usuário](../lexicos/#usuario) não ter [dinheiro](../lexicos/#dinheiro) suficiente pra [comprar](#comprar-acao) determinada ação</p> |

##  Investir por Categoria - V2
| **Título**  | **Investir por Categoria - V2** |
| ------------- | ------------- |
| **Objetivo**  | Possibilitar o [usuário](../lexicos/#usuario) de escolher por categoria o tipo de [investimento](../lexicos/#investimento) que quer realizar e, dentro da categoria selecionada, escolher o que [comprar](#comprar-acao) |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) tem uma quantidade de [dinheiro](../lexicos/#dinheiro) para [comprar uma ação](#comprar-acao)</p><p>**Pós-condição:**    O [usuário](../lexicos/#usuario) investe seu [dinheiro](../lexicos/#dinheiro) em alguma ação</p>  |
| **Atores** | <p>1. [usuário](../lexicos/#usuario)</p><p>2. Sistema</p> |
| **Recursos** | <p>1. Acesso a internet</p><p>2. [Dinheiro](../lexicos/#dinheiro) necessário depositado na conta</p> |
| **Episódios** | <p>O [usuário](../lexicos/#usuario) acessa sua [conta](../lexicos/#conta)</p><p>O [usuário](../lexicos/#usuario) visualiza sua quantidade de [dinheiro](../lexicos/#dinheiro) X</p><p>O [usuário](../lexicos/#usuario) não quer deixar seu [dinheiro](../lexicos/#dinheiro) parado</p><p>O [usuário](../lexicos/#usuario), por ser [conservador](../lexicos/#conservador), quer procurar nas categorias os [investimentos](../lexicos/#investimento) de renda fixa</p><p>O [usuário](../lexicos/#usuario) encontra o que quer [comprar](#comprar-acao) e investe seu [dinheiro](../lexicos/#dinheiro) </p> |
| **Restrições** | <p>O [usuário](../lexicos/#usuario) que possui [dinheiro](../lexicos/#dinheiro) na carteira</p><p>[usuário](../lexicos/#usuario) que não quer deixar o [dinheiro](../lexicos/#dinheiro) parado</p> |
| **Exceção** | <p>A internet parar de funcionar no meio da ação</p><p>O [usuário](../lexicos/#usuario) não ter [dinheiro](../lexicos/#dinheiro) suficiente pra [comprar](#comprar-acao) determinada ação</p><p>O usuário ser menor de idade</p>|


##  Consultar patrimônio
| **Título**  | **Consultar patrimônio** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) poderá visualizar qual o tamanho do seu [patrimônio](#Patrimônio), ou quantidade de [dinheiro](../lexicos/#dinheiro) depositado + [lucro](#Lucro) de [investimentos](#Investimentos) |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) estar curioso quanto á seu saldo</p><p>**Pós-condição:** o [usuário](../lexicos/#usuario) estar com controle sobre seu [patrimônio](#Patrimônio)</p>  |
| **Atores** | [usuário](../lexicos/#usuario) |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) não lembra quanto de [dinheiro](../lexicos/#dinheiro) tem na sua [conta](../lexicos/#conta)</p><p>2. O [usuário](../lexicos/#usuario) quer saber quanto ele possui na [conta](../lexicos/#conta) rico</p><p>3. O [usuário](../lexicos/#usuario) abre o app e efetua seu login</p> <p>O [usuário](../lexicos/#usuario) visualiza seu saldo existente e fica com controle quanto a sua [conta](../lexicos/#conta)</p> |
| **Restrições** | [Usuários]() interessados |
| **Exceção** | <p>A internet parar de funcionar no meio da ação do login</p> |
 
##  Consultar investimentos realizados
| **Título**  | **Consultar investimentos realizados** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode consultar quais [investimento](../lexicos/#investimento) foi efetuado por ele e seus, respectivos, rendimentos alcançados |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) estar curioso quanto seu rendimento</p><p> quais foram todos os [investimentos](../lexicos/#investimento) efetuados</p><p>**Pós-condição:** o [usuário](../lexicos/#usuario) estar no controle sobre seus [investimentos](../lexicos/#investimento) e o que teve lucro ou prejuízos</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) está curioso sobre como anda os rendimentos deu seus [investimentos](../lexicos/#investimento)</p><p>2. O [usuário](../lexicos/#usuario) está curioso sobre quais foram todos [investimentos](../lexicos/#investimento) realizados pelo app</p><p>3. O [usuário](../lexicos/#usuario) abre o app e efetua seu login</p><p>4. O [usuário](../lexicos/#usuario) entra na aba de [investimentos](../lexicos/#investimento)</p><p>O [usuário](../lexicos/#usuario) visualiza [investimento](../lexicos/#investimento) por [investimento](../lexicos/#investimento) em uma única página</p><p>O [usuário](../lexicos/#usuario) fica informado quanto a seus [investimentos](../lexicos/#investimento) e se sente mais seguro </p> |
| **Restrições** | [Usuários]() interessados |
| **Exceção** | <p>A internet parar de funcionar no meio da ação</p> |

##  Refazer Perfil de investidor
| **Título**  | **Refazer Perfil de investidor** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode refazer uma avaliação para descobrir que perfil de investidor ele(a) é |
| **Contexto** | <p> **Pré-condição:**</p><p> O [usuário](../lexicos/#usuario) não sabe que tipo de [investidor](../lexicos/#investidor) ele é.</p><p> O [usuário](../lexicos/#usuario) não quer saber se seu estilo de [investidor](../lexicos/#investidor) se alterou</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) estar conformado sobre seu tipo de [investidor](../lexicos/#investidor)</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) está curioso para saber quanto á seu perfil de investidor</p><p>2. O [usuário](../lexicos/#usuario) entra no Sistema e inicia a avalição para saber seu perfil de investidor</p><p>3. O sistema abre um questionário com uma série de perguntas á serem respondidas</p><p>4. O [usuário](../lexicos/#usuario) responde o questionário para o perfil de investidor</p><p>5. O sistema processa as respostas e retorna com uma resposta dizendo qual o perfil de investidor do [usuário](../lexicos/#usuario)</p><p>6. O [usuário](../lexicos/#usuario) fica informado quanto a seu perfil de investidor </p> |
| **Restrições** | [Usuários]() interessados |
| **Exceção** | <p>A internet parar de funcionar no meio da ação</p> |

##  Retirar Ação
| **Título**  | **Retirar Ação** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode cancelar ação de efetuar compra de um [investimento](../lexicos/#investimento) |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) investe em uma [ação](../lexicos/#acao) e muda de ideia</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) se disfez da possível participação de [investimento](../lexicos/#investimento) em tal ação</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet, Ter [dinheiro](../lexicos/#dinheiro) suficiente para [comprar alguma ação](#comprar-acao) |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) tem [dinheiro](../lexicos/#dinheiro) para [comprar](#comprar-acao) algum [investimento](../lexicos/#investimento)</p><p>2. O [usuário](../lexicos/#usuario), meio indeciso, compra uma [ação](../lexicos/#acao) sem pensar direito</p><p>3. O sistema retorna ao usuário uma mensagem de que a operação de compra será processada</p><p>4. O [usuário](../lexicos/#usuario) vê que essa compra não irá retornar lucros e quer desfazer da operação</p><p>5. O [usuário](../lexicos/#usuario) cancela o processamento da operação</p><p>6. O sistema cancela sua operação e retorna uma mensagem de sucesso para o usuário </p> |
| **Restrições** | [Usuários]() desatentos |
| **Exceção** | <p>A internet parar de funcionar no meio da ação e não voltar até a operação de compra ser efetuada</p> |

##  Comprar ação
| **Título**  | **Comprar ação** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode comprar uma [ação](#Ações) para investir seu [dinheiro](../lexicos/#dinheiro) |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) tem [dinheiro](../lexicos/#dinheiro) sem estar sendo utilizado</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) deixou seu [dinheiro](../lexicos/#dinheiro) trabalhando pra ele</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet, Ter [dinheiro](../lexicos/#dinheiro) suficiente para comprar alguma [ação](../lexicos/#acao) |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) tem [dinheiro](../lexicos/#dinheiro) para comprar alguma [ação](#Ações)</p><p>2. O [usuário](../lexicos/#usuario) verifica qual é a [ação](#Ações) ideal para ele comprar e ter seu [dinheiro](../lexicos/#dinheiro) com um maior rendimento anual</p><p>3. O [usuário](../lexicos/#usuario) encontra a [ação](#Ações) e efetua a compra</p><p>4. O sistema realiza as operações para disponibilidade da compra se comunicando com a [instituição](../lexicos/#instituicao-financeira) e efetuando o pagamento</p><p>5. O [usuário](../lexicos/#usuario) tem seu [dinheiro](../lexicos/#dinheiro) rendendo, trabalhando sozinho para ele</p> |
| **Restrições** | [Usuários]() incomodados com o [dinheiro](../lexicos/#dinheiro) parado |
| **Exceção** | <p>A internet parar de funcionar no meio da ação</p> |

##  Ter a acesso notificação
| **Título**  | **Ter a acesso notificação** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) recebe notificações quanto as operações do sistema |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) não sabe o que acontece quanto investe</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) fica informado quanto ao processamento do [investimento](../lexicos/#investimento) comprado</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) efetua a compra de um [investimento](../lexicos/#investimento) </p><p>2. O sistema recebe a solicitação da compra </p><p>3. O sistema envia um e-mail ao [usuário](../lexicos/#usuario) de que a compra está sendo processada</p><p>4. O sistema retorna com mais e-mails notificando o [usuário](../lexicos/#usuario) sobre cada etapa processada</p><p>5.O [usuário](../lexicos/#usuario) fica informado do que está acontecendo com seu [dinheiro](../lexicos/#dinheiro)</p> |
| **Restrições** | [Usuários]() preocupados |
| **Exceção** | <p>A internet parar de funcionar até ter acontecido todas as operações pelo sistema</p> |

##  Consultar minha Conta
| **Título**  | **Consultar minha Conta** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode consultar os dado de sua [conta](../lexicos/#conta) |
| **Contexto** | <p> **Pré-condição:** O usuário não lembra sua [conta](../lexicos/#conta) </p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) sabe qual sua [conta](../lexicos/#conta) e pode realizar a ação que deseja informando sua [conta](../lexicos/#conta)</p> |
| **Atores** | [usuário](../lexicos/#usuario) |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) deseja [depositar](#depositar-na-conta-da-rico) um [dinheiro](../lexicos/#dinheiro) em sua [conta](../lexicos/#conta) da rico porém não lembra os dados de sua [conta](../lexicos/#conta) </p><p>2. O [usuário](../lexicos/#usuario) entra no sistema </p><p>3. O [usuário](../lexicos/#usuario) abre a aba sobre sua [conta](../lexicos/#conta) e fica informado </p><p>4. O [usuário](../lexicos/#usuario) volta ao seu outro [banco](../lexicos/#banco) e efetua a transferência </p> |
| **Restrições** | [Usuários]() que não realizam muitas transferências |
| **Exceção** | <p>A internet parar de funcionar durante ação de visualizar dados da [conta](../lexicos/#conta)</p> |

##  Consultar Histórico de termos
| **Título**  | **Consultar Histórico de termos** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode visualizar seu histórico de termos |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) está curioso quanto a suas compras a termos</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) está atualizado sobre suas compras efetuadas </p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) quer verificar que compras a termos foram efetuadas </p><p>2. O [usuário](../lexicos/#usuario) abre o sistema e efetua o login </p><p>3. O [usuário](../lexicos/#usuario) clica na aba "Ação/Termos" </p><p>4. O [usuário](../lexicos/#usuario) se informa sobre todas as ações compradas a termos organizadas por data </p> |
| **Restrições** | [Usuários]() organizados |
| **Exceção** | <p>A internet parar de funcionar durante ação</p> |

##  Solicitar Atendimento
| **Título**  | **Solicitar Atendimento** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode solicitar atendimentos |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) está curioso para saber o que está acontecendo</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) está saciado e se sentindo seguro com seu [dinheiro](../lexicos/#dinheiro)</p> |
| **Atores** | [usuário](../lexicos/#usuario), Equipe Rico |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) efetua uma compra de grande valor em uma [ação](../lexicos/#acao) </p><p>2. O [usuário](../lexicos/#usuario) fica 2 dias sem receber uma resposta </p><p>3. O [usuário](../lexicos/#usuario),preocupado, entra em contato com a Equipe Rico por meio de um e-mail ou ligação</p><p>4. A Equipe Rico escuta atentamente o que o [usuário](../lexicos/#usuario) tem a dizer </p><p>5. A Equipe Rico conforta o [usuário](../lexicos/#usuario) e diz o que está acontecendo</p><p>6. O [usuário](../lexicos/#usuario) se acalma</p> |
| **Restrições** | [Usuários]() iniciantes, [Usuários]() preocupados |
| **Exceção** | <p>A internet parar de funcionar durante ação</p><p> Não ter sinal para efetuar uma ligação</p> |

##  Avaliar o App
| **Título**  | **Avaliar o App** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) deseja avaliar o app |
| **Contexto** | <p> **Pré-condição:** </p><p>O [usuário](../lexicos/#usuario) gostou muito do sistema e deja avalia-lo</p><p>O [usuário](../lexicos/#usuario) não gostou do sistema e deseja avalia-lo</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) avaliou o sistema </p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) está se sentindo muito satisfeito quanto a segurança e outros atributos do sistema </p><p>2. Ao longo que o [usuário](../lexicos/#usuario) utiliza o sistema, o mesmo gera um popup pedindo para que o sistema seja avaliado em sua tela </p><p>3. O [usuário](../lexicos/#usuario) clica para avaliar e é redirecionado para a página de avaliação </p><p>4. O [usuário](../lexicos/#usuario) avalia o sistema </p><p>5. A Equipe Rico recebe um feedback positivo</p> |
| **Restrições** | [usuário](../lexicos/#usuario) feliz com o sistema, [usuário](../lexicos/#usuario) chateado com o sistema |
| **Exceção** | <p>A internet parar de funcionar durante ação</p> |

##  Avaliar o App - V2
| **Título**  | **Avaliar o App - V2** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) deseja realizar uma avaliação da plataforma |
| **Contexto** | <p> **Pré-condição:** </p><p>O [usuário](../lexicos/#usuario) gostou muito do sistema e deja avalia-lo</p><p>O [usuário](../lexicos/#usuario) não gostou do sistema e deseja avalia-lo</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) avaliou o sistema </p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) está se sentindo muito satisfeito quanto a segurança e outros atributos do sistema </p><p>2. Após um tempo de uso, o sistema gera um popup, ao [usuário](../lexicos/#usuario), pedindo para que o sistema seja avaliado em sua tela</p><p>3. O [usuário](../lexicos/#usuario) clica em avaliar e é redirecionado para a página de avaliação </p><p>4. O [usuário](../lexicos/#usuario) avalia o sistema </p><p>5. A Equipe Rico recebe um feedback positivo</p> |
| **Restrições** | [usuário](../lexicos/#usuario) feliz com o sistema, [usuário](../lexicos/#usuario) chateado com o sistema |
| **Exceção** | <p>A internet parar de funcionar durante ação</p> |

##  Solicitar ajuda
| **Título**  | **Solicitar ajuda** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) sanou algum problema encontrado |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) está com algum problema</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) está isento de problemas</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet ou Acesso á rede telefonica |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) se depara com uma problema no sistema que não consegue solucionar </p><p>2. O [usuário](../lexicos/#usuario) entra no sistema com o intuito de buscar formas de pedir [ajuda](../lexicos/#ajuda-faq) </p><p>3. O sistema dá a possibilidade do usuário ter uma conversa online direto com a Equipe Rico, ou com o bot do sistema codificado com inteligência artificial, ou via telefone, ou pelo fórum de [dúvidas](../lexicos/#duvidas) </p><p>4. O [usuário](../lexicos/#usuario) escolhe a forma que melhor lhe agrada </p><p>5. O [usuário](../lexicos/#usuario) tem seu problema resolvido</p> |
| **Restrições** | [Usuários]() com problemas |
| **Exceção** | <p>A internet parar de funcionar durante ação</p><p> Não ter sinal para efetuar uma ligação</p> |

##  Solicitar ajuda - V2
| **Título**  | **Solicitar ajuda - V2** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) objetiva sanar algum problema ou dúvida  |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) está com algum problema</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) está isento de problemas</p> |
| **Atores** | [usuário](../lexicos/#usuario), Sistema |
| **Recursos** | Acesso a internet ou Acesso á rede telefonica |
| **Episódios** | <p>1. O [usuário](../lexicos/#usuario) se depara com uma problema no sistema que não consegue solucionar </p><p>2. O [usuário](../lexicos/#usuario) entra no sistema com o intuito de buscar formas de pedir [ajuda](../lexicos/#ajuda-faq) </p><p>3. O sistema dá a possibilidade do usuário ter uma conversa online direto com a Equipe Rico, ou com o bot do sistema codificado com inteligência artificial, ou via telefone, ou pelo fórum de [dúvidas](../lexicos/#duvidas) </p><p>4. O [usuário](../lexicos/#usuario) escolhe a forma que melhor lhe agrada </p><p>5. O [usuário](../lexicos/#usuario) tem seu problema resolvido</p> |
| **Restrições** | [Usuários]() com problemas |
| **Exceção** | <p>A internet parar de funcionar durante ação</p><p> Não ter sinal para efetuar uma ligação</p> |

##  Obter acesso a informações gerais
| **Título**  | **Obter acesso a informações gerais** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) pode ficar por dentro do que está acontecendo nos mercados |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) está desinformado com o que está acontecendo no mercado</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) fica informado quanto ao mercado</p> |
| **Atores** | [usuário](../lexicos/#usuario) |
| **Recursos** | Acesso a internet |
| **Episódios** | <p> 1. O [usuário](../lexicos/#usuario) está curioso quanto as rentabilidades do mercado </p><p>2. O [usuário](../lexicos/#usuario) entra no sistema  </p><p>3. O [usuário](../lexicos/#usuario) vê a aba "Investimentos", "Análises" e ["Destaques da semana"](#destaques-da-semana) </p><p>4. O [usuário](../lexicos/#usuario) entra em cada tópico e se informa da situação financeira do mundo </p> |
| **Restrições** | [Usuários]() curiosos |
| **Exceção** | <p>A internet parar de funcionar durante ação</p> |

##  Obter acesso a informações gerais - V2
| **Título**  | **Obter acesso a informações gerais - V2** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) deseja ficar por dentro do que está acontecendo nos mercados, seja quanto a índices |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) está desinformado com o que está acontecendo no mercado</p><p>**Pós-condição:** O [usuário](../lexicos/#usuario) fica informado quanto ao mercado</p> |
| **Atores** | [usuário](../lexicos/#usuario) |
| **Recursos** | Acesso a internet |
| **Episódios** | <p> 1. O [usuário](../lexicos/#usuario) está curioso quanto as rentabilidades do mercado </p><p>2. O [usuário](../lexicos/#usuario) entra no sistema  </p><p>3. O [usuário](../lexicos/#usuario) vê a aba "Investimentos", "Análises" e ["Destaques da semana"](#destaques-da-semana) </p><p>4. O [usuário](../lexicos/#usuario) entra em cada tópico e se informa da situação financeira do mundo </p> |
| **Restrições** | [Usuários]() curiosos |
| **Exceção** | <p>A internet parar de funcionar durante ação</p> |

## Conectar-se a um Home Broker
| **Título**  | **Conectar-se a um Home Broker** |
| ------------- | ------------- |
| **Objetivo**  |O usuaŕio deseja se concectar a um Home Broker, um sistema que permite a compra e venda de ações e outros ativos através da internet. Isto é, ele liga o usuário à Bolsa de Valores.|
| **Contexto** |<p> **Pré-condição:** O [usuário](../lexicos/#usuario) pretende [comprar](#comprar-acao) ou vender de ações e outros ativos</p><p>**Pós-condição:**    O [usuário](../lexicos/#usuario) vende e compra outros ativos</p>|
| **Atores** |<p>1. Usuário</p><p>2. Sistema</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário acessa a RICO</p><p>O usuário acessa o Home Broker do sistema</p><p>O usuário decide se quer [comprar](#comprar-acao) ou vender ações ou ativos</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário ser menor de idade</p>|


## Participar de Ofertas Públicas
| **Título**  | **O usuário deseja participar de Ofertas Públicas** |
| ------------- | ------------- |
| **Objetivo**  |O usuário deseja participar de uma oferta pública, a mesma ocorre quando uma empresa disponibiliza ao público ações, cotas de um [fundo de investimento](../lexicos/#fundo-de-investimentos) ou qualquer outro valor mobiliário previsto na regulamentação do mercado de capitais.|
| **Contexto** |<p> **Pré-condição:** O [usuário](../lexicos/#usuario) pretende participar de uma oferta pública, o mesmo deve ter também uma [conta](../lexicos/#conta) na RICO</p><p>**Pós-condição:** O usuário teŕa a oportunidade de investir em empresas que estão em fase de crescimento e obter bons retornos por isso, ou adquirir cotas de novos fundos.</p>|
| **Atores** |<p>1.Usuário</p><p>2.Empresas</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>Empresas disponibilizam ao público ações</p><p>O usuário compra ofertas públicas</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário ser menor de idade</p>|


## Redefinir Senha
| **Título**  | **Redefinir Senha** |
| ------------- | ------------- |
| **Objetivo**  |O usário necessita redefir sua senha|
| **Contexto** |<p> **Pré-condição:** O [usuário](../lexicos/#usuario) deve ter uma [conta](../lexicos/#conta) na RICO</p><p>**Pós-condição:** O usuário redefinirá sua senha</p>|
| **Atores** |<p>1. Usuário</p>2. Sistema</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário não sabe sua senha</p><p>O usuário teve seu celular roubado</p><p>O usuário solicita uma redefinição de senha por computador ou pelo celular</p><p>O sistema manda um e-mail com etapas para redefinição de senha</p><p>O usuário escolhe uma nova senha para acessas a RICO</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|


## Resgatar Dinheiro
| **Título**  | **Resgatar Dinheiro** |
| ------------- | ------------- |
| **Objetivo**  |O usuário deseja resgatar o [dinheiro](../lexicos/#dinheiro) proveniente de algum [investimento](../lexicos/#investimento)|
| **Contexto** |<p> **Pré-condição:** O [usuário](../lexicos/#usuario) deve ter uma [conta](../lexicos/#conta) na RICO e ter feito algum [investimento](../lexicos/#investimento)</p><p>**Pós-condição:** O usuário resgata o seu [dinheiro](../lexicos/#dinheiro)</p>|
| **Atores** |<p>1. Usuário</p><p>2. RICO</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário solicita um [investimento](../lexicos/#investimento)</p><p>A RICO vende os ativos nos quais você posicionou. Isso tem impacto direto na velocidade com a qual o [dinheiro](../lexicos/#dinheiro) cai em sua [conta](../lexicos/#conta) do [Banco](../lexicos/#banco).</p><p>O usuário recebe o seu [dinheiro](../lexicos/#dinheiro) após um tempo|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|


## Negociar na BM&F

| **Título**  | **Investimento em BM&F** |
| ------------- | ------------- |
| **Objetivo**  |O usuário deseja negociar na BM&F, que significa Bolsa de Mercadorias & Futuros. Ela também é chamada pelos jornais e noticiários de "Bolsa de Valores" ou apenas de "a Bolsa".O seu maior objetivo é registrar e negociar operações financeiras.|
| **Contexto** |<p> **Pré-condição:** O [usuário](../lexicos/#usuario) deve ter uma [conta](../lexicos/#conta) na RICO e de estar buscando por [investimentos](../lexicos/#investimento)</p><p>**Pós-condição:** O usuário negocia na BM&F por exemplo ações, cotas de fundos de investimento, preços de bens agrícolas e recursos naturais (commodities), além de títulos públicos e privados</p>|
| **Atores** |<p>1. Usuário</p><p>2. BM&F</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** | <p>O [usuário](../lexicos/#usuario) deseja investir</p><p>O usuário acessa a BM&F</p> <p>O [usuário](../lexicos/#usuario) compra por exemplo ações, cotas de fundos de investimento, preços de bens agrícolas e recursos naturais (commodities), além de títulos públicos e privados</p> <p>A BM&F disponibiliza e garante que o [investimento](../lexicos/#investimento) foi feito</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|


## Utilizar Alvo Programado
| **Título**  | **Alvo Programado** |
| ------------- | ------------- |
| **Objetivo**  | O time da RICO identifica boas oportunidades de ganhos no mercado e sugere uma operação pré-programada com preço de compra e preços de venda, cabendo ao [investidor](../lexicos/#investidor), se concordar com a estratégia, informar apenas a quantidade desejada e deixar a operação prosseguir de modo automático|
| **Contexto** |<p> **Pré-condição:** O [usuário](../lexicos/#usuario) se interessa pela ferramenta [alvo programado](../lexicos/#alvo-programado), o mesmo deve ter uma [conta](../lexicos/#conta) na RICO</p><p> **Pós-condição:** A RICO disponibiliza análise de [investimentos](../lexicos/#investimento) e sugere ao usuário</p>|
| **Atores** |<p>1. Usuário</p><p>2. RICO</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>A RICO identifica boas oportunidades de ganhos no mercado e sugere uma operação pré-programada com preço de compra e preços de venda</p><p>O usuário avalia, informa a quantidade desejada e a operação pressegue de modo automático</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|

##  Investir por Categoria
| **Título**  | **Investir por Categoria** |
| ------------- | ------------- |
| **Objetivo**  | Possibilitar o [usuário](../lexicos/#usuario) de escolher por categoria o tipo de [investimento](../lexicos/#investimento) que quer realizar e, dentro da categoria selecionada, escolher o que comprar |
| **Contexto** | <p> **Pré-condição:** O [usuário](../lexicos/#usuario) tem uma quantidade de [dinheiro](../lexicos/#dinheiro) para [comprar uma ação](#comprar-acao)</p><p>**Pós-condição:**    O [usuário](../lexicos/#usuario) investe seu [dinheiro](../lexicos/#dinheiro) em alguma ação</p>  |
| **Atores** | <p>1. [usuário](../lexicos/#usuario)</p><p>2. Sistema</p> |
| **Recursos** | <p>1. Acesso a internet</p><p>2. [Dinheiro](../lexicos/#dinheiro) necessário depositado na [conta](../lexicos/#conta)</p> |
| **Episódios** | <p>O [usuário](../lexicos/#usuario) acessa sua [conta](../lexicos/#conta)</p><p>O [usuário](../lexicos/#usuario) visualiza sua quantidade de [dinheiro](../lexicos/#dinheiro) X</p><p>O [usuário](../lexicos/#usuario) não quer deixar seu [dinheiro](../lexicos/#dinheiro) parado</p><p>O [usuário](../lexicos/#usuario), por ser [conservador](../lexicos/#conservador), quer procurar nas categorias os de renda fixa</p><p>o [usuário](../lexicos/#usuario) encontra o que quer [comprar](#comprar-acao) e investe seu [dinheiro](../lexicos/#dinheiro) </p> |
| **Restrições** | <p>O [usuário](../lexicos/#usuario) que possui [dinheiro](../lexicos/#dinheiro) na carteira</p><p>[usuário](../lexicos/#usuario) que não quer deixar o [dinheiro](../lexicos/#dinheiro) parado</p> |
| **Exceção** | <p>A internet parar de funcionar no meio da ação</p><p>O [usuário](../lexicos/#usuario) não ter [dinheiro](../lexicos/#dinheiro) suficiente pra [comprar](#comprar-acao) determinada ação</p><p>O usuário ser menor de idade</p>|

##  Depositar na conta da Rico
| **Título**  | **Depositar na conta da Rico** |
| ------------- | ------------- |
| **Objetivo**  | O usuário pode depositar [dinheiro](../lexicos/#dinheiro) do seu [banco](../lexicos/#banco) para a sua [conta](../lexicos/#conta) Rico e investi-lo|
| **Contexto** | <p> **Pré-condição:** Ter uma [conta](../lexicos/#conta-corrente) bancária e uma [conta](../lexicos/#conta) na Rico</p><p>**Pós-condição:** o usuário terá o [dinheiro](../lexicos/#dinheiro) na sua [conta](../lexicos/#conta) Rico e poderá investi-lo</p>  |
| **Atores** | <p> 1.[usuário](../lexicos/#usuario)</p><p>2. Sistema</p> <p>3. [Banco](../lexicos/#banco)</p>|
| **Recursos** | Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** | <p>O [usuário](../lexicos/#usuario) não possui [dinheiro](../lexicos/#dinheiro) na [conta](../lexicos/#conta) Rico</p><p>O [usuário](../lexicos/#usuario) quer investir e para isso necessita ter [dinheiro](../lexicos/#dinheiro) na [conta](../lexicos/#conta) Rico</p><p>O [usuário](../lexicos/#usuario) realiza uma transferência de um [banco](../lexicos/#banco) para a [conta](../lexicos/#conta) Rico</p> <p>O [usuário](../lexicos/#usuario) possui [dinheiro](../lexicos/#dinheiro) na [conta](../lexicos/#conta) rico</p> <p>O [banco](../lexicos/#banco) do usuário envia o [dinheiro](../lexicos/#dinheiro) para a [conta](../lexicos/#conta) Rico</p><p>O sistema recebe [dinheiro](../lexicos/#dinheiro) do [banco](../lexicos/#banco) </p>|
| **Restrições** | Fluxo interativo |
| **Exceção** | <p>A internet parar de funcionar no meio da ação</p><p>O [usuário](../lexicos/#usuario) fechar o aplicativo durante a ação</p><p>O usuário não possui [dinheiro](../lexicos/#dinheiro)</p> <p>Não estar no horário de transferência bancária</p><p>O usuário ser menor de idade</p>|

## Alavancagem
| **Título**  | **Alavancagem** |
| ------------- | ------------- |
| **Objetivo**  |[Alavancagem](../lexicos/#alavancar) é a utilização de determinados recursos para aproveitar oportunidades de multiplicar seus resultados. Ela funciona como um limite de [crédito](../lexicos/#credito), possibilitando que você invista um valor maior do que tem em [conta](../lexicos/#conta)|
| **Contexto** |<p> **Pré-condição:** Ter uma [conta](../lexicos/#conta) na Rico</p><p>**Pós-condição:** o usuário será capaz de utilizar a [alavancagem](../lexicos/#alavancar)</p>|
| **Atores** |1. Usuário|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário deseja investir valores maiores, mas não possui muito [dinheiro](../lexicos/#dinheiro)</p><p>O usuário faz uma [alavancagem](../lexicos/#alavancar)</p><p>O usuário investe uma quantia maior de [dinheiro](../lexicos/#dinheiro) maior</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|

## Realizar Alavancagem - V2
| **Título**  | **Realizar Alavancagem - V2** |
| ------------- | ------------- |
| **Objetivo**  |[Alavancagem](../lexicos/#alavancar) é a utilização de determinados recursos para aproveitar oportunidades de multiplicar seus resultados. Ela funciona como um limite de [cédito](../lexicos/#credito), possibilitando que você invista um valor maior do que tem em [conta](../lexicos/#conta)|
| **Contexto** |<p> **Pré-condição:** Ter uma [conta](../lexicos/#conta) na Rico</p><p>**Pós-condição:** o usuário será capaz de utilizar a [alavancagem](../lexicos/#alavancar)</p>|
| **Atores** |1. Usuário|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário deseja investir valores maiores, mas não possui muito [dinheiro](../lexicos/#dinheiro)</p><p>O usuário faz uma [alavancagem](../lexicos/#alavancar)</p><p>O usuário investe uma quantia maior de [dinheiro](../lexicos/#dinheiro) maior</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|

## Aplicação Automática
| **Título**  | **Aplicação Automática** |
| ------------- | ------------- |
| **Objetivo**  |[Aplicação automática](../lexicos/#aplicacao-automatica) ocorre quando o [dinheiro](../lexicos/#dinheiro) presente na [conta](../lexicos/#conta-corrente) corrente do cliente, ou parte dele, é direcionado para algum tipo de [investimento](../lexicos/#investimento) do [banco](../lexicos/#banco)|
| **Contexto** |<p> **Pré-condição:** Ter uma [conta](../lexicos/#conta) na Rico</p><p>**Pós-condição:** O usuário será capaz de direcionar o seu [dinheiro](../lexicos/#dinheiro) para algum tipo de [investimento](../lexicos/#investimento) de um [banco](../lexicos/#banco)</p>|
| **Atores** |<p>1. Usuário</p><p>2. [Banco](../lexicos/#banco)</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário possui [dinheiro](../lexicos/#dinheiro) em sua conta</p><p>O [banco](../lexicos/#banco) propõe algum [investimento](../lexicos/#investimento)</p><p>O usário permite o [banco](../lexicos/#banco) utilizar do seu [dinheiro](../lexicos/#dinheiro) para algum [investimento](../lexicos/#investimento) do [banco](../lexicos/#banco)</p><p>O usuário pode ter ou não rentabilidade</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta-corrente) bancária</p><p>O usuário ser menor de idade</p>|

## Análise Fundamentalista
| **Título**  | **Análise Fundamentalista** |
| ------------- | ------------- |
| **Objetivo**  |A análise fundamentalista consiste na avaliação de uma empresa de acordo com sua situação financeira, mercadológico e até mesmo política. Tem como base o uso de dados econômicos, indicadores do mercado financeiro, balanços e resultado das empresas, além de métodos próprios a fim de identificar perspectivas e oportunidades de mercado.|
| **Contexto** |<p> **Pré-condição:** Desejo de aumentar a probabilidade de lucro</p><p>**Pós-condição:** O usuário poderá lucrar mais com [investimentos](../lexicos/#investimento)</p>|
| **Atores** |<p>1. Usuário</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário quer aumentar sua probabilidades de ganhos</p><p>O usuário faz uma análise fundamentalista sobre empresas e indicadores do mercado financeiro por exemplo</p><p>O usuário aumenta sua chance de lucro com [investimentos](../lexicos/#investimento), principalmente em renda variável</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|

## Destaques da semana
| **Título**  | **Destaques da semana** |
| ------------- | ------------- |
| **Objetivo**  |Informar ao usuário os [destaques da semana](../lexicos/#destaques-da-semana) no mercado financeiro|
| **Contexto** |<p> **Pré-condição:** Ter uma [conta](../lexicos/#conta) na Rico</p><p>**Pós-condição:** O usuário será capaz de ver os [destaques da semana](../lexicos/#destaques-da-semana)</p>|
| **Atores** |<p>1. Usuário</p><p>2. RICO</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário prentende investir</p>O usuário acessa a RICO<p></p><p>A RICO disponibiliza informações semanais sobre o mercado de ações feitas por especialistas</p><p>O usuário acessa os [destaques da semana](../lexicos/#destaques-da-semana)</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|

## Aprender a investir com a Rico

| **Título**  | **Aprender a investir com a Rico** |
| ------------- | ------------- |
| **Objetivo**  |Ensinar o usuário a investir da maneira correta|
| **Contexto** |<p> **Pré-condição:** Ter uma [conta](../lexicos/#conta) na Rico</p><p>**Pós-condição:** O usuário será capaz de investir da melhor forma com especialistas da RICO</p>|
| **Atores** |<p>1. Usuário</p><p>2. RICO</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário não sabe investir</p><p>O usuário acessa a RICO</p><p>A RICO disponibiliza informações em formato de texto, vídeos, sobre o mercado de ações, essas feitas por especialistas</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|

## Sair do Aplicativo
| **Título**  | **Sair do Aplicativo** |
| ------------- | ------------- |
| **Objetivo**  |O usuário necessita sair da aplicação|
| **Contexto** |<p> **Pré-condição:** O usuário deve ter também uma [conta](../lexicos/#conta) na RICO</p><p>**Pós-condição:** O usuário sairá da aplicação</p>|
| **Atores** |1. Usuário|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário utilizou a rico por um determinado tempo do dia e resolveu ir fazer outra coisa</p>O usuário sai do sistema<p></p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p>|

## Sair do Aplicativo - V2
| **Título**  | **Sair do Aplicativo - V2** |
| ------------- | ------------- |
| **Objetivo**  | O [usuário](../lexicos/#usuario) irá encerrar a sessão de seu login que havia sido realizado pelo aplicativo e fechar a plataforma |
| **Contexto** |<p> **Pré-condição:** O usuário deve ter também uma [conta](../lexicos/#conta) na RICO</p><p>**Pós-condição:** O usuário sairá da aplicação</p>|
| **Atores** |1. Usuário|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário utilizou a rico por um determinado tempo do dia e resolveu ir fazer outra coisa</p>O usuário sai do sistema<p></p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p>|

## Fazer simulação gráfica de investimentos

| **Título**  | **Fazer simulação gráfica de investimentos** |
| ------------- | ------------- |
| **Objetivo**  |Fazer com que o usuário seja capaz de simular informações sobre seus [investimentos](../lexicos/#investimento)|
| **Contexto** |<p> **Pré-condição:** O usuário deve ter feito algum [investimento](../lexicos/#investimento) e deve ter também uma [conta](../lexicos/#conta) na RICO</p><p>**Pós-condição:** o usuário visualizará uma simulação com informações a respeito de seus [investimentos](../lexicos/#investimento)</p>|
| **Atores** |<p>1. Usuário</p><p>2. RICO</p>|
| **Recursos** |Acesso a internet, ter um smartphone ou computador com acesso a internet|
| **Episódios** |<p>O usuário faz algum [investimento](../lexicos/#investimento)</p><p>O usuário utiliza a ferramenta para simular seus [investimentos](../lexicos/#investimento)</p><p>O sistema simula informações e [gráficos](../lexicos/#grafico) a respeito dos [investimentos](../lexicos/#investimento) realizados pelo usuário</p>|
| **Restrições** |<p>Fluxo interativo</p><p>Boa experiência de usuário</p>|
| **Exceção** |<p>O usuário não possuir [conta](../lexicos/#conta) na RICO</p><p>A internet parar de funcionar no meio da ação</p><p>O usuário fechar a aplicação antes de terminar a ação.</p><p>O usuário ser menor de idade</p>|


## Histórico de revisões

Data | Responsável | Versão | Alteração 
---- | ----------- | ------ | ---------
26/09/2019 | [@dansousamelo](https://github.com/dansousamelo) | 1 | Adicionado cenários de 17 á 23
26/09/2019 | [@dansousamelo](https://github.com/dansousamelo) | 1.1 | Adicionado cenários de 17 á 30
27/09/2019 | [@pedroMiranda7410](https://github.com/pedroMiranda7410) | 1.2 | Adicionado cenários de 1 á 16
30/09/2019 | [@dansousamelo](https://github.com/dansousamelo) | 1.3 | Adicionado links ao primeiro cenário

## Referências
* <p align="justify">RICO.COM.VC (Brasil). Aprenda com o apoio do melhor conteúdo. Brasil, 2011. Disponível em: https://www.rico.com.vc/aprenda. Acesso em: 25 set. 2019.</p>

 * <p align="justify">RICO.COM.VC (Brasil). Dicionário de Finanças. Brasil, 2011. Disponível em: https://www.rico.com.vc/aprenda/dicionario-de-financas. Acesso em: 25 set. 2019.</p>

 * <p align="justify">RICO.COM.VC (Brasil). Educação Financeira - Conceitos e 11 Dicas Para Ficar Rico. Brasil, 2011. Disponível em: https://blog.rico.com.vc/educacao-financeira. Acesso em: 25 set. 2019.</p>

 * <p align="justify">SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10; Disponível em https://aprender.ead.unb.br/pluginfile.php/725948/mod_resource/content/1/Aula%2010.pdf.</p>
