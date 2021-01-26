# Canal Dstak Desafio Mobile

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento em UI / UX
- Conhecimento técnico em desenvolvimento Web usando React JS
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Criar um ambiente de desenvolvimento em React JS
- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Inicialmente a aplicação precisará de 2 telas simples. Uma que exiba uma lista de pedidos que estão pendentes de determinada ação. Uma outra que traga mais detalhes de um pedido escolhido.

Toda chamada ao backend deverá ser "mockada".

### Requisitos

* Básicos
  * A aplicação deverá ser em React JS
  * Simplificar o que deve ser feito mantendo qualidade
  * Uso de biblioteca de componentes estilizados
  * A UI deve ser coesa em seus estilos como tamanho de fontes e espaçamentos
  * Padrão de commits com Conventional Commits
  * Commits atômicos
  * Documentação do que você fez e das suas motivações no README
* Na listagem de pedidos será necessário:
  * uma lista com as seguintes colunas: data, codigo do pedido, nome do comprador, cidade/estado de entrega, valor, forma de pagamento e status.
  * ordernar por data, de forma crescente
  * colorir o fundo de cada linha de acordo com o status do pedido (aguardando pagamento, pago, preparando, enviado, entregue)
  * a lista de pedido precisa ser paginada
* Na tela de detalhes do produto
  * Exibir os detalhes do pedido. Além dos campos informado na lista, adicionar: itens (lista), anexos (exibir lista de documentos anexados)
  * Um botão para fechar a tela (não precisa permitir edição)

* Você se destacará ainda mais se fizer algum desses pontos:
  * Uso de componentes Material Design
  * Configuração/uso de lint
  * Aplicar conhecimentos de UI/UX
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes com Jest
  * Tratativas de Erro com feedback para o usuário

### Avaliação

* **50%**: Básico
* **30%**: Tela de listagem
* **20%**: Tela de detalhe
