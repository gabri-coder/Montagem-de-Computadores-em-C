Sistema de Montagem de Computadores com Pilha
1. Introdução
Este projeto tem como objetivo desenvolver um Sistema de Montagem de Computadores, utilizando a estrutura de dados Pilha. O sistema será responsável por simular o processo de montagem de um computador, onde os componentes são adicionados ou removidos de forma sequencial. O sistema oferece uma interface simples para que o usuário possa inserir componentes (como placa-mãe, processador, memória RAM, etc.), removê-los ou visualizar a lista de componentes atualmente selecionados.

2. Documentação das Funcionalidades
O que o sistema faz?
O Sistema de Montagem de Computadores permite ao usuário gerenciar a montagem de um computador de acordo com a ordem em que os componentes são inseridos na pilha. O sistema oferece funcionalidades para adicionar, remover e listar componentes, facilitando o acompanhamento da montagem. A pilha é utilizada para simular a ordem de montagem, onde o último componente adicionado é o primeiro a ser removido.

Menu de Opções
Ao executar o sistema, o usuário será apresentado a um menu com as seguintes opções:

Adicionar componente - Permite que o usuário insira um componente na pilha.
Remover componente - Remove o componente mais recentemente adicionado (topo da pilha).
Listar componentes - Exibe todos os componentes da pilha, do topo para a base.
Sair - Encerra o programa.
Explicação de cada funcionalidade:
1. Adicionar componente
Função: adicionarComponente()
O usuário fornece o nome do componente (por exemplo, "placa-mãe", "processador", "memória RAM") e o componente é adicionado ao topo da pilha.
Esta operação não salva os componentes em arquivo, sendo mantida apenas em memória até o programa ser encerrado.
2. Remover componente
Função: removerComponente()
O componente no topo da pilha é removido. O sistema informa qual componente foi removido.
Caso a pilha esteja vazia, o sistema informa que não há componentes para remover.
3. Listar componentes
Função: listarComponentes()
Exibe todos os componentes presentes na pilha, do topo para a base, em ordem de inserção.
Nenhum dado é alterado na pilha ao listar os componentes.
4. Sair
Função: sair()
Encerra o sistema e libera os recursos utilizados.
3. Conclusão
Considerações Finais
O Sistema de Montagem de Computadores desenvolvido é uma aplicação simples e eficaz que utiliza a estrutura de dados pilha para simular a montagem de um computador. O uso de pilha permite simular o processo de empilhamento de componentes durante a montagem e removê-los na ordem inversa (último componente a ser adicionado é o primeiro a ser removido).

Melhorias Futuras:
Persistência de Dados: Implementar a capacidade de salvar os componentes em um arquivo, para que o estado da montagem seja mantido entre diferentes execuções do programa.
Interface Gráfica: Criar uma interface gráfica para tornar o processo de montagem mais intuitivo.
Validação de Componentes: Implementar validações para garantir que os componentes inseridos sejam compatíveis entre si (por exemplo, verificar se a placa-mãe e o processador são compatíveis).
Banco de Dados de Componentes: Utilizar um banco de dados para armazenar informações sobre os componentes (preço, especificações técnicas, etc.), permitindo que o usuário monte computadores mais facilmente com base em um catálogo de peças
