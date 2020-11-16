# pix-qrcode
Função em JavaScript para criação do QrCode (com valor) do PIX.

Como usar:

Basta copiar a função no seu código e fornecer os seguintes dados:

merchant_account:    Chave PIX
merchant_name:       Titular da Conta
merchant_city:       Cidade do Titular
transaction_amount:  Valor da Transação

O retorno da função é string para geração do QrCode. Basta aplicar essa string em uma lib de geração de QrCode.

Exemplo:
>node qrCodePix.js

Saída:
Payload: 00020126580014br.gov.bcb.pix0136e91e0334-2b7d-41ec-89b8-65d1270869255204000053039865406123.455802BR5913FULANO DE TAL6007VITORIA62070503\*\*\*6304                                     
CRC: 176E                                                                                                                                                                                   
QrCode: 00020126580014br.gov.bcb.pix0136e91e0334-2b7d-41ec-89b8-65d1270869255204000053039865406123.455802BR5913FULANO DE TAL6007VITORIA62070503\*\*\*6304176E