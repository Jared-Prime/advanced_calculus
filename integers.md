Study notes for *Advanced Calculus* by Avner Friedman.

# 1.§ The Integers

## Note on Section §
The text is slightly confusing in its derivation of the rationals. Although Section 2 is titled "The Rational Numbers", its first few definitions and theorems are actually a derivation of the Integers `Z`.

Initially, I proposed this as an alternate approach to the rationals, but it turns out the author was doing just that: *Show that `0` is adequate for extending `N ⊃ Z` (`N` as a superset of `Z`). Then show that `+` and `*` still hold in `Z`. Next, remove the restriction 1.1.0(3) that `S(n) ≠ 1`. Thus `S(1) = 0`, `S(0) = -(1)`, `S(-(1)) = -(2)`, etc.*

## 1.§.0.0 Definitions
- negative numbers:
	- for each `n ∈ N`, there is a corresponding `-(n) ∈ R`, called the "negative" of `n`
- zero:
	- `0`, which is also it's own negative

## 1.§.0.1 Subtraction
Defined in terms of addition, subtraction shows:
- sum with negative is zero
	- `n = m ⊨ -(n) + m = 0`
- `n = m + x ⊨ -(n) + m = -(x)`
- `m = n + y ⊨ -(n) + m = y`

By the Trichotomy Law (Theorem 1.1.3), one and only one of the cases above is `true`.

## 1.§.0.2 Multiplication
- product of even and odd is odd
	- `m * -(n) = -(m * n)`
	- note the commutitive property holds
		- eg. `m * -(n) = -(n) * m = -(m * n)`
- product of odd and odd is even
	- `-(m) * -(n) = m * n`
	- note the commutivite property holds
- product with zero is zero
	- `-(n) * 0 = 0`
	- `m * 0 = 0`
	
## 1.§.1.0 (Theorem Statement)
For any integer `m, n, k ∈ Z`, Theorem 1.1.2 holds.

## 1.§.1.1 (Lemma Statement)
For any fixed integer `a, b ∈ Z` and some integer `x ∈ Z`, the equation `a + x = b` has a unique solution for `x`.

## 1.§.1.2 (Corralary)
*This may not be a *true* corralary.*
- "equal with"
	- `x = 0 ⊨ a = b`
- "larger than"
	- `x ∈ Z- ⊨ a > b`
- "smaller than"	
	- `x ∈ Z+ ⊨ a < b`