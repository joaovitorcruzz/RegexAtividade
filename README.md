﻿# RegexAtividade

Para a realização desta atividade, segui o seguinte estilo de formatação, para nomes, emaill e telefones;
 
Nome:
A expressão regular utilizada para o nome foi: /^[a-zA-Z\s]*$/.
Essa expressão regular permite apenas letras maiúsculas e minúsculas (de A a Z) e espaços em branco.
Descrição:
^: Indica o início da string.
[a-zA-Z\s]: Define um conjunto de caracteres permitidos, inclui letras maiúsculas e minúsculas (de A a Z) e espaços em branco.
*: Indica que o conjunto de caracteres anterior pode aparecer zero ou mais vezes.
$: Indica o fim da string.



E-mail:
A expressão regular utilizada para o e-mail foi: /^[^\s@]+@[^\s@]+\.[^\s@]+$/.
Essa expressão regular verifica se o e-mail tem um formato válido.
Descrição:
^: Indica o início da string.
[^\s@]+: Define um conjunto de caracteres permitidos antes do símbolo "@" que não inclui espaços em branco.
@: Indica o símbolo "@".
[^\s@]+: Define um conjunto de caracteres permitidos após o símbolo "@" que não inclui espaços em branco.
\.: Verifica a presença de um ponto.
[^\s@]+: Define um conjunto de caracteres permitidos após o ponto que não inclui espaços em branco.
$: Indica o fim da string.



Telefone:
A expressão regular utilizada para o telefone foi: /^\d{10,}$/.
Essa expressão regular verifica se o telefone tem pelo menos 10 dígitos.
Descrição:
^: Indica o início da string.
\d: Representa um dígito de 0 a 9.
{10,}: Indica que o dígito anterior (representado por \d) deve aparecer pelo menos 10 vezes.
$: Indica o fim da string.
