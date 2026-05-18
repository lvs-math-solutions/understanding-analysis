### Exercise 1.2.1
(a) Prove that \(\sqrt{3}\) is irrational. Does a similar argument work to show \(\sqrt{6}\) is irrational?

(b) Where does the proof of Theorem 1.1.1 break down if we try to use it to prove \(\sqrt{4}\) is irrational?

---
*Proof.* 
（a）

假设 \(\sqrt{3}\) 为有理数，则存在整数 \(p,q \in \Z,(q\neq0,gcd(p,q)=1)\) 使得

\[\dfrac{p}{q} = \sqrt{3}\]

可得 \(p^2=3q^2\), 令 \(p=3k\)

可知 \[3k^2=q^2\]

假设 \(\sqrt{6}\) 为有理数，则存在整数 \(p,q \in \Z,(q\neq0,gcd(p,q)=1)\) 使得

\[\dfrac{p}{q} = \sqrt{6}\]

可得 \(p^2=6q^2\), 令 \(p=6k\)

可知 \[6k^2=q^2\]

---
（b）

假设 \(\sqrt{4}\) 为有理数，则存在整数 \(p,q \in \Z,(q\neq0,gcd(p,q)=1)\) 使得

\[\dfrac{p}{q} = \sqrt{4}\]

则仅可得出：

\[p^2=4q^2\ \Longrightarrow p \mid 2\]

> 考虑一个更特殊的情况，若 \( 12 \mid p^2\)，则只能推出 \( 6 \mid p\)

> 疑问，为什么 \( 2 \mid p^2\)，可推出 \( 2\mid p\)，在我的逻辑里面，这个是需要证明的，尽管我知道它一定是对的，可以借助标准质数分解来校验正确性，但是有没有比较优雅的证明方法呢？(本书中的论述见 Page 2)
