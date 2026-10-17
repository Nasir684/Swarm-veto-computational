10.5281/zenodo.23433610
# Swarm Veto — Computational Validation

Computational validation of the cross-node coincidence veto defined in the
pre-registered Swarm Veto Protocol v1.0 (Zenodo 10.5281/zenodo.23431140).
Engineering analogue, control-only: these results establish feasibility and the
operating envelope; the physical falsifiers (S1–S5) are executed on hardware
separately.

**Run:** open `swarm_veto_simulation.ipynb` → Run All. Seed 684 regenerates every
number and figure. Outputs: `results.json`, `fig1_suppression.png`,
`fig2_survival.png`.

**Key results (seed 684, N = 4, T = 7200 s/arm):** suppression 262× at Δt = 5 ms
(full-strength EMI); genuine node-local survival ≥ 99.4%; equidistant-Poisson
survival 97.8–99.6% (measured accidental loss matches the protocol's Table 1);
blind region bounded: ≤ 0.10% survival for correlated swarm-global emission;
per-node KS p = 0.58–0.89. Dead-time distortion reproduces QCID-Sigma v5.4
verified values (0.10/0.83/4.00%) — simulator anchored to hardware before any
veto claim.

**Lineage:** QCID-Sigma v5.4 → muon pre-registration v1.1 → propulsion-EMI
protocol → swarm veto protocol v1.0 → this study.

**License:** MIT / CC BY. Civilian application.
