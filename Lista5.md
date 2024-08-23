QUESTÃO 1

Quando o NIST selecionou o AES, ele usou esses critérios principais para avaliar as cifras candidatas:

Segurança: A cifra precisava ser forte contra ataques, ou seja, proteger bem os dados.
Desempenho: A cifra deveria ser rápida e eficiente em diferentes tipos de computadores e dispositivos.
Facilidade de Implementação: Deveria ser fácil de implementar sem erros.
Versatilidade: A cifra deveria ser útil para diferentes tipos de aplicações.

QUESTÃO 2

No final, o NIST usou critérios semelhantes, mas com mais detalhes:

Segurança: A cifra precisava ser resistente a ataques conhecidos e oferecer proteção sólida.
Desempenho: A cifra deveria ser eficiente em diversos tipos de hardware e software.
Facilidade de Implementação: A implementação deveria ser simples e não propensa a erros.
Flexibilidade: Deveria suportar chaves de diferentes tamanhos e ser adaptável a diferentes usos.

QUESTÃO 3

Rijndael é um algoritmo de criptografia que pode usar blocos e chaves de vários tamanhos.
AES é uma versão específica do Rijndael adotada como padrão, que usa blocos de 128 bits e chaves de 128, 192 ou 256 bits.

QUESTÃO 4

A)
O array Estado é onde o texto claro é armazenado e transformado durante a criptografia no AES. É atualizado em cada etapa do processo para eventualmente se tornar o texto cifrado.

B) 
A S-box é uma tabela que substitui cada byte do array Estado por outro byte. Ela é criada através da inversão dos bytes em um campo matemático e, em seguida, aplica-se uma transformação adicional para criar a tabela final.

C) 
SubBytes: Substitui cada byte do array Estado por um byte diferente usando a S-box.
ShiftRows: Desloca os bytes nas linhas do array Estado para a esquerda em diferentes quantidades.
MixColumns: Mistura os bytes em cada coluna do array Estado para aumentar a difusão dos dados.
AddRoundKey: Adiciona a chave da rodada ao array Estado usando a operação XOR.
Algoritmo de Expansão de Chave: Gera várias subchaves a partir da chave original, que são usadas em cada rodada do AES.

QUESTÃO 5

Todos os 16 bytes do array Estado são afetados, mas cada byte é deslocado de forma diferente:

Primeira linha: Não é deslocada.
Segunda linha: Os bytes são deslocados uma posição para a esquerda.
Terceira linha: Os bytes são deslocados duas posições para a esquerda.
Quarta linha: Os bytes são deslocados três posições para a esquerda.

QUESTÃO 6

0011 0100 0010 0000. Usando um XOR

QUESTÃO 7

A) XOR do material da subchave com a entrada da função f

DES: XOR da subchave com a entrada da função f.
AES: No AES, a subchave é adicionada diretamente ao estado usando XOR na etapa AddRoundKey. Não há função f.

B) XOR da saída da função f com a metade esquerda do bloco

DES: A saída da função f é XORada com a metade esquerda do bloco.
AES: O AES não divide o bloco em metades. Em vez disso, usa o MixColumns e SubBytes para transformar o bloco inteiro.

C) Função f

DES: Função 𝑓 combina substituição, permutação e XOR com a subchave.
AES: Não há uma função 𝑓 em AES. Usa SubBytes, ShiftRows, MixColumns, e AddRoundKey.

D) Permutação P

DES: Permutação 𝑃 embaralha bits após a função 𝑓.
AES: Usa ShiftRows e MixColumns para espalhar e permutar bytes, sem uma permutação 𝑃 específica.

D) Troca de metades do bloco

DES: Troca as metades esquerda e direita do bloco após cada rodada.
AES: Não divide o bloco em metades. Pois, transforma o bloco inteiro usando várias operações.




