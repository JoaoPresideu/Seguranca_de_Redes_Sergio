QUESTÃO 1

Encriptação tripla, ou 3DES, é uma técnica que aplica o algoritmo DES três vezes para reforçar a segurança. Em vez de usar DES uma única vez, como no método padrão, o 3DES faz isso três vezes, o que torna a cifra mais difícil de quebrar.

QUESTÃO 2

O ataque meet-in-the-middle é uma técnica que tenta reduzir o tempo necessário para quebrar uma cifra. O atacante realiza operações de encriptação e decriptação em paralelo e tenta encontrar um ponto comum que ajude a resolver o problema mais rapidamente.

QUESTÃO 3

Na encriptação tripla (3DES), são usadas três chaves:

Três chaves diferentes (K1, K2, K3): Cada chave é distinta, oferecendo o máximo de segurança. O algoritmo aplica a primeira chave para encriptar, a segunda para decriptar, e a terceira para encriptar novamente.

Duas chaves diferentes (K1, K2, K1): Aqui , K1 é usada tanto na primeira quanto na terceira etapa, enquanto K2 é usada no meio. Isso ainda oferece uma boa segurança, mas com um pouco menos de complexidade.

Uma única chave (K1, K1, K1): Isso faz com que o 3DES funcione como o DES original, sem adicionar segurança extra, apenas compatibilidade.

QUESTÃO 4

No 3DES, usamos Encriptação - Decriptação - Encriptação (EDE) para garantir que o processo seja eficaz e seguro. A decriptação no meio ajuda a criar uma cifra que é mais difícil de quebrar, tornando o 3DES mais resistente contra ataques.

QUESTÃO 5

Alguns modos de operação de cifra de bloco, como CTR (Counter) e OFB (Output Feedback), usam apenas a encriptação porque geram um fluxo de bits que é independente do texto claro. Esse fluxo é combinado com o texto claro usando uma operação simples, como XOR, para encriptar e decriptar. Como a operação é simétrica, a mesma encriptação pode ser usada para ambos os processos.

Por outro lado, modos como CBC (Cipher Block Chaining) usam tanto encriptação quanto decriptação porque o processo de decriptar um bloco depende da encriptação do bloco anterior. Ou seja, você precisa das duas operações para transformar os blocos de forma segura e recuperar o texto original.

QUESTÃO 6



QUESTÃO 7


