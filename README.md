# NLP-fundamentos

No contexto do Processamento de Linguagem Natural (PLN), as expressões regulares (regex) são usadas principalmente para manipular e extrair informações de texto. As expressões regulares podem ser aplicadas em tarefas de pré-processamento de texto, tokenização e busca de padrões específicos em corpora linguísticos.

Algumas situações em que as expressões regulares são úteis no PLN incluem:

Tokenização: Dividir um texto em unidades significativas, chamadas de tokens. Por exemplo, uma expressão regular pode ser usada para dividir um texto em palavras, removendo pontuações.

Remoção de Stop Words: Expressões regulares podem ser usadas para identificar e remover palavras comuns (stop words) de um texto.

Extração de Informações: Ao buscar padrões específicos em um texto, como datas, números de telefone, endereços de e-mail, etc., as expressões regulares podem ser úteis para extrair essas informações.

Limpeza de Texto: Remover caracteres indesejados, espaços extras, ou realizar outras tarefas de limpeza no texto.

Validação de Formatos: Verificar se o texto segue um formato específico, como um formato de data ou número de telefone.

Expressoes Regulares

#importação da biblioteca 
import re

"\w+ - matches word - Magic"
"\d+ - matches digits - g "
"\s -  matches spaces - ' ' "
" .* -  matches wildcard - 'username74' " 

" + or * - greedy match - 'aaaaa' " 

"\S - matches not space - 'no_spaces' "
"[a-z] - lowercase group - 'abcdef' "
