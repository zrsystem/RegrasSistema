> Status : Em desenvolvimento ⚠ 

## Solicitação

+ Fazer uma nova tela de extrato onde apareça os 3 tipos de contas também corrigir os filtros do extrato, para que o cliente possa ver todos os tipos de contas em um lugar só sendo possível visualizar tudo que ele tem para pagar, recorrente e receber. o cliente poderá visualizar meses a frente marcando a situação correta em que quer ver a conta no caso de aguardando pagamento e aguardando recebimento.

# Regras de Negocio / Sistema  (extrato)

+ Mostrar os três tipos de contas no extrato sendo elas (receber,pagar,recorrente) ⏳ 
+ Ter um filtro na tela para habilitar um ou mais tipos de contas que será apresentado ⏳ 
+ Possibilidade de cadastrar contas ⏳ 
+ Possibilidade de dar baixa nas contas pagar e receber ⏳ 
+ Imprimir ou exportar o de acordo com o que apresenta na grid, tando em pdf quanto em arquivo csv ⏳ 
+ Possibilidade dar baixa em varias contas ao mesmo tempo pela grid do extrato ⏳ 
 
#### Regras Sistema (cadastro de contas)

+ Mostrar a data cadastro com a hora atual em que o cliente clicou para cadastrar a conta e não deixar que seja editada ✔
+ Somente sera exibido os campos 'valor pago', 'data pagamento' e 'conta bancaria' quando o checkbox de (Pago ?) estiver marcado ✔
+ Somente sera exibido os campos 'valor recebido', 'data recebimento' e 'conta bancaria' quando o checkbox de (Recebido ?) estiver marcado ✔
+ Somente quando a conta recorrente tiver a frequência 'personalizar' deve aparecer um campo 'dias' ✔
+ Fazer com que ao selecionar o campo 'tipo credor' em contas a pagar altere o input de acordo com o tipo credor selecionado ✔
+ Fazer com que ao selecionar o campo 'tipo operação' em contas a pagar receber o input de acordo com o tipo credor selecionado ✔
+ Criar um campo de Multa e juros que ja venham com um value presetado e que faça o calculo do valor total que o devedor deve pagar (o admin do sistema podera decidir se o campo será editado, por quem sera editado ou se  o valor ja vira padrão de acordo com as configurações) ✔
+ Adicionar em configurações do sistema juros e multa padrao de acordo com a forma de pagamento ✔
+ Verificação caso o desconto for maior que o valor total da conta não permitir salvar e exibira um alerta ⏳
+ Caso o valor pago da conta for menor que o valor total da mesma devera ser gerada uma outra conta com a diferença ⏳
+ Em formas de pagamento em ambos os tipos de contas (pagar, receber) possibilitar o parcelamento, fazendo assim com que o sistema gere o parcelamento dessas contas de acordo com o selecionado pelo cliente ⏳
+ Gerar recibo de pagamento ou recebimento ⏳
+ Ao dar recebimento em uma conta como forma de pagamento cheque ele tem que dar entrada em custodia de cheques ⏳

### Funcionalidades

+ Foi dado início  ao front-end da tela já com os filtros e tabela onde ficara todos os dados de contas a receber 
+ Botão opções onde temos as opções imprimir, planilha e cadastrar conta 

## Campos e Regras de campos

+ Check box 'Recebido ?' ou 'Pago ?' (devem aparecer de acordo com o radio escolhido) ✔
+ Data cadastro (ambos) (aparece em ambos os campos porem não permite edição) ✔
+ Data pagamento (pagar) (aparece somente na pagar, quando marcado o check box 'Pago ?') ✔
+ Data recebimento (receber) (aparece somente na pagar, quando marcado o check box 'Recebido ?') ✔
+ Frequência (recorrente) ✔
+ Dias (recorrente) (aparece somente quando o campo frequencia estiver com a opção (personalizado) selecionada) ✔
+ Tipo operação (receber) (aparece os campos de acordo com o que esta selecionado Cliente, Funcionario, Fornecedor, Outro ) ✔
+ Origem (receber) (tipo operação = transferencia) ✔
+ Destino (receber) (tipo operação = transferencia) ✔
+ Tipo de titulo (receber) ✔
+ Tipo credor (pagar) (aparece os campos de acordo com o que esta selecionado Cliente, Funcionario, Fornecedor, Outro ) ✔
+ Plano de contas (ambos) ✔
+ Valor total (ambos) ✔
+ Valor desconto (ambos) (aparece somente caso o 'Pago ?' ou 'Recebido?' esteja marcado ) ✔
+ Valor multa (ambos) ✔
+ Valor juros (ambos) ✔
+ Valor pago (pagar) ✔
+ Valor recebido (receber) ✔
+ Forma pagamento (ambos) ✔
+ Conta bancaria (ambos) ✔
+ N° do documento (ambos) ✔
+ N° nfe (receber) ✔ 
+ Historico (ambos) ✔
+ Situação (recorrente) ✔
+ código de barras  (ambos) ✔