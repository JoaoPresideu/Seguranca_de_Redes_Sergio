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

def encrypt(text, shift):
    result = ""
    for char in text:
        if char.isalpha():
            base = ord('A') if char.isupper() else ord('a')
            result += chr((ord(char) - base + shift) % 26 + base)
        else:
            result += char
    return result

def decrypt(text, shift):
    return encrypt(text, 26 - shift)

def main():
    text = input("Digite o texto: ")
    shift = int(input("Digite o valor de deslocamento: "))
    
  encrypted = encrypt(text, shift)
  print("Texto encriptado: " + encrypted)
    
  decrypted = decrypt(encrypted, shift)
  print("Texto decriptado: " + decrypted)

if __name__ == "__main__":
    main()


QUESTÃO 5

from collections import Counter
import string

portuguese_letter_freq = {
    'A': 14.63, 'E': 12.57, 'O': 10.73, 'S': 7.81, 'R': 6.53, 'I': 6.18,
    'N': 5.05, 'D': 4.99, 'M': 4.74, 'U': 4.63, 'T': 4.34, 'C': 3.88,
    'L': 2.78, 'P': 2.52, 'V': 1.67, 'G': 1.30, 'H': 1.28, 'Q': 1.20,
    'B': 1.04, 'F': 1.02, 'Z': 0.47, 'J': 0.40, 'X': 0.21, 'K': 0.02,
    'Y': 0.01, 'W': 0.01
}

def decrypt_caesar(ciphertext, shift):
    decrypted_text = []
    for char in ciphertext:
        if char.isalpha():
            shift_amount = shift if char.islower() else shift % 26
            decrypted_char = chr((ord(char) - shift_amount - 97) % 26 + 97) if char.islower() else chr((ord(char) - shift_amount - 65) % 26 + 65)
            decrypted_text.append(decrypted_char)
        else:
            decrypted_text.append(char)
    return ''.join(decrypted_text)

def frequency_analysis(ciphertext):
    counter = Counter(filter(str.isalpha, ciphertext.upper()))
    total_chars = sum(counter.values())
    char_freq = {char: (count / total_chars) * 100 for char, count in counter.items()}
    return char_freq

def score_text(text, freq_table):
    text_freq = frequency_analysis(text)
    score = sum(abs(text_freq.get(char, 0) - freq_table.get(char, 0)) for char in freq_table)
    return score

def decrypt_caesar_cipher(ciphertext, top_n=10):
    possible_texts = [(decrypt_caesar(ciphertext, shift), shift) for shift in range(26)]
    scored_texts = sorted(possible_texts, key=lambda x: score_text(x[0], portuguese_letter_freq))
    return scored_texts[:top_n]

ciphertext = "exemplo de texto cifrado aqui"

top_n = 10
resultados = decrypt_caesar_cipher(ciphertext, top_n)

for texto, chave in resultados:
print(f"Chave: {chave}, Texto: {texto}")

QUESTÃO 6

import numpy as np

def encrypt(message, key):
    message = message.upper().replace(" ", "")  
    n = len(message)
    
   if n % 2 != 0:
        message += 'X'
        n += 1
   message_nums = [ord(char) - ord('A') for char in message]
   message_matrix = np.array(message_nums).reshape(-1, 2)
    
   encrypted_message = ''
    for pair in message_matrix:
        encrypted_pair = np.dot(key, pair) % 26
        encrypted_message += ''.join([chr(num + ord('A')) for num in encrypted_pair])
    
return encrypted_message


def decrypt(encrypted_message, key):
    key_inv = np.linalg.inv(key)  # Calculando a matriz inversa da chave
    key_inv = np.round(key_inv * np.linalg.det(key)).astype(int) % 26  # Convertendo para inteiros módulo 26
    
   encrypted_message = encrypted_message.upper().replace(" ", "")  # Convertendo para maiúsculas e removendo espaços
   n = len(encrypted_message)
  
encrypted_nums = [ord(char) - ord('A') for char in encrypted_message]
encrypted_matrix = np.array(encrypted_nums).reshape(-1, 2)
    
decrypted_message = ''
for pair in encrypted_matrix:
        decrypted_pair = np.dot(key_inv, pair) % 26
        decrypted_message += ''.join([chr(num + ord('A')) for num in decrypted_pair])
    
return decrypted_message

key = np.array([[3, 5], [7, 2]])  # Chave fixa para simplificação
message = "HELLO WORLD"

encrypted_message = encrypt(message, key)
print(f"Mensagem encriptada: {encrypted_message}")

decrypted_message = decrypt(encrypted_message, key)
print(f"Mensagem decriptada: {decrypted_message}")







