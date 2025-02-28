
### Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;



## Ferramentas utilizadas

- [MySQL Workbench](https://www.mysql.com/products/workbench/)



## Respostas do Desafio

![img](https://github.com/htonioni/mysql-projeto-conceitual-bd-DIO/blob/main/ECOMMERCE/ecommerce_imagem.png)

- Para a entidade Cliente foram criadas duas novas entidades  ``PJ_Pessoa Juridica`` e ``PF_Pessoa Fisica`` contendo as informações de CNPJ e CPF.
- No caso de Pagamento a entidade esta atribuída a outras duas entidades afim de detalhar as formas de pagamento : Cartão e Boleto.
- Entrega foi criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.



## Certificado

![img](https://github.com/htonioni/mysql-projeto-conceitual-bd-DIO/blob/main/certificado/certificado.jpg)

