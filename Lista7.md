QUESTÃO 1

Aleatoriedades Estatísticas referem-se à capacidade de uma sequência de números parecer aleatória quando analisada estatisticamente. Isso significa que, ao aplicar testes estatísticos, a sequência não mostra padrões ou regularidades que possam ser identificados.

Imprevisibilidade, por outro lado, é sobre a dificuldade de prever ou antecipar o próximo valor em uma sequência. Mesmo que uma sequência pareça aleatória estatisticamente, se alguém conseguir prever o próximo valor, a sequência não é considerada imprevisível.
Aleatoriedades estatísticas focam na análise dos padrões de uma sequência, enquanto imprevisibilidade trata da dificuldade em prever futuros valores dessa sequência.

QUESTÃO 2

Ao projetar uma cifra de fluxo (stream cipher), algumas considerações importantes incluem:

Segurança da Chave: A chave deve ser suficientemente longa e mantida em segredo para evitar ataques.

Qualidade do Gerador de Sequência: O gerador de números pseudoaleatórios deve produzir uma sequência que seja estatisticamente indistinguível de uma sequência verdadeiramente aleatória.

Velocidade e Eficiência: A cifra deve ser rápida e eficiente em termos de processamento e uso de recursos.

Resistência a Ataques: Deve ser resistente a ataques conhecidos, como ataques de análise de frequência e ataques de recuperação de chave.

Facilidade de Implementação: A cifra deve ser fácil de implementar de forma segura e deve ter uma implementação prática que não introduza vulnerabilidades.

QUESTÃO 3

Não é desejável reutilizar uma chave de cifra de fluxo por alguns motivos:

Segurança Comprometida: Se a mesma chave é usada para cifrar diferentes mensagens, padrões podem ser descobertos. Isso pode permitir que um atacante use técnicas para encontrar a chave e decifrar as mensagens.

Risco de Ataques Conhecidos: Reutilizar chaves pode tornar o sistema vulnerável a ataques de análise de fluxo, onde o atacante pode usar informações de múltiplas mensagens cifradas com a mesma chave para descobrir a chave ou o conteúdo das mensagens.
Ou seja, Reutilizar uma chave de cifra de fluxo pode comprometer a segurança e facilitar a quebra da cifra.

QUESTÃO 4

O RC4, uma cifra de fluxo popular, utiliza operações primitivas como:

Trocas de Bytes: Troca os valores dos bytes dentro do estado interno (tabela S).

Permutações: Realiza uma permutação do estado interno com base na chave e no valor atual da tabela.

Substituição: Usa uma tabela de substituição para gerar uma sequência de chaves pseudoaleatórias que são combinadas com os dados para cifrar ou decifrar.
RC4 usa operações de troca e permutação de bytes para criar uma sequência de chave que é combinada com o texto claro para produzir o texto cifrado.

QUESTÃO 5

QUESTÃO 6

A) O período máximo é 8.

B)O valor de A deve ser coprimo com 16. Possíveis valores são a=1,3,5,7,9,11,13,15.

C)A semente 𝑋0 também deve ser coprima com 16, ou seja, 𝑋0 precisa ser um número ímpar:   X0 =1,3,5,7,9,11,13,15

QUESTÃO 7

Uma chave que deixa a matriz SSS inalterada (com os valores de 0 a 255 em ordem crescente) seria uma sequência de bytes de 0 a 255 na mesma ordem. Essa chave específica faz com que o processo de inicialização do RC4 não altere a ordem original de SSS.

QUESTÃO 8

A)p=563 e q=571, ambos primos e congruentes a 3 mod 4.

B)n = p×q = 563 × 571 = 321773

C) s=23, que é coprimo com 𝑛 = 321773.

D)x0 =(8²) mod n=(23²) mod 321773 = 529.

E)  xi=(x²i−1) mod n por 10 iterações.

x1 = (529)mod 321773 = 279841
x2 = (279841²) mod 321773 = 254028
𝑥3 = (254028²) mod 321773 = 109570
x4 = (109570²) mod 321773 = 210043
x5 = (210043²) mod 321773 = 72086
x6 ​= (72086²) mod 321773 = 27391
x7 =(27391²) mod 321773 = 253215
x8 = (253215²) mod321773 = 105774
x9 = (105774²) mod 321773 = 100581
x10 =(100581²) mod321773=319695 

A Sequência gerada foi:
529,279841,254028,109570,210043,72086,27391,253215,105774,100581,319695.







