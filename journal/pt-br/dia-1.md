# 1º Dia - Array

O primeiro dia é sobre Arrays que, segundo o material enviado, são:

> Arrays são estruturas de dados que armazenam elementos em sequência na memória, por isso, conseguimos acessar um elemento pelo seu índice, que sempre começa em 0!
>
> -- <cite>Giovanna Moeller</cite>

Uma explicação precisa, exata e concisa como o meio pede (lembrem que o material vai por e-mail), mas não foi o suficiente pra minha necessidade de saber as coisas. Por sorte, no e-mail também existe um link que aponta para um [artigo da Alura](https://www.alura.com.br/artigos/javascript-para-que-serve-array?_hsmi=270746392) para que quisessem mais detalhes, e é claro que eu me interessei.

O artigo detalha se extende um pouco mais, porém no propósito de explicar como utilizar arrays em JavaScript, não no que são arrays, o que me criou mais uma pergunta: como funcionam os arrays em JavaScript por baixo dos panos? Mais ainda! **Como são os arrays em cada uma das linguagens que me propuz a utilizar neste desafio?**

## O que são arrays?

Lembro que a primeira vez que tive contato com o termo "array" foi durante as aulas de POO quando fiz técnico em automação e, honestamente, não lemnbro da explicação do professor, mas lembro de pensar em `List` como umas forma mais fácil trabalhar dos vetores que tinha visto em C. Um tempo depois, agora na faculdade, lembro das minhas aulas sobre listas em C (simples, duplas, circulares) e pensar "ah, ok, então na real isso são os arrays em Java por baixo de tudo. Alguns podem me indagar o que eu vi sobre isso nas aulas de Estruturas de dados e para estes eu direi que tudo que ficou na minha memória dessas aulas foram árvores.

Bem, o que de fato é array?

Segundo [este artigo](https://en.wikipedia.org/wiki/Array_(data_structure)) (em inflês) da Wikipédia:
> In computer science, an array is a data structure consisting of a collection of elements (values or variables), of same memory size, each identified by at least one array index or key. An array is stored such that the position of each element can be computed from its index tuple by a mathematical formua.

Numa tradução livre para português:
> Na ciencência da computação, um _array_ é uma estrutura de dados que consiste em uma coleção de elementos (valores ou variáveis), de mesmo tamanho em memória, identificados por ao menos um indíce ou chave do array. Um array é armazenada de forma que a posição de cada elemento possa ser calculado a partir de sua tupla de indíce com uma forma matemática.

A partir disto podemos entender que um array é uma coleção de itens de mesmo tamanho em memória acessiveis por meio de um índice que permita calcular sua posição na memória. Por exemplo: se temos um array de intens que ocupam 4 bytes na memória e a nossa memória é endereçada em espaços de um byte, temos que a posição de cada item desse array seria índice x tamanho em bytes do tipo (1 x 4, 2 x 2, 3 x 4, etc).

O [_Dictionrary of Algorithms and Data Structures_](https://www.nist.gov/dads/) do [NIST (National Institute of Standards and Technoly)](https://xlinux.nist.gov/) define _array_ como "um conjunto de items podem ser acessados de forma aleatória utilizando inteiros, o índice" e indica que comumente um _array_ possui tamanho fixo, comportamento que pode ser modificado em outras estruturas que derivam e/ou especializam os _arrays_ básicos, como o _array dinâmico_, e costuma ser iniciado em 0 ou 1, dependendo da implementação.

Portando, adicionando esta definição ao nosso entendimento sobre _arrays_, temos que:
> Array é uma coleção finita, com tamanho máximo definido, de items de mesmo tamanho em memória acessíveis por meio de um índice inteiros, inciando em 0 ou 1, que permite calcular a sua posição em memória.