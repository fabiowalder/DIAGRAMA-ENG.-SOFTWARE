[Cliente] ----> (Cadastrar-se / Fazer login)
[Cliente] ----> (Pesquisar restaurante/prato)
[Cliente] ----> (Fazer pedido) <<include>> (Escolher forma de pagamento)
[Cliente] ----> (Acompanhar entrega)
[Cliente] ----> (Receber pedido)

[Restaurante] ----> (Gerenciar cardápio)
[Restaurante] ----> (Receber pedido)

[Entregador] ----> (Aceitar entrega)
[Entregador] ----> (Entregar pedido)

(Sistema de Pagamento) <---- (Escolher forma de pagamento)

Relacionamentos:
(Fazer login) <<extend>> (Recuperar senha)
