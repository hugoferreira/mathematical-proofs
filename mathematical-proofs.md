## Mathematical Proofs, 3rd edition

### Chapter 1: Sets

#### Section 1.1: Describing a Set

##### 1.1. Which of the following are sets?

> a. ~~1, 2, 3~~
b. ~~{1, 2}, 3~~ 
c. ~~{{1}, 2}, 3~~ 
d. {1, {2}, 3}
e. {1, 2, a, b}

> <i class="icon-pencil"></i> **Note.** This seems to be more of a notational question. Every item can be regarded as a set of things. There are no duplicate items, although they don't always share the same *domain*. Anyway, since the book states that a set should be denoted with `{...}`, only `d` and `e` qualify.

##### 1.2. Let $S = \{−2, −1, 0, 1, 2, 3\}$. Describe each of the following sets as $\{x ∈ S : p(x)\}$, where $p(x)$ is some condition on $x$.

> $A = \{1, 2, 3\} = \{x ∈ S: x \gt 0\} = \{x ∈ S: x \geq 1\}$
$B = \{0, 1, 2, 3\} = \{x ∈ S: x \geq 0\}  = \{x ∈ S: x \gt -1\}$ 
$C = \{−2, −1\} = \{x ∈ S: x \lt 0\}  = \{x ∈ S: x \leq 1\}$
$D = \{−2, 2, 3\} = \{x ∈ S: |~x~| \gt 1\}  = \{x ∈ S: |~x~| \geq 2\}$

> <i class="icon-pencil"></i> **Note.** With inequalities, there's always more than one way to express the same thing.

##### 1.3. Determine the cardinality of each of the following sets.

> $A = \{1,2,3,4,5\} \rightarrow |~A~| = 5$
$B = \{0,2,4,\ldots,20\} \rightarrow |~B~| = 11$
$C = \{25,26,27,\ldots,75\}  \rightarrow |~C~| = 51$
$D = \{\{1,2\},\{1,2,3,4\}\} \rightarrow |~D~| = 2$
$E = \{∅\} \rightarrow |~E~| = 1$
$F = \{2,\{2,3,4\}\} \rightarrow |~F~| = 2$

> <i class="icon-pencil"></i> **Note.** It's very easy to err with $|~B~| = 10$ and $|~C~| = 50$.

##### 1.4. Write each of the following sets by listing its elements within braces.

> $A = \{n ∈ {\bf Z} : −4 < n ≤ 4\} = \{-3,-2,-1,0,1,2,3,4\} $
$B = \{n ∈ {\bf Z} : n^2 < 5\} = \{-2, -1, 0, 1, 2\}$
$C = \{n ∈ {\bf N} : n^3 < 100\} = \{1, 2, 3, 4\}$
$D = \{x ∈ {\bf R} : x^2 − x = 0\} = \{0, 1\}$
$E = \{x ∈ {\bf R} : x^2 + 1 = 0\} = ∅$

> <i class="icon-pencil"></i> **Note.** Pay attention to the *domain*; ${\bf N}$ does not include zero, and ${\bf R}$ includes positive and negative real numbers, including zero.

##### 1.5. Write each of the following sets in the form $\{x ∈ Z : p(x)\}$, where $p(x)$ is a property concerning $x$.

> $A = \{−1,−2,−3,\ldots\} = \{n ∈ {\bf Z} : n < 0\}$
$B = \{−3,−2,\ldots,3\} = \{n ∈ {\bf Z} : |n| \leq 3\}$
$C = \{−2,−1,1,2\} = \{n ∈ {\bf Z} : |n| \leq 2 \wedge n \neq 0\}$

##### 1.6. The set $E = \{2x : x ∈ {\bf Z}\}$ can be described by listing its elements, namely $E = \{\ldots,−4,−2,0,2,4,\ldots\}$. List the elements of the following sets in a similar manner.

> $A = \{2x+1: x ∈ {\bf Z}\} = \{\ldots,-5, -3, -1, 1, 3, 5,\ldots\}$ 
$B = \{4n: n ∈ {\bf Z}\} = \{\ldots,-8, -4, 0, 4, 8,\ldots\}$
$C = \{3q + 1 : q ∈ {\bf Z}\} = \{\ldots,-5, -2, 1, 4, 7,\ldots\}$

> <i class="icon-pencil"></i> **Note.** There's really no rule of thumb of when to stop the sequence... A defining condition is much more precise and doesn't require subjective pattern matching.

##### 1.7. The set $E = \{\ldots, −4, −2, 0, 2, 4,\ldots\}$ of even integers can be described by means of a defining condition by $E=\{y=2x: x∈{\bf Z}\}=\{2x:x∈{\bf Z}\}$. Describe the following sets in a similar manner.

> $A = \{\ldots,−4,−1,2,5,8,\ldots\} = \{3x - 1: x \in {\bf Z}\}$
$B = \{\ldots,−10,−5,0,5,10,\ldots\} = \{5x: x \in {\bf Z}\}$
$C = \{1,8,27,64,125,\ldots\} = \{x^3: x \in {\bf N}\}$

##### 1.8. Let:
$A = \{n ∈ {\bf Z}: 2 ≤ |~n~| <4\}$,
$B=\{x∈ {\bf Q}: 2<x≤4\}$,
$C=\{x∈ {\bf R}: x^2−(2+\sqrt{2})x+2\sqrt{2}=0\}$, and 
$D=\{x∈ {\bf Q}: x^2−(2+\sqrt{2})x+2\sqrt{2}=0\}$.

a. Describe the set $A$ by listing its elements.

> $A = \{-3, -2, 2, 3\}$

b. Give an example of three elements that belong to $B$ but do not belong to $A$. 

> $S = \{\frac{5}{2}, \frac{7}{3}, 4\}$, where $S \subseteq B \wedge \forall {s \in S}: s \notin A$

c. Describe the set $C$ by listing its elements.

> $C = \{2, \sqrt{2}\}$

d. Describe the set $D$ in another manner.

> $D = \{2\}$

> <i class="icon-pencil"></i> **Note.** Pay attention to the *domain*. $\sqrt{2}$ is not a rational number, so it doesn't belong to ${\bf Q}$, although it does belong to ${\bf R}$. Refer to *pp.* 16--17 of the book.

e. Determine the cardinality of each of the sets $A$, $C$ and $D$.

> $|~A~| = 4$
$|~C~| = 2$
$|~D~| = 1$

1.9. For $A = \{2,3,5,7,8,10,13\}$, let $B=\{x∈A: x=y+z$, where $y,z∈A\}$ and $C=\{r∈B: r+s∈B$ for some $s∈B\}$. Determine $C$.

> $B = \{5, 7, 8, 10, 13\}$
$C=\{5,8\}$

#### Section 1.2: Subsets

##### 1.10. Give examples of three sets $A$, $B$ and $C$ such that:

a. $A ⊆ B ⊂ C$

> $A = \{1, 2\}$, $B = \{1, 2\}$, and $C = \{1, 2, 3\}$ 

b. $A ∈ B, B ∈ C$, and $A \notin C$

> $A = ∅$, $B = \{∅\}$, and $C = \{\{∅\}\}$ 

c. $A ∈ B$ and $A⊂C$

> $A = \{1\}$, $B = \{\{1\}\}$, and $C = \{1, 2\}$

