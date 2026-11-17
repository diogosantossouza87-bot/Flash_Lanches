# Flash Lanches – Delivery

Site de delivery para lanchonete, feito com HTML5, CSS3 e JavaScript puro (sem dependências).

## Funcionalidades
- Catálogo por categorias (Lanches, Acompanhamentos, Bebidas)
- Carrinho lateral com subtotal, taxa de entrega e total em tempo real
- Pagamento adiantado obrigatório (PIX, crédito ou débito). Não há pagamento na entrega
- Dados de entrega, número do pedido, previsão e resumo via WhatsApp
- Layout responsivo, focado em celular, com modo escuro automático

## Como rodar
Abra o `index.html` no navegador. Não precisa de build nem de servidor.

## Configuração
No início do `script.js`, edite o objeto `CONFIG`:
- `whatsapp`: número da lanchonete (DDI + DDD + número, só dígitos)
- `pix`: código PIX copia-e-cola
- `fee` e `freeFrom`: taxa de entrega e valor para frete grátis

## Aviso
O pagamento é simulado (a função `processPayment()` só aguarda 1,8 s). Para cobrar de verdade, integre um gateway e confirme o pagamento no servidor.
