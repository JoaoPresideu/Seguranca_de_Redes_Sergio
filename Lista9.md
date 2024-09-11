QUESTÃO 1

Chave Pública: Chave que qualquer pessoa pode usar para criptografar dados ou verificar assinaturas. Ela é distribuída amplamente.

Chave Privada: Chave que só o proprietário conhece e usa para descriptografar dados ou criar assinaturas. Deve ser mantida em segredo.

Algoritmo de Criptografia: Conjunto de regras matemáticas usadas para criptografar e descriptografar dados. Exemplos incluem RSA e ECC.

Assinatura Digital: Método para garantir que uma mensagem não foi alterada e foi realmente enviada pelo proprietário da chave privada.

QUESTÃO 2

Chave Pública:
Uso: Para criptografar mensagens e verificar assinaturas.
Exemplo: Maria usa a chave pública de João para criptografar uma mensagem. Somente João pode descriptografar a mensagem com sua chave privada.

Chave Privada:
Uso: Para descriptografar mensagens recebidas e assinar digitalmente documentos.
Exemplo: João usa sua chave privada para descriptografar uma mensagem que Maria enviou usando a chave pública dele. João também usa sua chave privada para assinar digitalmente um documento.

QUESTÃO 3

Garantir Confidencialidade: Apenas o destinatário com a chave privada correspondente deve conseguir ler a mensagem criptografada.

Assegurar Integridade: A mensagem não deve ser alterada durante a transmissão. Assinaturas digitais ajudam a garantir que a mensagem permaneceu intacta.

Prover Autenticidade: O destinatário deve poder verificar que a mensagem realmente veio do remetente esperado.

Permitir Não Repúdio: O remetente não deve ser capaz de negar ter enviado a mensagem. A assinatura digital ajuda a garantir que o remetente não possa negar a autoria.

Ser Resiliente a Ataques: O sistema deve ser resistente a tentativas de quebra de segurança, como ataques de força bruta.

QUESTÃO 4


Para escolher um número primo de forma eficiente, siga estes passos:

Perimeiro escolha um Número Aleatório: Selecione um número aleatório no intervalo que preferir.
Teste de Divisibilidade: Verifique se o número é divisível por números menores (geralmente até a raiz quadrada do número). Se não for divisível por nenhum deles, é um candidato a primo.
Algoritmo de Teste de Primalidade: Use um teste de primalidade eficiente, como o Teste de Miller-Rabin, para confirmar se o número é primo. Esse teste é mais eficiente para números grandes e reduz a probabilidade de erro.
Confirmação: Verifique o número novamente para garantir que não há falhas no teste de primalidade.

QUESTÃO 5 

A) X

B) X

QUESTÃO 6

A)Calculando n: n=3×11=33
Calcular φ(n):  φ(n)=(3−1)×(11−1)=2×10=20              //  p é φ
Verificando: mdc(e, φ(n)) = 1:
mdc(7, 20) = 1 (válido).
Calculando D: d=3(pois 7×3≡1mod20)
Encriptação (C):
C = M_e  mod n = 5_7 mod 33 = 78125 mod 33 = 14
Decriptação (M): M = C_d mod n = 14³  mod 33 = 2744 mod 33 = 5
M = 5.

B)n = 5 × 11 = 55
φ(n) = (5−1) × (11−1) = 4 × 10 = 40
mdc(3, 40) = 1 (válido).
d = 27 (pois 3 × 27 ≡ 1 mod 40)
C = M_e mod n = 9³ mod 55 = 729 mod 55 = 14
M = 9.

C)n = 7 × 11 = 77
φ(n) = (7−1) × (11−1) = 6 × 10 = 60
mdc(17, 60) = 1 (válido).
d = 53 (pois 17 ×5 3 ≡ 1 mod 60)
C = M_e mod n = 8_17 mod 77 = 57
M = C_d mod n = 57_53 mod 77 = 8
M = 8.

D) n = 11 × 13 = 143
φ(n) = (11−1) × (13−1) = 10 × 12 = 120
mdc(11, 120) = 1 (válido).
d = 11(pois 11 × 11 ≡ 1 mod 120)
C = M_e mod n = 7_11 mod 143 = 106
M = C_d mod n =106_11 mod 143 = 7
M = 7.

E) n = 17 × 31 = 527
φ(n) = (17−1) × (31−1) = 16 × 30 = 480
mdc(7, 480) = 1 (válido).
d = 343(pois 7 × 343 ≡ 1 mod 480)
C = M_e  mod n = 2_7 mod 527 = 128
M = C_d mod n = 128_343 mod 527 = 2
M = 2.

QUESTÃO 7

n = 35 = 5 × 7
Então p = 5 e q = 7

ϕ(n) = (5−1) × (7−1) = 4 × 6 = 24

e=5, ϕ(n) = 24
d × 5 ≡ 1 mod 24
d=5, pois 5 × 5 = 25 ≡ 1 mod24

M = C_d mod n = 10_5 mod 35

10_5 =100000
100000 ÷ 35  =2857(quociente)
100000 − (2857 × 35) = 100000 − 99995 = 5.  o texto claro M é 5.








