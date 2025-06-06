# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.0.0-beta.7] (2025-06-06)


### Features

* **cadastro:** adiciona status ao lado do serviço em cadastro de pacotes ([3fb303d](https://github.com/gerenciar/gerenciar_autoescola/commit/3fb303debbdd02578ba747c0387c28d73cf5e4ca)), closes [#1498](https://github.com/gerenciar/gerenciar_autoescola/issues/1498)
* **cadastro:** evita que conta destino seja cadastrado em branco em formas de pagamento ([2a6f328](https://github.com/gerenciar/gerenciar_autoescola/commit/2a6f32802c862a10826d272d8693ca10747e165d)), closes [#1536](https://github.com/gerenciar/gerenciar_autoescola/issues/1536)
* **caixa:** centro de custos em saída filtra somente despesas ([52bfbc8](https://github.com/gerenciar/gerenciar_autoescola/commit/52bfbc878d7e9fd6e27626756639d4b30ef2b8f5)), closes [#1537](https://github.com/gerenciar/gerenciar_autoescola/issues/1537)
* **relatório:** adiciona campo de observação em aulas - matricial ([1aefde4](https://github.com/gerenciar/gerenciar_autoescola/commit/1aefde45adcbcc0333b868f0fb7a3c82d6dbc5a1)), closes [#1379](https://github.com/gerenciar/gerenciar_autoescola/issues/1379)


### Bug Fixes

* **agenda:** corrige campo de status na impressão dos relatórios pra condizer com o calendário ([c1d1d5c](https://github.com/gerenciar/gerenciar_autoescola/commit/c1d1d5cb7ad9ae9a47c068515facc0dab1c9bc31)), closes [#1163](https://github.com/gerenciar/gerenciar_autoescola/issues/1163)
* **cadastro:** corrige cadastro de autoescolas não afetando o banco de dados ([49e69f5](https://github.com/gerenciar/gerenciar_autoescola/commit/49e69f52920ae0620d86458318587bee642458aa)), closes [#1508](https://github.com/gerenciar/gerenciar_autoescola/issues/1508)
* **caixa:** evita que caixa seja duplicado por clicar várias vezes em inserir caixa ([fe344a6](https://github.com/gerenciar/gerenciar_autoescola/commit/fe344a6c15bb9ab7517742a8b66f8b44de4e11a8)), closes [#1532](https://github.com/gerenciar/gerenciar_autoescola/issues/1532)
* **exames:** Corrigido filtro de status para o exame de renovação ([ca43517](https://github.com/gerenciar/gerenciar_autoescola/commit/ca435173f6198faaff8b68934de33e18401012de)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)
* **login:** Recupera aviso de empresa bloqueada para admin ao logar ([6e921eb](https://github.com/gerenciar/gerenciar_autoescola/commit/6e921eb1a14a24a35b63a80ed2712f8ab95d3444)), closes [#1180](https://github.com/gerenciar/gerenciar_autoescola/issues/1180)

## [2.0.0-beta.6] (2025-06-03)


### Features

* **cadastro:** adiciona status ao lado do serviço em cadastro de pacotes ([76bc59b](https://github.com/gerenciar/gerenciar_autoescola/commit/76bc59bf49da84455c4a850b192c0052e81dada4)), closes [#1498](https://github.com/gerenciar/gerenciar_autoescola/issues/1498)


### Bug Fixes

* **agenda:** corrige campo de status na impressão dos relatórios pra condizer com o calendário ([e90f33b](https://github.com/gerenciar/gerenciar_autoescola/commit/e90f33b3bec5c3fecbb2b8dc928cd7e38875aca4)), closes [#1163](https://github.com/gerenciar/gerenciar_autoescola/issues/1163)
* **cadastro:** corrige cadastro de autoescolas não afetando o banco de dados ([651a274](https://github.com/gerenciar/gerenciar_autoescola/commit/651a274b6fde433f0df6df99fbd6165b366cb7ad)), closes [#1508](https://github.com/gerenciar/gerenciar_autoescola/issues/1508)
* **caixa:** evita que caixa seja duplicado por clicar várias vezes em inserir caixa ([984ce02](https://github.com/gerenciar/gerenciar_autoescola/commit/984ce0253d0aa2203be5ca114b3efe900f26eb1a)), closes [#1532](https://github.com/gerenciar/gerenciar_autoescola/issues/1532)
* **catraca:** Corrigida exportação da catraca para aparecer o nome da empresa ([6283e86](https://github.com/gerenciar/gerenciar_autoescola/commit/6283e869b0e1639da2fa2331b159b3caa8f6f6b2))
* **exames:** Corrigido filtro de status para o exame de renovação ([704a129](https://github.com/gerenciar/gerenciar_autoescola/commit/704a129943a7bb52f5b6b7b4461fa94236f14e2e)), closes [#1181](https://github.com/gerenciar/gerenciar_autoescola/issues/1181)
* **login:** Recupera aviso de empresa bloqueada para admin ao logar ([313a683](https://github.com/gerenciar/gerenciar_autoescola/commit/313a683149b42d6539a688d9a0faad59669503dc)), closes [#1180](https://github.com/gerenciar/gerenciar_autoescola/issues/1180)

# [2.0.0-beta.4] (2025-05-26)


### Bug Fixes

* **relatorio:** Corrige impressão de nomes vazios na agenda 74528e1, closes #1318
* **vendas:** Corrigido o tipo de exame aplicado ao item ao realizar venda 57ab7ef, closes #1181


### Features

* **adiantamento:** Adicionado status ao lado do nome no filtro de funcionário 976dd90, closes #1479
* **cadastro:** Torna campos obrigatórios no cadastro do aluno na aba de cadastro e endereço para CFC Máxima 31a5c2c, closes #1375
* **cadastro:** Torna início, vencimento e alerto do processo obrigatórios para CFC Método 4971d66, closes #1303
* **relatorio:** adiciona filtro de aluno no relatório de exames e resultados 6fd80c7, closes #1181



# [2.0.0-beta.3] (2025-05-26)


### Bug Fixes

* **exames:** Corrigido filtro de exame na tela de exames e resultados dd6c4c6, closes #1181


### Features

* **recibo:** Adicionado campo de data de nascimento nos modelos 1 e 2 e assinatura do aluno no modelo 1 f832cdf, closes #1179 #1285
* **relatorio:** Concatenado o CPF do aluno ao lado do nome na impressão da agenda 5dcbbd6, closes #1308



# [2.0.0-beta.2] (2025-05-26)


### Bug Fixes

* **adiantamento:** Bloquado geração de adiantamento de salário quando funcionário está inativo 0a30604, closes #1477
* **cadastro:** Componente de Alerta volta a ter a cor vermelha quando ativado 0f7abc0, closes #1477
* **cadastro:** Corrigido cálculo da data de vencimento do exame médico ed66fe0, closes #1305
* **cadastro:** Corrigido envio de email e mensagem com login e senha do funcionario ao cadastrar 14bd79e, closes #1477
* **consulta:** Remove alunos inativos dos resultados da consulta de alunos 3b07c03, closes #1477
* **relatorio:** Corrige filtro de data no relatório de aniversário 6afa104, closes #565
* **webhook:** Adicionado um commit logo após a inserção na tabela aud_fluxocaixa. 4a8f619, closes #1054


### Features

* **consulta:** Adicionado aba de fornecedores na consulta de cadastros inativos 1514b3e, closes #1477
* **contrato:** Adiciona index de naturalidade 1204411, closes #1183
* **nav:** Adicionado o nome da empresa na barra de navegação superior fa851d1
* **vendas:** Adicionado bloqueio ao voltar venda para pendente se estiver cancelada 32962da, closes #1337



# [2.0.0-beta.1](2025-05-26)


### Bug Fixes

* **adiantamento:** Corrigida duplicação na consulta de adiantamento do funcionário 14ef509, closes #1477
* **cadastro:** Corrigida validação no cadastro de funcionários para impedir duplicidade no CPF d78edbe, closes #1477
* **caixa:** Campos de juros e multa agora atualizam de acordo com a parcela na aba de Entrada do Fechamento de Caixa 70f2955, closes #1477



# [2.0.0-beta.0] (2025-05-26)


### Bug Fixes

* **cadstro:** Corrigido tela de erro no Cadastro de Pacotes depois da migraçã 3f3213b


### Features

* **login:** Adicionado acesso do aluno ao sistema acc5acf
* **mobile:** Versão do Maker 5 implementa novo app mobile 2dbbd53, closes #1477


### BREAKING CHANGES

* O suporte ao Maker Bootstrap foi descontinuado em 14 de fevereiro de 2024, versão incompatível com Maker Bootstrap



