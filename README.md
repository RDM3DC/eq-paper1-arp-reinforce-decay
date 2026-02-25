# Generic ARP Reinforce/Decay Law

**ID:** `eq-paper1-arp-reinforce-decay`  
**Tier:** derived  
**Score:** 93  
**Units:** OK  
**Theory:** PASS  

## Equation

$$
\dot{G}=\alpha\,\mathcal{A}(\phi,G)-\mu\,(G-G_0)
$$

## Description

Conductance/coupling G increases with activity A(φ,G) at gain α, and relaxes toward baseline G₀ at rate μ. The workhorse ARP law in its most general continuous-time form.

## Assumptions

- Activity functional A(φ,G) ≥ 0 (non-negative reinforcement).
- Single relaxation timescale μ⁻¹ dominates.
- G₀ > 0 is a stable equilibrium baseline.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

## Contributing

You can add images, derivations, simulations, data, or notes to this repo:

| Folder | What goes here |
|--------|---------------|
| `images/` | Plots, diagrams, phase portraits, animations (.png, .jpg, .mp4, ...) |
| `derivations/` | Step-by-step derivations and proofs (.tex, .md, .pdf) |
| `simulations/` | Computational models and code (.py, .ipynb, .jl, .m) |
| `data/` | Numerical results, experimental measurements (.csv, .hdf5, .npy) |
| `notes/` | Research notes, lit reviews, references (.md, .bib, .txt) |
| `docs/` | Formal documents, validation plans (.md, .pdf) |

**Three ways to contribute:**
1. **GitHub Issue** — click [New Issue](../../issues/new?template=artifact_submission.yml) and attach your file
2. **Pull Request** — fork, add files, open a PR
3. **CLI** — `python tools/push_to_equation_repo.py --equation-id eq-paper1-arp-reinforce-decay --file <path> --folder <folder>`

All submissions are content-moderated. See the [full contributing guide](https://github.com/RDM3DC/TopEquations/blob/main/CONTRIBUTING.md).
