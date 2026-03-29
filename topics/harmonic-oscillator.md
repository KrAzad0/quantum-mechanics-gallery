# 🎵 Quantum Harmonic Oscillator

## Fact Sheet

| Property | Details |
|----------|---------|
| Potential | V(x) = ½mω²x² |
| Energy levels | E_n = ℏω(n + ½), n = 0,1,2,... |
| Ground state energy | E₀ = ℏω/2 (zero-point energy) |
| Wave functions | Hermite polynomials × Gaussian |
| Importance | Basis for QFT, molecular vibrations, photons |

---

## Hamiltonian

```
Ĥ = p̂²/2m + ½mω²x̂²
```

## Ladder Operators

```
â  = √(mω/2ℏ) · (x̂ + ip̂/mω)   [annihilation / lowering]
â† = √(mω/2ℏ) · (x̂ - ip̂/mω)   [creation / raising]
```

Key relations:
```
[â, â†] = 1
Ĥ = ℏω(â†â + ½) = ℏω(N̂ + ½)
â|n⟩ = √n |n-1⟩
â†|n⟩ = √(n+1) |n+1⟩
```

## Ground State Wave Function

```
ψ₀(x) = (mω/πℏ)^{1/4} · exp(-mωx²/2ℏ)
```

---

## 📖 References
- Griffiths Ch. 2.3
- Sakurai Ch. 2.3
