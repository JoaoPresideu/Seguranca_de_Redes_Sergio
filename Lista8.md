QUESTÃO 1

O mdc de 𝑛 e 𝑛+1 é 1 porque números consecutivos não têm divisores em comum além de 1, já que a diferença entre eles é exatamente 1.
Portanto: mdc(n,n+1)=1

QUESTÃO 2

Aplicando o Teorema de Fermat:
3_10 ≡ 1 mod 11

Múltriplo de 10 :
201 = 20 × 10 + 1

3 201=(3_10)_20 x 3¹
(3_10)_20 ≡ 1_20 ≡ 1 mod 11
3_201 ≡ 1 × 3 ≡ 3 mod 11
3_201 mod 11 = 3

QUESTÃO 3

a ≡ 9794 mod 73
9794 ÷ 73 ≈ 134,5
9794 − (73 × 134) = 9794 − 9782 = 12
9794 ≡ 12 mod 73
O número 𝑎 entre 0 e 72 que é congruente a 9794 módulo 73 é: a = 12

QUESTÃO 4

1. EncontraNDO ϕ(10)
ϕ(10) = ϕ(2×5) = ϕ(2)×ϕ(5)
ϕ(2)=2−1=1
ϕ(5)=5−1=4
ϕ(10)=1×4=4

2. a ϕ(n) ≡ 1 mod n

3. 7ϕ_(10) ≡ 7_4 ≡ 1 mod 10
 1000=4×250
 7_1000 = (7_4)_250
7_4 ≡ 1 mod 10:
(7_4)_250 ≡ 1_250 ≡ 1 mod 10
7_1000 mod 10 = 1
a = 1.

QUESTÃO 5
Primeiros fatores de 35 são 5 e 7.
Vamos usar n = p × q:
ϕ(35)=ϕ(5)×ϕ(7)
ϕ(5)=5−1=4
ϕ(7)=7−1=6
ϕ(35)=4×6=24

Teorema de Euler:a 
ϕ(n) ≡ 1 mod n    =  x_24 ≡ 1 mod 35

Reduzir o expoente 85 módulo ϕ(35):
85=24×3+13
x_85 ≡ x_13 mod 35
x_13 ≡ 6 mod 35

Testando: Para x = 6:
6_13 mod 35 = 6
x=6 satisfaz a congruência. O número x entre 0 e 28 que satisfaz 𝑥_85 ≡ 6 mod 35 é x=6.

QUESTÃO 6 X

QUESTÃO 7

Descompondo 2046=2⋅1023
Portanto, s = 1 e d = 1023.

2_d mod 2047: 2_1023 mod 2047

2¹ mod 2047: 2¹ mod 2047 = 2

2² ⋅ 1023  =2 ⋅ 1023 = 2046
2_2046 mod 2047 = 1 (por definição de pseudoprimo)
2_1023 ≡ − 1 mod 2047, logo 2047 é um pseudo-primo forte à base 2.

QUESTÃO 8

1.Combinar x ≡ 2 mod 3 e x ≡ 2 mod 7
x ≡ 2 mod lcm(3,7)
x ≡ 2 mod 21

2.Combinar x ≡ 2 mod 21 com x ≡ 3 mod 5
Substituimos x = 21k + 2 na congruência x ≡ 3 mod 5: 21k+2 ≡ 3 mod 5
Simplificamos: 21 ≡ 1 mod 5
1k + 2  ≡3 mod5
k + 2 ≡ 3 mod5
k ≡ 1 mod5
k = 5m+1

3. Substituir k = 5m + 1:
x = 21(5m + 1) + 2
x = 105m + 21 + 2
x = 105m + 23
x ≡ 23 mod 105
A menor solução positiva será x=23.




