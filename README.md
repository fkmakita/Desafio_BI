# Desafio BI
### Parte 1 - Diagrama do DataMart
O diagrama foi desenvolvido dentro do próprio Power BI, através de dados randomizados ([Sheets com os dados](https://docs.google.com/spreadsheets/d/1xrO9IwalCOP1evJECOiUgnHjmXuHg7_F3qWzvKWseBM/edit?usp=sharing)) para visualização do Dashboard na Parte 2.<br><br>
O diagrama se baseia em 3 blocos principais: ifood (em vermelho), Rappi (em laranja) e Delivery Próprio (em verde).<br>
Cada bloco é composto por uma tabela de Vendas (fato), Carrinho (dimensão), Clientes (dimensão) e Status pedido (dimensão em comum com os 3 blocos).<br>
Por fim, a integração dos 3 sistemas é realizada na tabela '_Vendas Geral'.<br>
![ifood](https://user-images.githubusercontent.com/86500603/236711378-d0671b12-2ae8-4227-811e-60730f416e0b.png)

### Parte 2 -  Mockup do Dashboard
O Mockup foi também desenvolvido dentro do próprio Power BI, através de dados randomizados para simular o funcionamento e distribuição dos dados dentro do Dashboard. Os principais pontos a serem atendidos são: visualizar o volume de pedidos por dia, visualizar o  volume de pedidos com erro e visualizar os valores dos pedidos processados.<br><br>
Com isso em mente, trouxe em 4 cards (Big Numbers) as informações de volume/receita processada e processamentos com erro. O usuário do Dashboard pode alterar o intervalo de visualização dos dados através dos filtros na lateral esquerda, assim como alterar o originador que deseja visualizar (ou a combinação deles).<br>
Em seguida, trouxe a visualização em colunas empilhadas, onde o usuário pode visualizar a evolução das vendas/receita e consegue também com facilidade visualizar pontualmente os dias em que houve algum erro no processamento.<br>
Por fim, trouxe alguns agrupamentos em gráficos de rosca, auxiliando a visualização do percentual que o erro representa no total de pedidos. Além disso, também é possível visualizar a proporção da origem dos erros (neste exemplo a plataforma do ifood é a que menos errou, tanto em volume quanto em percentual de receita).<br>
![Mockup Go2Go_pages-to-jpg-0001](https://user-images.githubusercontent.com/86500603/236712268-a56f41f4-db03-4740-bcc5-7ecf6996098a.jpg)
Pensando em pontos de melhoria, poderiam ser criadas abas específicas para cada um dos originadores, assim detalhando cada um deles e permitindo uma melhor rastreabilidade dos erros, assim como dos clientes que foram afetados.
