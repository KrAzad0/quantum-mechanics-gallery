# 🔗 Quantum Entanglement & Bell States

## Fact Sheet

| Property | Details |
|----------|---------|
| Concept introduced | Einstein, Podolsky, Rosen (1935) — EPR paradox |
| Bell inequalities | John Bell (1964) |
| Experimentally verified | Aspect et al. (1982), Hensen et al. (2015) |
| Applications | Quantum cryptography, Quantum teleportation, QKD |

---

## What is Entanglement?

A bipartite state |ψ⟩ ∈ H_A ⊗ H_B is **entangled** if it **cannot** be written as a product state:
```
|ψ⟩ ≠ |φ⟩_A ⊗ |χ⟩_B
```

## The Four Bell States (Maximally Entangled)

```
|Φ⁺⟩ = 1/√2 (|00⟩ + |11⟩)
|Φ⁻⟩ = 1/√2 (|00⟩ - |11⟩)
|Ψ⁺⟩ = 1/√2 (|01⟩ + |10⟩)
|Ψ⁻⟩ = 1/√2 (|01⟩ - |10⟩)
```

## CHSH Bell Inequality

Classical hidden variable theories predict:
```
|S| = |E(a,b) - E(a,b') + E(a',b) + E(a',b')| ≤ 2
```

Quantum mechanics predicts violations up to **2√2 ≈ 2.828** (Tsirelson bound).

---

## 📖 References
- Einstein, Podolsky, Rosen (1935). Phys. Rev. 47, 777.
- Bell, J.S. (1964). Physics 1(3), 195-200.
- Aspect, A. et al. (1982). Phys. Rev. Lett. 49, 91.
