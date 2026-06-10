### Exercise 1.2.3. 
 Decide which of the following represent true statements about the nature of sets. For any that are false, provide a specific example where the statement in question does not hold.
(a) if \(A_1 \supseteq A_2 \supseteq A_3 \supseteq A_4\dots\) are sets containing an infinite number of elements, then the intersection \(\bigcap_{n=1}^{\infty}A_n\) is infinite as well.
(b) if \(A_1 \supseteq A_2 \supseteq A_3 \supseteq A_4\dots\) are all finite, nonempty sets of real numbers, then the intersection \(\bigcap_{n=1}^{\infty}A_n\) is finite and nonempty.
(c) \(A \cap (B \cup C)\) = \((A \cap B) \cup C\)
(d) \(A \cap (B \cap C)\) = \((A \cap B) \cap C\)
(e) \(A \cap (B \cup C)\) = \((A \cap B) \cup (A \cap C)\)

---

(a)
不一定对

考虑 \(A_i = \{x, x\ge i\}\)，那么我们可以证明对任意数字 \(x\)，其都不在 \(n\) 足够大\(A_n\)中，故而也不在 \(\bigcap_{n=1}^{\infty}A_n\) 中，此时最终集合是 \(\varnothing\).

对于正确的情况，我们考虑 \(A_i = \{x, x\ge i\}\cup\{x,x\le-2\}\)，那么最后的交集是\(\{x,x\le-2\}\)

(b)
找不到反例，一个很粗糙的论证是，所有的 LLM 必然包含一个相同的元素，若两个 LLM 不包含相同的元素，则不构成属于关系，和题设相悖，如果所有的 LLM 都至少包含一个相同的元素，那么\(\bigcap_{n=1}^{\infty}A_n\)毫无疑问也至少包含那个元素。

(c)
\(D=\{x,x\in C,x\notin A\}\) 

则 \(D \cap [A \cap (B \cup C)] = \varnothing\)，且 \(D \subseteq [(A \cap B) \cup C]\)

(d)
从两个方向论证，设等式左侧表示的结合为 \(D\)，右侧表示的集合为 \(E\)，那么对任意 \(x_i\in D\)，\(x_i \in A\bigcap B\bigcap C\)，反之同样成立，同理对 \(E\) 成立，说明两边表示的是同一个集合。

(e)
Venn 图想象一下就好了（John Venn 1880）