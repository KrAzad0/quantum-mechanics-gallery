# 🌊 Wave Functions

## Fact Sheet

| Property | Details |
|----------|---------|
| Symbol | ψ(x, t) or \|ψ⟩ |
| Space | Complex Hilbert space L²(ℝ) |
| Normalization | ∫\|ψ\|² dx = 1 |
| Introduced by | Erwin Schrödinger (1926) |
| Physical meaning | Probability amplitude |

---

## Definition

A **wave function** ψ(x, t) is a complex-valued function that encodes all information about a quantum system. The probability of finding a particle between x and x+dx is:

```
P(x, t) = |ψ(x, t)|² dx
```

## Dirac (Bra-Ket) Notation

- **Ket**: |ψ⟩ — state vector in Hilbert space
- **Bra**: ⟨ψ| — dual vector (complex conjugate)
- **Inner product**: ⟨φ|ψ⟩ = ∫ φ*(x) ψ(x) dx

## Normalization Condition

```
⟨ψ|ψ⟩ = ∫_{-∞}^{∞} |ψ(x,t)|² dx = 1
```

## Superposition Principle

If |ψ₁⟩ and |ψ₂⟩ are valid states, then any linear combination:
```
|ψ⟩ = α|ψ₁⟩ + β|ψ₂⟩
```
is also a valid state (α, β ∈ ℂ).

## Collapse Postulate

Upon measurement, the wave function **collapses** to an eigenstate of the measured observable.

---

## 📖 References
- Griffiths Ch. 1
- Sakurai Ch. 1
- [arXiv: quant-ph](https://arxiv.org/list/quant-ph/recent)
