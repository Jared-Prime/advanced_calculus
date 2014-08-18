Study notes for *Advanced Calculus* by Avner Friedman.

# 1.1 The Natural Numbers
Let `N` designate the natural numbers. Let `∈` stand for the predicate "is a", eg. `1 ∈ N` means "one is a natural number"

## 1.1.0 Peano Axioms

1. `1` is a natural number
	- `1 ∈ N`
2. To every natural number, there is a unique natural number called a successor.
	- `n ∈ N ⊨ s ∈ N`
	- call `S(n)` the successor function that uniquely determines `n`'s successor
3. `1` is not the successor of any other `n ∈ N`
	- `S(n) ≠ 1`
4. If two natural numbers have the same successor, they are equal.
	- `S(a) = S(b) ⊨ a = b`
5. Let `M` be a subset of `N` such that
	a. `1` is in the subset `M`
		- `1 ∈ M`
	b. If `n` is in the subset `M`, then it's successor is also in the subset `M`.
		- `n ∈ M ⊨ S(n) ∈ M`
	c. Then `M` coincides with all `N`
		- `M = N`

Axiom 5 is the "principle of mathematical induction".

## 1.1.1.1 (Theorem Statement)
There exists unique operations `+` and `*` with the following properties:

a. addition property
	- `S(n) = n + 1`
	- `n + S(m) = S(n + m)`
b. multiplication property
	- `n * 1 = n`
	- `n * S(m) = n * m + n`

## 1.1.1.2 (Theorem Proof)

## 1.1.1.3 Note: Order of Operations
We can define multiplication in terms of addition. Precisely because we can do this, multiplication has logical precedence over addition; we need to expand its notation into its component parts in order to evaluate it.

## 1.1.2 (Theorem Statement)
The following properties are true for `m, n, k ∈ N`:
- communitive laws
	- `m + n = n + m`
	- `m * n = n * m`
- associative laws
	- `(m + n) + k = m + (n + k)`
	- `(m * n) * k = m * (n * k)`
- distributive laws
	- `m * (n + k) = m * n + m * k`

## 1.1.2 (Theorem Proof)

***Exercise:** Derive Theorem 1.1.2 by induction from Theorem 1.1.1(a) and Theorem 1.1.1(b)*

## 1.1.3 Trichotomy Law (Theorem Statemet)
Given any `n, m ∈ N`, one and only one of the following occurs:

- `m` and `n` are equal
	- `m = n`
- `m` is larger than `n`
	- `m = n + x` where `x ∈ N`
	- `m > n`
- `m` is less than `n`
	- `n = m + y` where `y ∈ N`
	- `m < n`