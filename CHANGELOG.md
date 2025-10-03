# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

# [2.4.1](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.4.1...v) (2025-10-01)


### Bug Fixes

* **histórico:** corrige erro ao baixar de vários itens causado na atualização anterior ([5db44af](https://github.com/gerenciar/gerenciar_autoescola/commit/5db44af286c9a2dfde2412a6b802b17cfde230f3)), closes [#2386](https://github.com/gerenciar/gerenciar_autoescola/issues/2386)
* **cadastro:** corrige reativação de alunos causado na última atualização ([cba5e7a](https://github.com/gerenciar/gerenciar_autoescola/commit/cba5e7a7a9b722e10e797825f608e69aacfc852d)), closes [#2373](https://github.com/gerenciar/gerenciar_autoescola/issues/2373)
* **login:** corrige acesso do aluno inativo causado na última atualização ([aa76ec6](https://github.com/gerenciar/gerenciar_autoescola/commit/aa76ec6baf03eff4369717edb29fe3538934cff0)), closes [#2264](https://github.com/gerenciar/gerenciar_autoescola/issues/2264)



# [2.4.0](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.4.0-thiago...v2.4.0) (2025-09-18)


### Bug Fixes

* **agenda:** remove filtro de status da aula ([4136b14](https://github.com/gerenciar/gerenciar_autoescola/commit/4136b145693505a2a2a9cec6f60843fbf047773c)), closes [#2278](https://github.com/gerenciar/gerenciar_autoescola/issues/2278)
* **exame:** adiciona campos obrigatórios de data na solicitação de exame ([2b0ce9c](https://github.com/gerenciar/gerenciar_autoescola/commit/2b0ce9c6ab28b110e381d6fd47a6c192d4f5afde)), closes [#2252](https://github.com/gerenciar/gerenciar_autoescola/issues/2252)
* **login:** bloqueia acesso ao sistema de alunos inativos e desistentes ([f15f3c9](https://github.com/gerenciar/gerenciar_autoescola/commit/f15f3c91cbafae042d90e30e814784cf057a3d02)), closes [#2264](https://github.com/gerenciar/gerenciar_autoescola/issues/2264)
* **relatório:** corrige soma incorreta de valores do relatório de taxas ([98da231](https://github.com/gerenciar/gerenciar_autoescola/commit/98da23102418d68ade3ea9902dfd64834d39115b)), closes [#1629](https://github.com/gerenciar/gerenciar_autoescola/issues/1629)
* **cadastro:** corrige cadastro de forma de pagamento ao criar conta autoescola ([ac8b0d0](https://github.com/gerenciar/gerenciar_autoescola/commit/ac8b0d029412ba8be3ba430491827461219888fb)), closes [#2014](https://github.com/gerenciar/gerenciar_autoescola/issues/2014)
* **financeiro:** adiciona campos obrigatórios ao realizar lançamento no receber ([cbcf104](https://github.com/gerenciar/gerenciar_autoescola/commit/cbcf104edc6876e34a1df0ca64396e0c426b2988)), closes [#2291](https://github.com/gerenciar/gerenciar_autoescola/issues/2291)
* **financeiro:** corrige o lançamento automático no caixa quando baixa uma ou mais despesas ([292258e](https://github.com/gerenciar/gerenciar_autoescola/commit/292258ebcc8950c63b6bfe5bebffbb106e461525)), closes [#2125](https://github.com/gerenciar/gerenciar_autoescola/issues/2125)
* **financeiro:** torna Conta p/ Conciliação obrigatória ao realizar baixa ([ce41df9](https://github.com/gerenciar/gerenciar_autoescola/commit/ce41df981f1a2e9f3339b36dd6286707a0870c5e)), closes [#2140](https://github.com/gerenciar/gerenciar_autoescola/issues/2140)


### Features

* **agenda:** permite agendamento para alunos inativos ([e498c05](https://github.com/gerenciar/gerenciar_autoescola/commit/e498c0553906e716698ca443d71d9ab891a267f3)), closes [#2244](https://github.com/gerenciar/gerenciar_autoescola/issues/2244)
* **cadastro:** adiciona novo status desistente para alunos ([5d0065b](https://github.com/gerenciar/gerenciar_autoescola/commit/5d0065b52226c9d629cfde19697db62e17f9dfba)), closes [#1339](https://github.com/gerenciar/gerenciar_autoescola/issues/1339)
* **cadastro:** envia e-mail para m.gerenciarautoescola@gmail.com ao cadastrar CFC ([cf71d43](https://github.com/gerenciar/gerenciar_autoescola/commit/cf71d43223c944864cd6ac0a8caa943f2037b2c8)), closes [#2109](https://github.com/gerenciar/gerenciar_autoescola/issues/2109)
* **cadastro:** torna campos obrigatórios para alunos da CFC Almeida ([94fad1b](https://github.com/gerenciar/gerenciar_autoescola/commit/94fad1b568b59dbedc754fa0b1c1769b19e0942c)), closes [#1670](https://github.com/gerenciar/gerenciar_autoescola/issues/1670)
* **cadastro:** adiciona filtros de busca na área de inativos ([0d9102d](https://github.com/gerenciar/gerenciar_autoescola/commit/0d9102d3f0c980b936b8fea5ffbe8ba156acf045)), closes [#1861](https://github.com/gerenciar/gerenciar_autoescola/issues/1861)
* **relatório:** adiciona campo data de vencimento no recibo térmico ([bc5ec48](https://github.com/gerenciar/gerenciar_autoescola/commit/bc5ec48ff644a32262ae072d8819f45c12b05adb)), closes [#1928](https://github.com/gerenciar/gerenciar_autoescola/issues/1928)
* **relatório:** adiciona campo observação no relatório de ([910dc9d](https://github.com/gerenciar/gerenciar_autoescola/commit/910dc9da5872a3933dffbb6be405070a919620f8)), closes [#1283](https://github.com/gerenciar/gerenciar_autoescola/issues/1283)



## [2.3.1](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.3.1-tharc...v2.3.1) (2025-09-03)


### Bug Fixes

* **acerto:** corrige valor reprovação zerado ([2b779c9](https://github.com/gerenciar/gerenciar_autoescola/commit/2b779c9297ad356780b44fbff1d9d812eff58ba2)), closes [#1905](https://github.com/gerenciar/gerenciar_autoescola/issues/1905)
* **login:** corrige erro no acesso do aluno causado pela nova conf de proxy ([6b423de](https://github.com/gerenciar/gerenciar_autoescola/commit/6b423de6e9695fbada60ce15ef9b77674e395172))
* **cadastro:** mostra produtos/serviços inativos na grade de pagamento do funcionário ([f5d8a55](https://github.com/gerenciar/gerenciar_autoescola/commit/f5d8a559c64eebd4d342dd485f418ebb42d5cb9b)), closes [#1877](https://github.com/gerenciar/gerenciar_autoescola/issues/1877)



# [2.3.0](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.3.0-thiago...v2.3.0) (2025-09-03)


### Bug Fixes

* **cadastro:** aumenta capacidade de caracteres do nome do produto/serviço para 100 ([1e59586](https://github.com/gerenciar/gerenciar_autoescola/commit/1e5958678d2edf77bc4ce622b44f30957cdb0da1)), closes [#2225](https://github.com/gerenciar/gerenciar_autoescola/issues/2225)
* **financeiro:** adiciona opção de selecionar conta Cel Cash no cadastro de contas ([0b8525e](https://github.com/gerenciar/gerenciar_autoescola/commit/0b8525e4dc8b08c339213b3035d4dc57c6d23ddb)), closes [#1579](https://github.com/gerenciar/gerenciar_autoescola/issues/1579)
* **mobile:** corrige proporção esticada de ícones ([80febc0](https://github.com/gerenciar/gerenciar_autoescola/commit/80febc0e10d58f5c14b3dc39b3eaadffb3c794ed)), closes [#1523](https://github.com/gerenciar/gerenciar_autoescola/issues/1523)
* **relatório:** corrige quantidade de aulas na impressão de tickets ([7f3eaf2](https://github.com/gerenciar/gerenciar_autoescola/commit/7f3eaf278beb3bf6a87788b04f3308b6bdda6dee)), closes [#2135](https://github.com/gerenciar/gerenciar_autoescola/issues/2135)
* **relatório:** mostra taxas que não apareciam no relatório de taxas ([6a214ec](https://github.com/gerenciar/gerenciar_autoescola/commit/6a214ecfb842ba940feea9470f38dc340249acfe))
* **histórico:** corrige erro ao entrar no histórico na área do aluno ([4dbb5cf](https://github.com/gerenciar/gerenciar_autoescola/commit/4dbb5cf6d780ab742c9cc971adde4621e6a9b9d1)), closes [#1600](https://github.com/gerenciar/gerenciar_autoescola/issues/1600)


### Features

* **cadastro:** torna endereço obrigatório para alunos ([ee5a34a](https://github.com/gerenciar/gerenciar_autoescola/commit/ee5a34af8dc44cac768216e635d4d1e723968484)), closes [#2202](https://github.com/gerenciar/gerenciar_autoescola/issues/2202)
* **cadastro:** adiciona obrigatoriedade em campos para alunos exclusivo cfc globo ([4309163](https://github.com/gerenciar/gerenciar_autoescola/commit/43091633f7363575d60698a05f0de004d413e9f6)), closes [#2012](https://github.com/gerenciar/gerenciar_autoescola/issues/2012)
* **caixa:** adiciona coluna data_inclusao na grade do caixa ([a6831ec](https://github.com/gerenciar/gerenciar_autoescola/commit/a6831ec2abefb2abec919239608d9c6b59a8164e)), closes [#1645](https://github.com/gerenciar/gerenciar_autoescola/issues/1645)
* **financeiro:** adiciona '/pix' ás opções de boleto em contas a receber ([150f428](https://github.com/gerenciar/gerenciar_autoescola/commit/150f4280c865af9f5765256e79c27bf8230dcce4)), closes [#1858](https://github.com/gerenciar/gerenciar_autoescola/issues/1858)



# [2.2.0](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.2.0-thiago...v2.2.0) (2025-08-21)


### Bug Fixes

* **cadastro:** corrige campos nulos na tabela matriz de autoescolas ([f6d5d99](https://github.com/gerenciar/gerenciar_autoescola/commit/f6d5d99fffe5382323788b9c9a8e7c321dcc3cfc)), closes [#1646](https://github.com/gerenciar/gerenciar_autoescola/issues/1646)
* **financeiro:** corrige fluxo contas a pagar - baixa ([d38f895](https://github.com/gerenciar/gerenciar_autoescola/commit/d38f895cfffabf991603caee2c022daf6f612210)), closes [#1612](https://github.com/gerenciar/gerenciar_autoescola/issues/1612)
* **relatório:** corrige a quantidade de serviços por valor na impressão de tickets ([7578cd2](https://github.com/gerenciar/gerenciar_autoescola/commit/7578cd2de936b56e5e137a726c1981f796751612)), closes [#2099](https://github.com/gerenciar/gerenciar_autoescola/issues/2099)
* **relatório:** corrige impressão de comissão por venda ([b14e315](https://github.com/gerenciar/gerenciar_autoescola/commit/b14e31598144d70d957f420c5d6f1dc86ce9f05a)), closes [#2041](https://github.com/gerenciar/gerenciar_autoescola/issues/2041)


### Features

* **agenda:** adiciona parâmetro que bloqueia recepcionista de cancelar uma aula agendada ([a48c4cc](https://github.com/gerenciar/gerenciar_autoescola/commit/a48c4cca90393801f32c2975f985a4469c9ff086)), closes [#2115](https://github.com/gerenciar/gerenciar_autoescola/issues/2115)



### [2.1.2](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.1.0-try-catch-caixa...v2.1.2) (2025-08-13)


### Bug Fixes

* **boleto:** corrige erro ao tentar cancelar boleto depois de 60 dias ([2879724](https://github.com/gerenciar/gerenciar_autoescola/commit/2879724f76bf2811de1f5db53ba5ae652f9bb4b8)), closes [#2044](https://github.com/gerenciar/gerenciar_autoescola/issues/2044)
* **caixa:** corrige duplicação de lançamentos pela quantidade de boletos enviados ([960f561](https://github.com/gerenciar/gerenciar_autoescola/commit/960f561cb3424ddf8ea8ffe18593de0d792a5cb3)), closes [#2046](https://github.com/gerenciar/gerenciar_autoescola/issues/2046)
* **financeiro:** filtra apenas formas de pagamento ativas ([507f3d2](https://github.com/gerenciar/gerenciar_autoescola/commit/507f3d2fc91e92e4f9fe71dba7d0bf08938a6643)), closes [#1575](https://github.com/gerenciar/gerenciar_autoescola/issues/1575)

### [2.1.1](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.1.0-try-catch-caixa...v2.1.1) (2025-07-30)


### Bug Fixes

* **caixa:** corrige parcelas faltando no caixa ([a202841](https://github.com/gerenciar/gerenciar_autoescola/commit/a2028417d04e336ad8ca60f1e844eccc8605b735))

## [2.1.0](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0...v2.1.0) (2025-07-07)


### Features

* **cadastro:** torna forma de captação obrigatória em alunos para CFC Almeida ([bbcf631](https://github.com/gerenciar/gerenciar_autoescola/commit/bbcf631d91e0f3a7b8fd8937d666250fd1ee30ca)), closes [#1632](https://github.com/gerenciar/gerenciar_autoescola/issues/1632)
* **caixa:** adiciona logs no fechamento de caixa ([7485599](https://github.com/gerenciar/gerenciar_autoescola/commit/7485599690ab57e0bfc2fbfa707f73fe807fa0ca)), closes [#1599](https://github.com/gerenciar/gerenciar_autoescola/issues/1599)


### Bug Fixes

* **agenda:** bloqueia baixa da aula se já existem 3 aulas baixadas dessa categoria no dia ([412290c](https://github.com/gerenciar/gerenciar_autoescola/commit/412290c5ed426f5936c16d8245858cef3dbe2423)), closes [#1455](https://github.com/gerenciar/gerenciar_autoescola/issues/1455)
* **indicadores:** corrige gráficos mostrando informação errada ([d710c57](https://github.com/gerenciar/gerenciar_autoescola/commit/d710c576215fce9b25ae1af4d65f1cc1732b2d9c)), closes [#1631](https://github.com/gerenciar/gerenciar_autoescola/issues/1631)

## [2.0.0](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.10...v2.0.0) (2025-06-25)

### Bug Fixes

* **acerto:** corrige valor total do acerto ao gerar ([60eb53b](https://github.com/gerenciar/gerenciar_autoescola/commit/60eb53bbae3c6306de1619fddcbcbeb22015baf2)), closes [#1252](https://github.com/gerenciar/gerenciar_autoescola/issues/1252)
* **caixa:** filtra formas de pagamento ativas na entrada e saída do caixa ([d5243ca](https://github.com/gerenciar/gerenciar_autoescola/commit/d5243caded784ba224e612d33edf33ccb1efa601)), closes [#1575](https://github.com/gerenciar/gerenciar_autoescola/issues/1575)

### Features

* **caixa:**: adiciona históricos de fechamento de caixa ([d4a5c58](https://github.com/gerenciar/gerenciar_autoescola/commit/d4a5c584b9d43b54040f77159157f3a3fb00eb8c)), closes [#1599](https://github.com/gerenciar/gerenciar_autoescola/issues/1599)

## [2.0.0-beta.10](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.9...v2.0.0-beta.10) (2025-06-17)


### Bug Fixes

* **acerto:** corrige soma do desconto e acrécimo na impressão do acerto ([28877c7](https://github.com/gerenciar/gerenciar_autoescola/commit/28877c7950e0869d15253e26474035839ab84812)), closes [#1316](https://github.com/gerenciar/gerenciar_autoescola/issues/1316)
* **relatórios:** corrige impressão de itens do aluno para sair a empresa correta ([f66f8b8](https://github.com/gerenciar/gerenciar_autoescola/commit/f66f8b8d1fd21fb039bfbd81333feaca291e5997)), closes [#1583](https://github.com/gerenciar/gerenciar_autoescola/issues/1583)

## [2.0.0-beta.9](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.8...v2.0.0-beta.9) (2025-06-16)


### Bug Fixes

* **relatórios:** corrige erro na data do pagamento do recibo causado na correção anterior ([95b305b](https://github.com/gerenciar/gerenciar_autoescola/commit/95b305bb593370fb1066c584025f95c6a7aba134)), closes [#1140](https://github.com/gerenciar/gerenciar_autoescola/issues/1140)

## [2.0.0-beta.8](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.7.tharc.dev...v2.0.0-beta.8) (2025-06-13)


### Features

* **relatorios:** adiciona data do pagamento no recibo de vendas ([303522d](https://github.com/gerenciar/gerenciar_autoescola/commit/303522d81d76e0792f9794b1fab6f5bcd2283390)), closes [#1140](https://github.com/gerenciar/gerenciar_autoescola/issues/1140)


### Bug Fixes

* **relatorios:** corrige impressão de aulas - matricial e lazer ([a02cf99](https://github.com/gerenciar/gerenciar_autoescola/commit/a02cf992f1ad5e7d872f448b19b39c9b50fc4883)), closes [#1290](https://github.com/gerenciar/gerenciar_autoescola/issues/1290)
* **relatorios:** corrige quantidade de parcelas em branco na impressão detalhada do acerto ([c042ec9](https://github.com/gerenciar/gerenciar_autoescola/commit/c042ec9a21c156902ac414cbb911b82de91d4eb2)), closes [#1566](https://github.com/gerenciar/gerenciar_autoescola/issues/1566)
* **layout:** corrige frase estranha em relatórios gerencias no mobile ([251bc0c](https://github.com/gerenciar/gerenciar_autoescola/commit/251bc0c40a08e08c9c4b03c9c36200f4494b1f18)), closes [#1525](https://github.com/gerenciar/gerenciar_autoescola/issues/1525)



# [2.0.0-beta.7](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.6...v2.0.0-beta.7) (2025-06-06)


### Bug Fixes

* **agenda:** corrige campo de status na impressão dos relatórios pra condizer com o calendário ([1065ddb](https://github.com/gerenciar/gerenciar_autoescola/commit/1065ddb3df94e1a3fa8be0dad426e3cb72aca37d)), closes [#1163](https://github.com/gerenciar/gerenciar_autoescola/issues/1163)
* **cadastro:** corrige cadastro de autoescolas não afetando o banco de dados ([07c546b](https://github.com/gerenciar/gerenciar_autoescola/commit/07c546b880ce9c873aa18b5a17d264214cf223f0)), closes [#1508](https://github.com/gerenciar/gerenciar_autoescola/issues/1508)
* **caixa:** evita que caixa seja duplicado por clicar várias vezes em inserir caixa ([7b7b70a](https://github.com/gerenciar/gerenciar_autoescola/commit/7b7b70a94000254e55f5559d9ba4b25875e21b70)), closes [#1532](https://github.com/gerenciar/gerenciar_autoescola/issues/1532)
* **exames:** Corrigido filtro de status para o exame de renovação ([a6ced7d](https://github.com/gerenciar/gerenciar_autoescola/commit/a6ced7d520d51639d52d09187ff96af68927102f)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)
* **login:** Recupera aviso de empresa bloqueada para admin ao logar ([58050d3](https://github.com/gerenciar/gerenciar_autoescola/commit/58050d3358fa1e65a52d87172ac886b3be07d238)), closes [#1180](https://github.com/gerenciar/gerenciar_autoescola/issues/1180)


### Features

* **cadastro:** adiciona status ao lado do serviço em cadastro de pacotes ([7276d37](https://github.com/gerenciar/gerenciar_autoescola/commit/7276d37f4f046363f3804f96a4b28ab2c5efd944)), closes [#1498](https://github.com/gerenciar/gerenciar_autoescola/issues/1498)
* **cadastro:** evita que conta destino seja cadastrado em branco em formas de pagamento ([12df428](https://github.com/gerenciar/gerenciar_autoescola/commit/12df428830e53833ed83ed75884d98fba03338cf)), closes [#1536](https://github.com/gerenciar/gerenciar_autoescola/issues/1536)
* **caixa:** centro de custos em saída filtra somente despesas ([8c26cf0](https://github.com/gerenciar/gerenciar_autoescola/commit/8c26cf04eab93b58f11b6067feb3c216f5bf67c6)), closes [#1537](https://github.com/gerenciar/gerenciar_autoescola/issues/1537)
* **relatório:** adiciona campo de observação em aulas - matricial ([700043b](https://github.com/gerenciar/gerenciar_autoescola/commit/700043b190c0cba9d11fae847b27d1ce54e3e8df)), closes [#1379](https://github.com/gerenciar/gerenciar_autoescola/issues/1379)



# [2.0.0-beta.6](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.5...v2.0.0-beta.6) (2025-06-03)


### Bug Fixes

* **agenda:** corrige campo de status na impressão dos relatórios pra condizer com o calendário ([e90f33b](https://github.com/gerenciar/gerenciar_autoescola/commit/e90f33b3bec5c3fecbb2b8dc928cd7e38875aca4)), closes [#1163](https://github.com/gerenciar/gerenciar_autoescola/issues/1163)
* **cadastro:** corrige cadastro de autoescolas não afetando o banco de dados ([651a274](https://github.com/gerenciar/gerenciar_autoescola/commit/651a274b6fde433f0df6df99fbd6165b366cb7ad)), closes [#1508](https://github.com/gerenciar/gerenciar_autoescola/issues/1508)
* **caixa:** evita que caixa seja duplicado por clicar várias vezes em inserir caixa ([984ce02](https://github.com/gerenciar/gerenciar_autoescola/commit/984ce0253d0aa2203be5ca114b3efe900f26eb1a)), closes [#1532](https://github.com/gerenciar/gerenciar_autoescola/issues/1532)
* **exames:** Corrigido filtro de status para o exame de renovação ([704a129](https://github.com/gerenciar/gerenciar_autoescola/commit/704a129943a7bb52f5b6b7b4461fa94236f14e2e)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)
* **login:** Recupera aviso de empresa bloqueada para admin ao logar ([313a683](https://github.com/gerenciar/gerenciar_autoescola/commit/313a683149b42d6539a688d9a0faad59669503dc)), closes [#1180](https://github.com/gerenciar/gerenciar_autoescola/issues/1180)


### Features

* **cadastro:** adiciona status ao lado do serviço em cadastro de pacotes ([76bc59b](https://github.com/gerenciar/gerenciar_autoescola/commit/76bc59bf49da84455c4a850b192c0052e81dada4)), closes [#1498](https://github.com/gerenciar/gerenciar_autoescola/issues/1498)



# [2.0.0-beta.5](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.5.allan.dev...v2.0.0-beta.5) (2025-05-28)


### Bug Fixes

* **catraca:** Corrigida exportação da catraca para aparecer o nome da empresa ([6283e86](https://github.com/gerenciar/gerenciar_autoescola/commit/6283e869b0e1639da2fa2331b159b3caa8f6f6b2))


### Features

* **caixa:** opção de fechar caixa na configuração de email conta com período de datas ([03b26b8](https://github.com/gerenciar/gerenciar_autoescola/commit/03b26b82a2a1cca9f38fb8fc0d0dd36b8b518c4e))



# [2.0.0-beta.4](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.4.thiago.dev...v2.0.0-beta.4) (2025-05-23)


### Bug Fixes

* **relatorio:** Corrige impressão de nomes vazios na agenda ([74528e1](https://github.com/gerenciar/gerenciar_autoescola/commit/74528e1ffa7e78e4c920110852411eac0f038f08)), closes [#1318](https://github.com/gerenciar/gerenciar_autoescola/issues/1318)
* **vendas:** Corrigido o tipo de exame aplicado ao item ao realizar venda ([57ab7ef](https://github.com/gerenciar/gerenciar_autoescola/commit/57ab7efa7c0ff6b2186d5811b4b80681ff1d8444)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)


### Features

* **adiantamento:** Adicionado status ao lado do nome no filtro de funcionário ([976dd90](https://github.com/gerenciar/gerenciar_autoescola/commit/976dd902bb6e32a5b660f8732994ff470298cc35)), closes [#1479](https://github.com/gerenciar/gerenciar_autoescola/issues/1479)
* **cadastro:** Torna campos obrigatórios no cadastro do aluno na aba de cadastro e endereço para CFC Máxima ([31a5c2c](https://github.com/gerenciar/gerenciar_autoescola/commit/31a5c2c83a69903a0894e13ddedca93669aab023)), closes [#1375](https://github.com/gerenciar/gerenciar_autoescola/issues/1375)
* **cadastro:** Torna início, vencimento e alerto do processo obrigatórios para CFC Método ([4971d66](https://github.com/gerenciar/gerenciar_autoescola/commit/4971d667b9dfb30b6511fc0d9078b73caf7f9cd7)), closes [#1303](https://github.com/gerenciar/gerenciar_autoescola/issues/1303)
* **relatorio:** adiciona filtro de aluno no relatório de exames e resultados ([6fd80c7](https://github.com/gerenciar/gerenciar_autoescola/commit/6fd80c74c5ee3dc5a63cf15411faa0e9a9aaba88)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)



# [2.0.0-beta.3](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.3.thiago.dev...v2.0.0-beta.3) (2025-05-20)


### Bug Fixes

* **exames:** Corrigido filtro de exame na tela de exames e resultados ([dd6c4c6](https://github.com/gerenciar/gerenciar_autoescola/commit/dd6c4c6da348607bd9072e0923da5dfdd4e88b81)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)


### Features

* **recibo:** Adicionado campo de data de nascimento nos modelos 1 e 2 e assinatura do aluno no modelo 1 ([f832cdf](https://github.com/gerenciar/gerenciar_autoescola/commit/f832cdf8542bfa1dc4c55af8695aee037d57d7ba)), closes [#1179](https://github.com/gerenciar/gerenciar_autoescola/issues/1179) [#1285](https://github.com/gerenciar/gerenciar_autoescola/issues/1285)
* **relatorio:** Concatenado o CPF do aluno ao lado do nome na impressão da agenda ([5dcbbd6](https://github.com/gerenciar/gerenciar_autoescola/commit/5dcbbd6235dd03d2c3afa5e54b06a1ec63354335)), closes [#1308](https://github.com/gerenciar/gerenciar_autoescola/issues/1308)



# [2.0.0-beta.2](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.2.thiago.dev...v2.0.0-beta.2) (2025-05-19)


### Bug Fixes

* **adiantamento:** Bloquado geração de adiantamento de salário quando funcionário está inativo ([0a30604](https://github.com/gerenciar/gerenciar_autoescola/commit/0a30604dce085b008ee275336f8b46297bba308e)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **cadastro:** Componente de Alerta volta a ter a cor vermelha quando ativado ([0f7abc0](https://github.com/gerenciar/gerenciar_autoescola/commit/0f7abc0df61c1b8208ced449225dea436549d3cd)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **cadastro:** Corrigido cálculo da data de vencimento do exame médico ([ed66fe0](https://github.com/gerenciar/gerenciar_autoescola/commit/ed66fe0a3b9ac7a5e19ea1af0c7357f256411722)), closes [#1305](https://github.com/gerenciar/gerenciar_autoescola/issues/1305)
* **cadastro:** Corrigido envio de email e mensagem com login e senha do funcionario ao cadastrar ([14bd79e](https://github.com/gerenciar/gerenciar_autoescola/commit/14bd79ebf78c1c66185a2c2c159feaaed0c1ef86)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **consulta:** Remove alunos inativos dos resultados da consulta de alunos ([3b07c03](https://github.com/gerenciar/gerenciar_autoescola/commit/3b07c033214f9800a1d53f4da35d1295310ced19)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **relatorio:** Corrige filtro de data no relatório de aniversário ([6afa104](https://github.com/gerenciar/gerenciar_autoescola/commit/6afa104544fb6c676b345018a6409e4b3c291c1c)), closes [#565](https://github.com/gerenciar/gerenciar_autoescola/issues/565)
* **webhook:** Adicionado um commit logo após a inserção na tabela aud_fluxocaixa. ([4a8f619](https://github.com/gerenciar/gerenciar_autoescola/commit/4a8f6194dd6a560c880271b54da02805b5785993)), closes [#1054](https://github.com/gerenciar/gerenciar_autoescola/issues/1054)


### Features

* **consulta:** Adicionado aba de fornecedores na consulta de cadastros inativos ([1514b3e](https://github.com/gerenciar/gerenciar_autoescola/commit/1514b3e9766e90d3a04a4c0db9c6c156589ea7fe)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **contrato:** Adiciona index de naturalidade ([1204411](https://github.com/gerenciar/gerenciar_autoescola/commit/1204411e80497c717bd9316045c9228eeba0fad3)), closes [#1183](https://github.com/gerenciar/gerenciar_autoescola/issues/1183)
* **nav:** Adicionado o nome da empresa na barra de navegação superior ([fa851d1](https://github.com/gerenciar/gerenciar_autoescola/commit/fa851d1db07cfbc740972d7221e39fcc18ce0074))
* **vendas:** Adicionado bloqueio ao voltar venda para pendente se estiver cancelada ([32962da](https://github.com/gerenciar/gerenciar_autoescola/commit/32962da0ab814e7aaab862f79906e7f6ebb8c5d8)), closes [#1337](https://github.com/gerenciar/gerenciar_autoescola/issues/1337)



# [2.0.0-beta.1](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.1.thiago.dev...v2.0.0-beta.1) (2025-05-16)


### Bug Fixes

* **adiantamento:** Corrigida duplicação na consulta de adiantamento do funcionário ([14ef509](https://github.com/gerenciar/gerenciar_autoescola/commit/14ef509b20a374744836ca59b17af076baa9de67)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **cadastro:** Corrigida validação no cadastro de funcionários para impedir duplicidade no CPF ([d78edbe](https://github.com/gerenciar/gerenciar_autoescola/commit/d78edbe1ee168f65d4f4b467ab8a0d425fa5dd53)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)
* **caixa:** Campos de juros e multa agora atualizam de acordo com a parcela na aba de Entrada do Fechamento de Caixa ([70f2955](https://github.com/gerenciar/gerenciar_autoescola/commit/70f29557132853768fa1650fbdc3483049b954e0)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)



# [2.0.0-beta.0](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.0.tharc.dev...v2.0.0-beta.0) (2025-05-13)


* refactor(maker)!: Projeto Gerenciar Autoescola migrado do Maker Bootstrap para o Maker 5 ([6d4f528](https://github.com/gerenciar/gerenciar_autoescola/commit/6d4f5289b9b490a84817e97757ec6475a0c5f4e6))


### Bug Fixes

* **cadstro:** Corrigido tela de erro no Cadastro de Pacotes depois da migraçã ([3f3213b](https://github.com/gerenciar/gerenciar_autoescola/commit/3f3213bfa39a245f048920fd1911ee255db855ab))


### Features

* **login:** Adicionado acesso do aluno ao sistema ([acc5acf](https://github.com/gerenciar/gerenciar_autoescola/commit/acc5acf9cc169e2738741604aa507c30cc622f65))
* **mobile:** Versão do Maker 5 implementa novo app mobile ([2dbbd53](https://github.com/gerenciar/gerenciar_autoescola/commit/2dbbd539856ad1aaf089e1d5d2cee0716373ec1d)), closes [#1477](https://github.com/gerenciar/gerenciar_autoescola/issues/1477)


### BREAKING CHANGES

* O suporte ao Maker Bootstrap foi descontinuado em 14 de fevereiro de 2024, versão incompatível com Maker Bootstrap



