# ArvoresBinariaAvl
Gabriel Yuichi Suzaki, Ciência da Computação, 4 periodo
# Comparação entre as arvores binaria e AVL
  O projeto consiste em duas arvores diferentes resolvendo uma mesma sequencia numerica, sem repetições por fins de evitar problemas na remoção ou adição, a maquina utilizada no projeto tem um processador 11th Gen Intel(R) Core(TM) i5-1135G7 @ 2.40GHz   2.42 GHz e 8,00 GB de RAM. São realizados três ações, criação/inserção, remoção e busca, como os resultados apontam o tempo de execução em milissegundos, serão realizadas todas as três ações de uma vez, assim será possivel ver qual é mais eficiente ou mais rapida (nota: não foi possivel realizar testes com mais de 10000, a ferramenta inteliJ não suportou.):
  # primeiro teste - 100 elementos:
  Arvore Binaria - criação -> 16 milissegundos - busca -> 1 milissegundo - remoção -> 0 milissegundo
  Arvore AVL - criação -> 27 milissegundos - busca -> 0 milissegundo - remoção -> 0 milissegundo
   # segundo teste - 500 elementos:
  Arvore Binaria - criação -> 122 milissegundos - busca -> 1 milissegundo - remoção -> 0 milissegundo
  Arvore AVL - criação -> 162 milissegundos - busca -> 0 milissegundo - remoção -> 0 milissegundo
   # terceiro teste - 5000 elementos:
  Arvore Binaria - criação -> 100 milissegundos - busca -> 2 milissegundo - remoção -> 1 milissegundo
  Arvore AVL - criação -> 331 milissegundos - busca -> 0 milissegundo - remoção -> 0 milissegundo

  # Respostas das perguntas:
  1)- Qual funciona melhor?
  R - A AVL parece ser melhor para consultar e remover, já a binaria é mais rapida para criar, agora depende do objetivo do programador, se é necessário criar muitas arvores em sequencia, a binaria é melhor, mas se o objetivo é consultar e lidar com as arvores, a AVL é a melhor. 
  
  2)- Criticas sobre as arvores
  R - Honestamente, a mais simples de criar é a binaria, porém ela vai perder tempo ao fazer buscas ou remoções, por conta de somente seguir a regra de esquerda e direita, mas é claro que a AVL acaba sendo a melhor no geral, por mais complicado que seja o codigo para rotacionar e comparar alturas, ela acaba ganhando tempo na parte de busca e remoção,por conta de solucionar desbalanços na arvore, deixando a arvore com menos niveis, isso na minha opinião a torna melhor e compensa pelo tempo da criação. Mas em situações onde não são muito grandes, como nos testes, fica um pouco dificil dizer se alguma é muito melhor que outra.
