QUESTÃO 1 

A) É a base para muitos algoritmos de criptografia, como o DES.

B) Uma cifra em fluxo é uma cifra que processa os elementos da entrada (bytes, usualmente) continuamente, produzindo a saída de um elemento de cada vez, enquanto prossegue. Uma cifra de bloco ela processa a entrada de um bloco de elementos (bytes) de cada vez, medido por sua quantidade de bits, e produzindo um bloco de saída para cada bloco de entrada. O processamento por fluxo é mais rápido do que por bloco

C) Pela facilidade de quebra por análise de frequência.

D) Combinação de duas ou mais cifras simples para aumentar a segurança.

E) Difusão: Espalhar bits do texto claro no texto cifrado. Confusão: Tornar a relação entre texto claro e texto cifrado complexa.

F)Função de rodada, número de rodadas, chave de encriptação.

G) É uma equena mudança no texto claro ou na chave resulta em uma grande mudança no texto cifrado.

QUESTÃO 2

ALTERNATIVA D Todas as alternativas estão presentes no projeto da rede de Feistel:

Tamanho do bloco e da chave: Define a estrutura básica do processamento de dados e a segurança do algoritmo. Função da rodada: Aplicada repetidamente para transformar os dados de entrada. Gerador de sub-chaves: Cria chaves derivadas para cada rodada, aumentando a segurança e variabilidade do processo de encriptação.

QUESTÃO 3

ALTERNATIVA D 64.

O Data Encryption Standard (DES) encripta blocos de dados de 64 bits de comprimento. Isso significa que cada vez que o DES é aplicado, ele processa exatamente 64 bits de texto claro por vez.

QUESTÃO 4

Cada S-box recebe 6 bits como entrada e produz 4 bits como saída. O DES possui um total de 8 rodadas, e em cada rodada, são utilizadas 6 S-boxes para realizar substituições não lineares nos dados, aumentando a complexidade e segurança do algoritmo.

QUESTÃO 5

Ataque de Força-Bruta porque refere-se à tentativa de testar todas as possíveis combinações de chaves (2^56 no caso do DES) para encontrar a chave correta de encriptação.

QUESTÃO 6

Passo a Passo do Processo: Definição da Chave: Escolher uma chave fixa para simplificação do exemplo. A chave deve ser uma matriz 2x2 invertível.
Encriptação: Converter cada par de caracteres (16 bits) em números correspondentes (A=0, B=1, ..., Z=25). Dividir o texto em dois pares de números. Aplicar a matriz chave para encriptar cada par. Repetir o processo para dois rounds.
Decifração: Calcular a matriz inversa da chave. Aplicar a matriz inversa para decifrar cada par de números. Converter os números de volta para caracteres.

![348353057-2c194331-c441-4334-b6a5-5bdbdf7048a8](https://github.com/user-attachments/assets/594b5d38-3f00-4879-a632-83325eba4c5c)

QUESTÃO 7

A cifra de Feistel mencionada tem um padrão previsível no modo como as chaves são usadas e reutilizadas. Isso significa que, após as primeiras oito rodadas, as chaves começam a ser repetidas de trás para frente até completar as dezesseis rodadas. Isso cria um padrão que pode ser explorado por um atacante. Imaginamos que temos um dispositivo que pode cifrar mensagens quando você o consulta. Normalmente, esse dispositivo é usado para proteger informações, mas, neste caso, o padrão previsível de como as chaves são usadas permite que um atacante, ao enviar uma mensagem especial, possa deduzir quais chaves foram usadas para cifrar essa mensagem. Isso é preocupante porque um atacante pode, com apenas uma consulta a esse dispositivo e observando a resposta cifrada, descobrir todas as chaves que foram usadas na cifragem. Isso compromete a segurança do sistema, pois a confidencialidade das mensagens pode ser comprometida.
