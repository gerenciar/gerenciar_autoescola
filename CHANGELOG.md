# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.0.0-beta.6](https://github.com/gerenciar/gerenciar_autoescola/compare/v2.0.0-beta.5.allan.dev...v2.0.0-beta.6) (2025-06-05)


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



