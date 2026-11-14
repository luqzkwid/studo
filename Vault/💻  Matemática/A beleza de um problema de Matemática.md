---
Data: 6 de novembro de 2026
Assunto: Beleza da matemática
---
### Discutindo sobre um problema matemático do meu livro da escola

Hoje (*6 de novembro de 2026*) me deparei com um problema simples de matemática, porém extremamente legal.
O problema envolvia progressões aritiméticas e polígonos, e no meio da solução aparece uma soma de uma sequência de números ímpares! 
($1 + 3 + 5 + 7 + ...$)

Tal problema era o seguinte:

*Usando palitos de fósforo, foi criada a sucessão de quadrados. A regra para construí-las é sempre adicionar dois novos quadrados na figura seguinte. Desse modo, calcule quantos palitos são necessários para exibir **simultaneamente** as 100 primeiras figuras.*

### Resolução

Primeiro temos que iniciar com duas ideias fundamentais:
 1. Cada figura é representada pelo número de palitos de fósforo que a forma.
 2. Cada quadrado é formado por 4 palitos de fósforo.

Sob essa ótica, ainda temos que seguir mais uma regra que foi falada no enunciado:
==🟠*A regra para construí-las é sempre adicionar dois novos quadrados na figura seguinte.*==

Portando temos que,
$\left\{\begin{aligned}f_1 = 4 \\ f_2 = f_1 + 2 \cdot f_1 = 3 \cdot f_1 \\ f_3 = 3 \cdot f_1 + 2 \cdot f_1 = 5 \cdot f_1 \\ f_4 = 5 \cdot f_1 + 2 \cdot f_1 = 7 \cdot f_1\end{aligned}\right.$  Existe uma Progressão Aritimética de Razão $2 \cdot f_1$

Para obter o número total de palitos de fósforos que existem quando nós exibimos as 100 figuras simultaneamente, basta somar todos as figuras:
	$Total = f_1 + f_2 + f_3 + f_4 + f_5 + \cdot\cdot\cdot + f_{100}$
	$Total = f_1 + 3 \cdot f_1 + 5 \cdot f_1 + 7 \cdot f_1 + \cdot\cdot\cdot a_{100} \cdot f_1$
Colocando o termo $f_1$ em evidência:
	$Total = f_1 \cdot (3 + 5 + 7 + \cdot\cdot\cdot + a_{100})$
Agora ficou fácil, através da fórmula: $a_n = a_1 + (n - 1) \cdot R$, na qual R representa a razão da PA, nós podemos descobrir o termo $a_{100}$ e com isso aplicar uma soma de gauss intuitiva:

Descobrindo o termo $a_{100}$:
	$a_n = a_1 + (n - 1) \cdot R \\ a_{100} = 3 + 99 \cdot 2 \\ a_{100} = 3 + 99 \cdot 2 \\ a_{100} = 199$

Agora basta somar os termos:
	$g: (1, 3, 5, 7, \cdot\cdot\cdot,199)$
	$soma: (1 + 3 + 5 + 7 + \cdot\cdot\cdot + 193 + 195 + 197 + 199) \\ \rightarrow (1 + 199) = 200 \\ (3 + 197) = 200 \\ (5 + 195) = 200 \\ (7 + 193) = 20$
Portando:
	$199 + 200 \cdot 98 = 19799$
	$19799 \cdot 4 = 79196$ palitos.

### Conclusão

Esse problema é incrível pois ele retoma as relações entre polígonos e uma progressão aritimética e mostra que a matemática não é apenas cáculos sem sentido, porém um sistema de pensamento crítico e lógico, capa de solucionar qualquer problema de forma brilhante e concreta.

Após solucioná-lo, criei uma familiaridade com problema similares, revisei um pouco a matéria e melhorei minha forma de pensar.\