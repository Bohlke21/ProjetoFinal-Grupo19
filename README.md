# ProjetoFinal-Grupo19

Esta pasta contém o código de um sistema orientado a objetos em Java para quiosques de autoatendimento, utilizando o framework JavaFX.

O projeto, realizado no segundo semestre da disciplina de Programação I, do Professor Rodrigo Goulart, curso de Sistemas de Informação da Feevale, busca reproduzir o funcionamento de um totem de autoatendimento de estabelecimentos, neste caso de um restaurante, apresentando funcionalidades para o cliente e para o estabelecimento. As funções presentes para o cliente são: visualizar opções de interação, adicionar e remover itens, visualizar o resumo da interação e confirmar o processo. As funções presentes para o estabelecimento são: gerar um número de atendimento único, armazenar os atendimentos em uma lista de atendimentos realizados, permitir o acompanhamento do status do pedido e atualizar este mesmo status conforme o andamento (quando for necessário).

Para realizar um teste e execução do programa, você deve abrir a classe App e "rodá-la". Ao fazer isso, a tela do sistema abrirá e você poderá interagir com as funcionalidades.

# :hammer: Funcionalidades
- `Funcionalidade 1`: Para adicionar produtos para o carrinho você deve clicar no botão "Adicionar ao Carrinho" localizado abaixo da imagem do item de sua escolha.
- `Funcionalidade 2`: Para remover produtos do carrinho, você deve clicar no botão "-" presente ao lado do de "Adicionar ao Carrinho" do item de sua escolha.
- `Funcionalidade 3`: Os produtos adicionados irão aparecer na "Lista de Itens" (retângulo branco) ao lado das opções de produtos, aparecendo, além dos produtos o valor total do pedido.
- `Funcionalidade 4`: Para limpar a lista de produtos, clique no botão "Limpar Lista" localizado logo abaixo da "Lista de Itens". Isso fará com que os produtos escolhidos sejam excluídos.
- `Funcionalidade 5`: Para confirmar o pedido, clique no botão "Confirmar" localizado logo abaixo da "Lista de Itens". Ao confirmar, aparecerá na lista, além dos produtos e valor total, o número único e status do pedido. Essa lista irá aparecer também para o "Estabelecimento" (retângulo branco) localizado à direita da "Lista de Itens".
- `Funcionalidade 6`: Para mudar o status do pedido de "Em Preparo" para pronto ou entregue, clique no botão "Pronto", localizado abaixo do "Estabelecimento", para mudar o status do pedido para pronto. Clique no botão "Entregue", localizado abaixo do "Estabelecimento", para mudar o status do pedido para entregue.
