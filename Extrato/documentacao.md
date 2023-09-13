> Status : Em desenvolvimento ⚠

## Solicitação

+ Fazer uma nova tela de extrato onde apareça os 3 tipos de contas também corrigir os filtros do extrato, para que o cliente possa ver todos os tipos de contas em um lugar só sendo possível visualizar tudo que ele tem para pagar, recorrente e receber. o cliente poderá visualizar meses a frente marcando a situação correta em que quer ver a conta no caso de aguardando pagamento e aguardando recebimento.

# Regras Sistema (extrato)

+ Mostrar os três tipos de contas no extrato sendo elas (receber,pagar,recorrente)
+ Ter um filtro na tela para habilitar um ou mais tipos de contas que será apresentado
+ Possibilidade de cadastrar contas

#### Regras Sistema (cadastro de contas)

+ Mostrar a data cadastro com a hora atual em que o cliente clicou para cadastrar a conta e não deixar que seja editada ✔
+ Somente sera exibido os campos 'valor pago', 'data pagamento' e 'conta bancaria' quando o checkbox de (Pago ?) estiver marcado ✔
+ Somente sera exibido os campos 'valor recebido', 'data recebimento' e 'conta bancaria' quando o checkbox de (Recebido ?) estiver marcado ✔
+ Somente quando a conta recorrente tiver a frequência 'personalizar' deve aparecer um campo 'dias' ✔
+ Fazer com que ao selecionar o campo 'tipo credor' em contas a pagar altere o input de acordo com o tipo credor selecionado
+ Fazer com que ao selecionar o campo 'tipo operação' em contas a pagar receber o input de acordo com o tipo credor selecionado
+ Criar um campo de Multa e juros que ja venham com um value presetado e que faça o calculo do valor total que o devedor deve pagar (o admin do sistema podera decidir se o campo será editado, por quem sera editado ou se  o valor ja vira padrão de acordo com as configurações) 
+ Adicionar em configurações do sistema juros e multa padrao de acordo com a forma de pagamento


### Funcionalidades

+ Foi dado início  ao front-end da tela já com os filtros e tabela onde ficara todos os dados de contas a receber 
+ Botão opções onde temos as opções imprimir, planilha e cadastrar conta 
