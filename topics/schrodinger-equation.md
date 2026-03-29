# 🔷 Schrödinger Equation

## Fact Sheet

| Property | Details |
|----------|---------|
| Formulated by | Erwin Schrödinger (1926) |
| Type | Partial Differential Equation |
| Domain | Non-relativistic quantum mechanics |
| Relativistic generalization | Dirac equation / Klein-Gordon equation |

---

## Time-Dependent Schrödinger Equation (TDSE)

```
iℏ ∂ψ/∂t = Ĥ ψ
```

Where:
- ℏ = h/2π (reduced Planck constant)
- Ĥ = Hamiltonian operator = T̂ + V̂ (kinetic + potential)
- ψ = ψ(x, t) wave function

In 1D with V(x,t):
```
iℏ ∂ψ/∂t = -ℏ²/2m · ∂²ψ/∂x² + V(x,t)ψ
```

## Time-Independent Schrödinger Equation (TISE)

For stationary states (time-separable solutions ψ(x,t) = φ(x)·e^{-iEt/ℏ}):
```
Ĥ φ = E φ
```

In 1D:
```
-ℏ²/2m · d²φ/dx² + V(x)φ = E φ
```

## Solutions for Common Potentials

| Potential V(x) | Solution Type |
|----------------|---------------|
| V = 0 (free particle) | Plane waves e^{ikx} |
| Infinite square well | Sinusoidal standing waves |
| Harmonic oscillator | Hermite polynomials × Gaussian |
| Hydrogen atom | Laguerre × Legendre polynomials |

---

## 📖 References
- Griffiths Ch. 2
- Sakurai Ch. 2
- Original paper: Schrödinger, E. (1926). Ann. Phys.
