# SC-004 Work ↔ Gallery Guide

- Public Gallery: `https://c3right.github.io/text2pic-review-gallery/lab/sc004/`
- Optimization revision: `a338e9b1d474c18a02b9c048b3927d1ad9ac60fc`
- Post-P5 prompt-regression revision: `43b761e5181bebeef4b40221203f4a5e7f17b0b3`
- Public layer: derived review assets only

## P0

P0 was zero-image preflight. Historical North Star: [G21/W](https://c3right.github.io/text2pic-review-gallery/groups/007/G06W/) and [G22/H](https://c3right.github.io/text2pic-review-gallery/groups/007/G06H/).

## Phase map

| Phase | Images | Work | Variable | Decision |
|---|---:|---|---|---|
| [P1](stages/p1/) | 48 | `SC-004` | native vs U1 vs U2 | U2 became the experimental palette baseline. |
| [P2](stages/p2/) | 40 | `SC-004` | fixed U2 across T01–T10 | Problem map only: 28 acceptable, 7 near-pass, 5 failures. |
| [P2C](stages/p2c/) | 16 | `SC-004` | legacy-v2 adapted vs current Skill | Directional evidence; no prompt-system winner. |
| [P2C_TASK_MAPPING_CORRECTION](stages/p2c-task-mapping-correction/) | 0 | `SC-004` | corrected LYNK4 input | Two provider calls returned no image; no replacement. |
| [P2C_TASK_MAPPING_CORRECTION_SANITIZED](stages/p2c-task-mapping-correction-sanitized/) | 2 | `SC-004` | corrected LYNK4 input | Two corrected G21/G22 outputs passed semantic review. |
| [P3](stages/p3/) | 48 | `SC-004` | B vs G1 vs G2 | Directional only; no broad adopted package. |
| [P3F](stages/p3f/) | 16 | `SC-004` | narrative/analytical × warm/cool | Exposed wash, weak separation and insufficient functional contrast. |
| [P3PA](stages/p3pa/) | 15 | `SC-004-P3PA-ADOPTION` | role-bound-functional-palette-v1 | Adopted after human preference and cross-model regression. |
| [P4](stages/p4/) | 48 | `SC-004-P4-VIDEO-SAFE-OCCUPANCY` | video-safe-canvas-occupancy-v1 | Rejected / no Skill change. |
| [P5](stages/p5/) | 32 | `SC-004-P5-TEXT-SPECIAL-CONSTRAINTS` | exact-text-and-special-constraint-v1 | Rejected / no Skill change. |

## Post-P5 prompt-only diagnostic

`PROMPT-LEGACY-CURRENT-REGRESSION-001` generated no images. It found that the current Skill can recover legacy topology under complete D0→D3 execution, but generalizing the fixed four-type skeleton lowered the weak/incomplete execution floor. Test type-to-topology conservation before a broad image wave.
