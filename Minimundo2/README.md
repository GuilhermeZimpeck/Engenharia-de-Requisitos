<table>
  <tr>
    <td>
      
  <strong> Minimundo 2 – Delicatessen Tudo de Bom </strong>
      
      
  A delicatessen Tudo de Bom conta atualmente com 15 funcionários sendo que 80% destes atuam na sua loja. O aumento das vendas e o medo de perder o controle fizeram com que a direção da delicatessen lhe solicitasse o desenvolvimento de um sistema.
  
  Para evitar que mudanças constantes nos requisitos venham a prejudicar o andamento do projeto, o framework Scrum deve ser utilizado. O prazo máximo para entrega do produto é de 4 meses.
  
  A delicatessen trabalha com vendas no balcão, que devem ser registradas pelo atendente. Da venda é preciso conhecer a data e hora em que ela ocorreu, os produtos que foram vendidos, e qual atendente a registrou. O sistema deverá integrar-se com leitores de código de barras para identificação dos produtos.  O sistema deverá registrar uma venda em até 2 segundos, considerando até 20 produtos por venda, em condições normais de operação.
  
  Os produtos que podem ser comercializados têm o seu cadastro mantido pelo gerente de compras e deles deve-se conhecer: o nome, a quantidade no estoque, a quantidade mínima que deve ter no estoque e se ele é fabricado pela delicatessen ou comprado. Para os produtos fabricados o cozinheiro chefe deverá informar a sua composição (os ingredientes com suas respectivas quantidades). 
  
  O coziheiro chefe também é responsável por manter atualizado o cadastro de ingredientes necessários à fabricação dos produtos. Neste cadastro, basta que ele informe o nome do ingrediente e a sua quantidade no estoque.
  
  Cada produto tem um valor de venda que deve ser atualizado, sempre que necessário, pelo gerente de vendas. 	
  
  O estoquista, sempre que recebe os produtos comprados ou os ingredientes para a fabricação dos produtos na delicatessen, deve registrar a entrada de itens no estoque.
  
  Cada vez que o cozinheiro chefe necessita de ingredientes para a fabricação de produtos ele registra um pedido, o que implica no envio de uma notificação para o estoquista. O pedido deve conter a data e hora em que foi realizado e a quantidade de cada ingrediente necessário.
 
  O estoquista, por sua vez, quando separa os ingredientes para atender ao cozinheiro chefe, registra a data e hora da entrega do pedido, o que gera a baixa no estoque (data e quantidade entregue). A entrega de ingredientes pode não corresponder ao total de ingredientes solicitados, fazendo com que novas entregas possam ocorrer.
  
  Não é responsabilidade do sistema controlar os pedidos de compra dos ingredientes para fabricação dos produtos, nem dos demais produtos.
  
  Dos atendentes é preciso conhecer: nome, CPF, endereço, telefone, e-Mail e data de nascimento. A manutenção desse cadastro é de responsabilidade do gerente geral.
  
  Sempre que solicitado pelo estoquista o sistema deve fornecer a quantidade de ingredientes entregues ao cozinheiro chefe em determinado período.
  
  Sempre que solicitado por qualquer gerente o sistema deverá lhe fornecer:
  
  - Os “n” produtos mais comprados pelos clientes da delicatessen, em um determinado período.
  
  - O valor das vendas, por produto, em determinado período.
  
  - As vendas realizadas por um atendente.
  
  Qualquer relatório emitido pelo sistema deve ser liberado para o usuário em, no máximo 30 segundos, após a solicitação.	
 
  O sistema deverá realizar backup automático do banco de dados diariamente e permitir a restauração completa dos dados em até 30 minutos.
    </td>
  </tr>
</table>
