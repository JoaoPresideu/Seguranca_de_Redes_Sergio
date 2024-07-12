# Seguranca_de_Redes_Sergio

Discente: JOÃO VICTOR IANE GOIS PRESIDEU                                          

LISTA 1 - CAPÍTULO 01

QUESTÃO 1

A arquitetura de segurança OSI (Open System Interconnection) oferece uma estrutura sistemática para definir ataques à segurança, mecanismo e serviços. E é útil para os gerentes como um meio de organizar a tarefa de prover segurança.

QUESTÃO 2

A diferença é que um Ataque passivo tenta descobrir ou utilizar informações do sistema, mas não afeta seus recursos. Um ataque ativo tenta alterar os recursos do sistema ou afeta sua operação.

QUESTÃO 3

Os Ataques Passivos possuem a natureza de bisbilhotar ou monitorar transmissões. O objetivo é obter informações que estão sendo transmitida. Dois tipos de ataques passivos são: liberação do conteúdo da mensagem e análise de trafego.
Os Ataques Ativos envolvem alguma modificação do fluxo de dados ou a criação de um fluxo falso e podem ser subdivido em quatro categorias: disfarce, repetição, modificação de mensagens e negação de serviço.

QUESTÃO 4

1. Autenticação
Verifica a identidade de usuários ou sistemas antes de conceder acesso a recursos. Um exemplo é o uso de nome de usuário e senha para login.

2. Controle de Acesso
Determina e aplica quem pode acessar ou modificar recursos específicos. Um exemplo é a configuração de permissões de leitura e escrita em arquivos.

3. Confidencialidade
Assegura que informações só sejam acessíveis a indivíduos autorizados. A criptografia de dados é um exemplo dessa prática.

4. Integridade
Garante que os dados não sejam alterados ou corrompidos sem autorização. Ferramentas como assinaturas digitais e checksums são usadas para esse fim.

5. Não Repúdio
Previne que uma entidade negue a realização de uma ação ou comunicação previamente realizada. Isso é conseguido através de registros de log e assinaturas digitais.

6. Disponibilidade
Assegura que os recursos e serviços estejam acessíveis para usuários autorizados sempre que necessário. Medidas contra ataques de negação de serviço (DoS) são exemplos dessa prática.

7. Auditoria e Monitoramento
Registra e analisa atividades no sistema para detectar e responder a comportamentos suspeitos. Logs de segurança e sistemas de detecção de intrusões (IDS) são exemplos de ferramentas utilizadas para essa finalidade.

Esses serviços são essenciais para garantir uma proteção abrangente e eficaz dos sistemas e dados contra diversas ameaças e ataques.


QUESTÃO 5

Sistema de Detecção e Prevenção de Intrusões (IDS/IPS): É qualquer processo(ou um dispositivo incorporado tal processo) projetado para detectar, impedir, ou permitir a recuperação deum ataque à segurança. 
Criptografia: Protege a confidencialidade e a integridade dos dados ao transformá-los em um formato ilegível para qualquer pessoa que não tenha a chave de decodificação.
Assinaturas Digitais: Garantem a autenticidade e a integridade dos dados, funcionando como uma assinatura eletrônica que verifica a identidade do remetente e assegura que o conteúdo não foi alterado.
Controle de Acesso: Restringe o acesso a recursos e informações apenas para usuários autorizados, garantindo que apenas pessoas ou sistemas com permissões adequadas possam acessar dados sensíveis.
 Certificados Digitais: Utilizados para verificar a identidade de uma entidade (pessoa, organização, servidor) através de uma autoridade certificadora confiável.
 Firewalls: Dispositivos ou programas que filtram o tráfego de rede, bloqueando acessos não autorizados e protegendo a rede interna de ameaças externas.
 Sistemas de Detecção de Intrusões (IDS): Monitoram a rede ou sistemas para detectar atividades suspeitas ou maliciosas, alertando os administradores sobre possíveis ataques.
Autenticação: Processo de verificação da identidade de um usuário ou dispositivo antes de permitir o acesso a recursos, normalmente usando senhas, tokens ou biometria.
Controle de Integridade: Garante que os dados não foram alterados ou corrompidos de forma não autorizada, frequentemente usando somas de verificação (hashes) para verificar a integridade dos dados.
Esses mecanismos trabalham de forma integrada para garantir a confidencialidade, integridade, disponibilidade e autenticidade das informações, essenciais para a segurança em redes de computadores.

QUESTÃO 6

O sistema deve manter os números de identificação pessoal confidenciais, tanto no sistema do 
host quanto durante a transmissão de uma transação , assim isso é de alta importância.
Também deve proteger a integridade dos registros de contas e de transações individuais, logo também tem alta importancia.
Já a disponibilidade do sistema host é importante para o bem-estar econômico do banco, mas não à sua responsabilidade fiduciária. A disponibilidade de caixas eletrônicos individuais é menos preocupante, então podemos considerar de importância média.



QUESTÃO 7

![1](https://github.com/user-attachments/assets/7161c67c-62fc-4d43-9f3e-4c21d2ee761d)



LISTA 2 - CAPÍTULO 02

QUESTÃO 1

A) 
Os   elementos   essenciais   são   o   texto   claro,   algoritmo   de   criptografia,   chavesecreta, texto cifrado, algoritmo de descriptografia.

B) 
As   funções   básicas   são   proteger   os   dados   digitais,   tendo   algoritmo   de   cifrar e decifrar como as principais

C)
Uma cifra em fluxo é uma cifra que processa os elementos da entrada (bytes, usualmente) continuamente, produzindo a saída de um elemento de cada vez, enquanto prossegue.
Uma cifra de bloco processa a entrada de um bloco de elementos (bytes) de
cada vez, medido por sua quantidade de bits, produzindo um bloco de saída para cada bloco de entrada.
O processamento por fluxo é mais rápido do que por bloco.

D)
As tecnicas usadas são a criptoanálise e ataque por força bruta sobre a chave.

E)
Os problemas são que a chave   precisa ser usada uma única vez. Se repetida, ela pode   ser   facilmente quebrada. Essa  era a principal  vulnerabilidadede uma cifra semelhante , o outro problema  é que  a chave  precisa  ser  tão   longa quanto a mensagem. Isso implica numa grande dificuldade de gerar  e armazenar chaves para mensagens longas.

F)
É uma técnica de criptografia que reorganiza as posições dos caracteres no texto, sem alterar os próprios caracteres.

G)
Esteganografia é uma técnica que consiste em esconder um arquivo  dentro do outro, de forma   criptografada. Porém,ao contrário da criptografia, que visa deixar as mensagens incompreensíveis,   esta tem como objetivo esconder a existência de uma determinada mensagem, camuflando-a dentro   de outros arquivos,  imagens, músicas, vídeos ou textos. Sendo assim, é   possível, por exemplo,   esconder mensagens dentro de  imagens sem que outras pessoas desconfiem que existe alguma coisa escrita ali.


QUESTÃO 2 

A -   
Não. Uma mudança no valor de b muda a relação entre letras de texto plano e letras de texto cifrado para a esquerda ou direita uniformemente, de modo que, se o mapeamento for um para um, ele permanece um para um

B-
 2, 4, 6, 8, 10, 12, 13, 14, 16, 18, 20, 22, 24. Qualquer valor maior do que 25 é equivalente para a mod 26.

C-
Os valores  de  a  e  26 não  devem  ter  um  fator  inteiro positivo comum  diferente de 1.  Isto é equivalente a dizer que a e 26 são relativamente primos, ou que o maior divisor comum de um e 26 é 1. Para ver isto, primeiro note que E (a, p) = E (a, q) (0 ≤ p ≤ q <26) se e somente se a (p - q) é divisível por 26. 1. Suponha que a e 26 sejam relativamente primos. Então, um (p - q) não é divisível por 26, porque não tem jeito para reduzir a fração a / 26 e (p - q) é menor que 26. 2. Suponha que a e 26 têm um fator comum k> 1. Então E (a, p) = E (a, q), se q = p + m / k ≠ p.

QUESTÃO 3

![2](https://github.com/user-attachments/assets/1ab3ed4c-3497-4e44-9fca-83d72b4a6d93)


QUESTÃO 4

![questão4](https://github.com/user-attachments/assets/1955b827-5608-4fd2-a238-03233981bc15)


QUESTÃO 5

![QUESTAO5](https://github.com/user-attachments/assets/fe79c5d0-d1ad-4178-8aab-49cbfa30b50a)

QUESTÃO 6

![questao6](https://github.com/user-attachments/assets/2dce4469-fa36-4b46-91de-61c2275c8d3e)



LISTA 3 - CAPÍTULO 03

QUESTÃO 1

A)
É a base para muitos algoritmos de criptografia, como o DES.

B)
Uma cifra em fluxo é uma cifra que processa os elementos da entrada (bytes, usualmente) continuamente, produzindo a saída de um elemento de cada vez, enquanto prossegue.
Uma cifra de bloco ela processa a entrada de um bloco de elementos (bytes) de
cada vez, medido por sua quantidade de bits, e produzindo um bloco de saída para cada bloco de entrada.
O processamento por fluxo é mais rápido do que por bloco

C)
Pela facilidade de quebra por análise de frequência.

D)
Combinação de duas ou mais cifras simples para aumentar a segurança.

E)
Difusão: Espalhar bits do texto claro no texto cifrado.
Confusão: Tornar a relação entre texto claro e texto cifrado complexa.

F)Função de rodada, número de rodadas, chave de encriptação.

G)
É uma equena mudança no texto claro ou na chave resulta em uma grande mudança no texto cifrado.

QUESTÃO 2

ALTERNATIVA D  Todas as alternativas estão presentes no projeto da rede de Feistel:

Tamanho do bloco e da chave: Define a estrutura básica do processamento de dados e a segurança do algoritmo.
Função da rodada: Aplicada repetidamente para transformar os dados de entrada.
Gerador de sub-chaves: Cria chaves derivadas para cada rodada, aumentando a segurança e variabilidade do processo de encriptação.

QUESTÃO 3

ALTERNATIVA D 64.

O Data Encryption Standard (DES) encripta blocos de dados de 64 bits de comprimento. Isso significa que cada vez que o DES é aplicado, ele processa exatamente 64 bits de texto claro por vez. 

QUESTÃO 4

Cada S-box recebe 6 bits como entrada e produz 4 bits como saída. O DES possui um total de 8 rodadas, e em cada rodada, são utilizadas 6 S-boxes para realizar substituições não lineares nos dados, aumentando a complexidade e segurança do algoritmo.

 QUESTÃO 5

Ataque de Força-Bruta porque refere-se à tentativa de testar todas as possíveis combinações de chaves (2^56 no caso do DES) para encontrar a chave correta de encriptação.

QUESTÃO 6

Passo a Passo do Processo:
Definição da Chave:
Escolher uma chave fixa para simplificação do exemplo. A chave deve ser uma matriz 2x2 invertível.

Encriptação:
Converter cada par de caracteres (16 bits) em números correspondentes (A=0, B=1, ..., Z=25).
Dividir o texto em dois pares de números.
Aplicar a matriz chave para encriptar cada par.
Repetir o processo para dois rounds.

Decifração:
Calcular a matriz inversa da chave.
Aplicar a matriz inversa para decifrar cada par de números.
Converter os números de volta para caracteres.
![QUESTAO6_LISTA3](https://github.com/user-attachments/assets/2c194331-c441-4334-b6a5-5bdbdf7048a8)

QUESTÃO 7

A cifra de Feistel mencionada tem um padrão previsível no modo como as chaves são usadas e reutilizadas. Isso significa que, após as primeiras oito rodadas, as chaves começam a ser repetidas de trás para frente até completar as dezesseis rodadas. Isso cria um padrão que pode ser explorado por um atacante. Imaginamos que temos um dispositivo que pode cifrar mensagens quando você o consulta. Normalmente, esse dispositivo é usado para proteger informações, mas, neste caso, o padrão previsível de como as chaves são usadas permite que um atacante, ao enviar uma mensagem especial, possa deduzir quais chaves foram usadas para cifrar essa mensagem.
Isso é preocupante porque um atacante pode, com apenas uma consulta a esse dispositivo e observando a resposta cifrada, descobrir todas as chaves que foram usadas na cifragem. Isso compromete a segurança do sistema, pois a confidencialidade das mensagens pode ser comprometida.





