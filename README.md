# Seguranca_de_Redes_Sergio
Capítulo 2 - Questões

1°:
a) Os elementos essenciais de uma cifra simétrica são a chave e o algoritmo de criptografia.

b) As duas funções básicas usadas nos algoritmos de criptografia são a função de criptografia e a função de decriptografia.

c)A diferença entre uma cifra de bloco e uma cifra de fluxo é que a cifra de bloco opera em blocos fixos de dados, enquanto a cifra de fluxo opera em dados contínuos, cifrando-os um bit (ou byte) de cada vez.

d)As duas técnicas gerais para atacar uma cifra são ataques de força bruta, que tentam todas as possíveis chaves, e ataques de criptoanálise, que exploram fraquezas no algoritmo de criptografia para encontrar a chave ou os dados originais.

e)Os dois problemas com o one-time pad são a necessidade de chaves tão longas quanto os dados a serem cifrados e a necessidade de que cada chave seja usada apenas uma vez para garantir segurança absoluta.

f)Uma cifra de transposição é um tipo de cifra na qual os caracteres ou blocos de texto são rearranjados de acordo com uma chave específica, sem modificar o conteúdo dos caracteres.

g) Esteganografia é a prática de esconder mensagens ou informações dentro de arquivos, imagens ou outros dados de forma que a presença da informação seja oculta para observadores externos.
***
2°:
a) Sim, existem limitações sobre o valor de b na cifra de César afim. O valor de b deve ser tal que a fórmula (ap + b) mod 26 gere resultados únicos para cada valor de p. Se b não for cuidadosamente escolhido, pode haver colisões, ou seja, dois valores diferentes de p podem produzir o mesmo resultado C. Isso viola o requisito básico de que o algoritmo de criptografia deve ser um-para-um. Portanto, para garantir que a cifra seja um-para-um, b deve ser um número inteiro coprimo com 26.

b) Os valores de a que não são permitidos são aqueles que compartilham um fator comum com 26, exceto 1. Isso ocorre porque, se a e 26 tiverem fatores em comum, então os caracteres de texto claro serão mapeados em ciclos que não cobrem todo o alfabeto, tornando a decriptação impossível ou ambígua. Portanto, os valores de a não permitidos são aqueles que não são coprimos com 26.

c) Uma afirmação geral sobre os valores de a permitidos na cifra de César afim é que a deve ser coprimo com 26 para garantir que a cifra seja um-para-um. Isso ocorre porque, se a e 26 tiverem fatores em comum, então os caracteres de texto claro serão mapeados em ciclos que não cobrem todo o alfabeto, tornando a decriptação impossível ou ambígua. Portanto, a escolha comum para a é selecionar um número primo em relação a 26, garantindo assim que a cifra seja um-para-um.
***
3°:
