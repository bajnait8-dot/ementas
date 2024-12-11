


# TÍTULO DA DISCIPLINA: 	Introdução a lógica e provas.

## MAT1053 --  		Tópicos IV

## CARGA HORÁRIA TOTAL: 	60 HORAS

## No CRÉDITOS:		4

## PROFESSOR:		Sergey Galkin



# OBJETIVOS DA DISCIPLINA/TURMA

Na sua mensagem "As origens e motivações das fundações univalentes. Uma missão pessoal para desenvolver verificação de prova computacional para evitar erros matemáticos." ("The Origins and Motivations of Univalent Foundations. A Personal Mission to Develop Computer Proof Verification to Avoid Mathematical Mistakes.") Vladimir Voevodsky escreve:

   "... vou supor que qualquer fundação de matemática adequada tanto para a raciocínio humano quanto para a verificação por computador deva ter as seguintes três componentes. A primeira é um sistema de dedução formal: uma linguagem e regras de manipulação de sentenças puramente formais, de modo que o registro destas manipulações possa ser verificado por um programa de computador. A segunda componente é uma estrutura que atribui um significado às sentenças desta linguagem em termos de objetos mentais intuitivamente compreensíveis por seres humanos. A terceira componente é uma estrutura que permite aos seres humanos codificar as ideias matemáticas em termos dos objetos diretamente associados à linguagem."

O objetivo neste curso é para alunos aprenderem essas três componentes para melhor se basear em matemática.

O curso introduz os alunos para a lógica matemática, metamatemática, fundações de matemática, conjuntos, tipos e categorias,
relacionamento de matemática, lógica e programação, e as assistentes de provas tais como Coq e LEAN,
as linguagens de programação modernas dedicadas ao programa de formalização e verificação de provas.

# EMENTA DA DISCIPLINA

- Ementa básica:
 Lógica proposicional. Variáveis e quantificadores. Equivalência lógica. Tautologias. Conjuntos e operações com eles. Funções, injetoras e sobrejetoras. Axiomas de Peano, indução. Conjuntos finitos. Cardinalidade e cardinais. Matemática construtiva X não; lei do terceiro excluído, axioma da escolha. Programas assistentes de provas: Lean, Coq, Agda, HOL/Isabelle. Prática de programação e demonstração em Lean.
- Tópicos: 
 O método diagonal de Cantor e a sua reiteração por Russel, Gödel, Brouwer, Lawvere.
Conjuntos, tipos, categorias. Dedução natural. Cálculo lambda. Lógica clássica. Lógica intuicionista e a interpretação de Brouwer--Heyting--Kolmogorov dela. Isomorfismo de Curry--Howard e Curry--Howard--Lambek.

# PRÉ-REQUISITOS DA DISCIPLINA

O aluno precisa de um computador com um teclado.


# PROGRAMA DA DISCIPLINA/TURMA

O primeiro mes alunos jogam em jogo dos números naturais (Natural Number Game) de Kevin Buzzard,
o que é uma gamificação do trabalhos de Grassmann e Peano. Ele serve como uma pre-introdução ao Lean e às provas, está baseado no modo "tático" de provas em LEAN. O objetivo é terminar todos os níveis do jogo.
A partir do segundo mes os alunos já escrevem os programas em LEAN e resolvem os problemas das varias fontes, tais como "Lógica e Provas" (ref [2]).
A partir do segundo mes os alunos aprendem usar LEAN como uma linguagem e assistente de provas,
e aprendem não somente o modo tático, mas também em modo normal, em particular aprendem cálculo lambda.
Todas as soluções são verificadas automaticamente pela mesma assistente LEAN. Para obter o grau 10 o aluno tem que resolver todos os problemas atribuídos e colocar no repositório git. Diferentes alunos recebem distintos problemas (sem interseção).

O curso é feito pelo zoom, com alunos compartilhando o seu terminal de jogo, LEAN, etc,
contribuindo as suas soluções no respositório de github sergunchik/lean212,
e as dicas rápidas pelo bate-papo de LEAN e/ou grupo dedicado de Telegram.

A parte prática do curso está complementada por parte teórica, introduzida por instrutor,
em paralelo.

# AVALIAÇÃO DA DISCIPLINA

- Critério 2
- Média = (G1+2*G2)/3

# DETALHAMENTO AVALIAÇÃO DA DISCIPLINA

A avaliação é baseado nas resoluções de problemas.

O grau G1 é baseado no porcentagem de níveis no jogo dos números naturais que o aluno alcançou,
e adicionais tarefas escritas (i.e. provas em matemática/lógica "não formal" em sentido
do programa de formalização de matemática com computadores e assistentes de provas).

O grau G2, em sua vez, esta baseado na porcentagem dos 10 problemas de provas em LEAN resolvidos, que foram atribuídos para cada aluno.


# BIBLIOGRAFIA BÁSICA DA DISCIPLINA


0. Kevin Buzzard: Natural Number Game, http://wwwf.imperial.ac.uk/~buzzard/xena/natural_number_game
1. Clive Newstead: An infinite Descent into Pure Mathematics, http://infinitedescent.xyz versão 0.4, 01.01.2020, 592 páginas.
2. Jeremy Avigad, Robert Y. Lewis, Floris van Doorn: Logic and Proof, Release 3.18.4, 29.03.2021. 222 páginas. https://leanprover-community.github.io/logic_and_proof

# BIBLIOGRAFIA COMPLEMENTAR DA DISCIPLINA

3. Jeremy Avigad, Kevin Buzzard, Robert Y. Lewis, Patrick Massot: Mathematics in Lean, Release 0.1, 21.02.2021, 63 páginas. https://leanprover-community.github.io/mathematics_in_lean
4. https://github.com/leanprover-community/tutorials
5. Lean for the Curious Mathematician 2020 exercises, https://github.com/leanprover-community/lftcm2020
6. Jeremy Avigad, Leonardo de Moura, Soonho Kong: Theorem Proving in Lean, Release 3.23.0, 167 páginas. https://leanprover.github.io/theorem_proving_in_lean

# BIBLIOGRAFIA DE PESQUISA DA DISCIPLINA 

8. Homotopy Type Theory: Univalent Foundations of Mathematics, https://homotopytypetheory.org/book, Institute for Advanced Study, 2013.
9. Vladimir VOevodsky: The Origins and Motivations of Univalent Foundations
A Personal Mission to Develop Computer Proof Verification to Avoid Mathematical Mistakes. IAS, 2014. https://www.ias.edu/ideas/2014/voevodsky-origins
