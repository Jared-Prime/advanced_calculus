# Exercises: The Naturals

1. If n > m, then n + k > m + k.

	Take `n, m, k ∈ N` and `n > m`. The smallest `k ∈ N` is `1`. By definition of `S(n)`, `S(n) = n + 1` and `S(m) = m + 1`. Substituting, we get `n > m ⊨ S(n) > S(m)`. Q.E.D.

2. If n > m, m > k, then n > k.
	Take `n, m, k ∈ N`, `n > m`, and `m > k`. Let `S(n) = m` and `S(m) = k`, or in other words `m` is allowed to be the smallest successor to `n` and the largest predecessor to `k`. By composition, `S(S(n)) = k` or `k = n + 2`. Therefore `n > k`.
	
3. If n + k ≦ m + k, then n ≦ m.

	Take `n, m, k ∈ N` and `n < m`. The smallest `k ∈ N` is `1`. By the Trichotemy law, there are three possibilities for the pair of functions `S(n)` and `S(m)`.
		- `S(n) > S(m)`
		- `S(n) < S(m)`
		- `S(n) = S(m)`
	Let the first of these be `false`. Then, the Peano Axioms show either `n < m` or `n = m` is `true`.

4. (n + 1) 2 = n2 + 2n + 1, where n2 = n · n.

5. (n + 1) 3 = n3 + 3n2 + 3n + 1, where n3 = n2 · n.

6. Prove the associative law (m + n) + k = m + (n + k), by induction on k.

7. Prove the distributive law (m + n) k = mk + nk, by induction on n.

8. If m > n, then mk > nk. Conversely, if mk > nk, then m > n. 