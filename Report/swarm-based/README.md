
============================================================
GROUP: swarm_based  (2 algorithms)
============================================================

  F1 Sphere (20D)
  --------------------------------------------------

[Agent] F1 Sphere – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Case 1: Easy separable unimodal (F1, F2, F5)
        adapt_interval increased: 20 → 40
        convergence_tol = 1e-10 (strict)
    Final: adapt_interval = 40, convergence_tol = 1e-10


    --- Per-generation data for PSO on F1 Sphere ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    PSO           agent=  0.000000  base=  0.000000  gens=5000  adapt=111

[Agent] F1 Sphere – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Case 1: Easy separable unimodal (F1, F2, F5)
        adapt_interval increased: 20 → 40
        convergence_tol = 1e-10 (strict)
    Final: adapt_interval = 40, convergence_tol = 1e-10


    --- Per-generation data for ABC on F1 Sphere ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=161

  F2 Ellipsoidal (20D)
  --------------------------------------------------

[Agent] F2 Ellipsoidal – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Case 1: Easy separable unimodal (F1, F2, F5)
        adapt_interval increased: 20 → 40
        convergence_tol = 1e-10 (strict)
    Final: adapt_interval = 40, convergence_tol = 1e-10


    --- Per-generation data for PSO on F2 Ellipsoidal ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |   439.772283
    PSO           agent=  0.000000  base=439.772283  gens=3299  adapt=104

[Agent] F2 Ellipsoidal – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Case 1: Easy separable unimodal (F1, F2, F5)
        adapt_interval increased: 20 → 40
        convergence_tol = 1e-10 (strict)
    Final: adapt_interval = 40, convergence_tol = 1e-10


    --- Per-generation data for ABC on F2 Ellipsoidal ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=162

  F3 Rastrigin (20D)
  --------------------------------------------------

[Agent] F3 Rastrigin – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Special: Separable multimodal (F3, F4) – treat as adequate multimodal
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F3 Rastrigin ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    49.955817 |    49.747822
    PSO           agent= 19.932736  base= 49.747822  gens= 219  adapt=106

[Agent] F3 Rastrigin – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Special: Separable multimodal (F3, F4) – treat as adequate multimodal
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F3 Rastrigin ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=348

  F4 Bueche-Rastrigin (20D)
  --------------------------------------------------

[Agent] F4 Bueche-Rastrigin – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Special: Separable multimodal (F3, F4) – treat as adequate multimodal
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F4 Bueche-Rastrigin ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    49.955817 |    49.747822
    PSO           agent= 19.932736  base= 49.747822  gens= 219  adapt=106

[Agent] F4 Bueche-Rastrigin – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Special: Separable multimodal (F3, F4) – treat as adequate multimodal
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F4 Bueche-Rastrigin ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=348

  F5 Linear Slope (20D)
  --------------------------------------------------

[Agent] F5 Linear Slope – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Case 1: Easy separable unimodal (F1, F2, F5)
        adapt_interval increased: 20 → 40
        convergence_tol = 1e-10 (strict)
    Final: adapt_interval = 40, convergence_tol = 1e-10


    --- Per-generation data for PSO on F5 Linear Slope ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    PSO           agent=  0.000000  base=  0.000000  gens=  99  adapt=132

[Agent] F5 Linear Slope – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.90  (raw: separable)
    adapt_interval before tuning = 20
    → Case 1: Easy separable unimodal (F1, F2, F5)
        adapt_interval increased: 20 → 40
        convergence_tol = 1e-10 (strict)
    Final: adapt_interval = 40, convergence_tol = 1e-10


    --- Per-generation data for ABC on F5 Linear Slope ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=174

  F6 Attractive Sector (20D)
  --------------------------------------------------

[Agent] F6 Attractive Sector – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F6 Attractive Sector ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    PSO           agent=  0.000000  base=  0.000000  gens=5000  adapt=223

[Agent] F6 Attractive Sector – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F6 Attractive Sector ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=332

  F7 Step Ellipsoidal (20D)
  --------------------------------------------------

[Agent] F7 Step Ellipsoidal – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F7 Step Ellipsoidal ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     6.097100 |     0.000000
    PSO           agent=  0.000000  base=  0.000000  gens= 219  adapt=149

[Agent] F7 Step Ellipsoidal – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F7 Step Ellipsoidal ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=  19  adapt=348

  F8 Rosenbrock (20D)
  --------------------------------------------------

[Agent] F8 Rosenbrock – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F8 Rosenbrock ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |   107.191833 |     0.212010
    PSO           agent=  5.942824  base=  0.212010  gens=  19  adapt= 47

[Agent] F8 Rosenbrock – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F8 Rosenbrock ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.049122 |     0.000532
    ABC           agent=  0.049122  base=  0.000532  gens= 799  adapt=178

  F9 Rosenbrock Rotated (20D)
  --------------------------------------------------

[Agent] F9 Rosenbrock Rotated – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F9 Rosenbrock Rotated ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    95.514374 |     5.020480
    PSO           agent=  9.558213  base=  5.020480  gens= 139  adapt= 42

[Agent] F9 Rosenbrock Rotated – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F9 Rosenbrock Rotated ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     7.511610 |     7.396037
    ABC           agent=  7.511610  base=  7.396037  gens=5000  adapt= 23

  F10 Ellipsoidal Rotated (20D)
  --------------------------------------------------

[Agent] F10 Ellipsoidal Rotated – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F10 Ellipsoidal Rotated ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 | 24731.720639 |  2936.801452
    PSO           agent=672.413241  base=2936.801452  gens=  19  adapt= 37

[Agent] F10 Ellipsoidal Rotated – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F10 Ellipsoidal Rotated ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |  3415.972320 |  3362.226896
    ABC           agent=3415.972320  base=3362.226896  gens=5000  adapt= 18

  F11 Discus (20D)
  --------------------------------------------------

[Agent] F11 Discus – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F11 Discus ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     7.296138 |     0.086244
    PSO           agent=  1.741345  base=  0.086244  gens=1379  adapt= 57

[Agent] F11 Discus – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F11 Discus ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    45.783070 |    45.829383
    ABC           agent= 45.783070  base= 45.829383  gens=  19  adapt= 85

  F12 Bent Cigar (20D)
  --------------------------------------------------

[Agent] F12 Bent Cigar – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F12 Bent Cigar ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 | 13623.854488 |     4.336125
    PSO           agent=  0.860336  base=  4.336125  gens=  39  adapt= 73

[Agent] F12 Bent Cigar – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F12 Bent Cigar ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.038545 |     0.037755
    ABC           agent=  0.038545  base=  0.037755  gens=  19  adapt=303

  F13 Sharp Ridge (20D)
  --------------------------------------------------

[Agent] F13 Sharp Ridge – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F13 Sharp Ridge ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |   251.328386 |     5.739391
    PSO           agent=  0.322180  base=  5.739391  gens=  19  adapt= 74

[Agent] F13 Sharp Ridge – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F13 Sharp Ridge ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.394308 |     0.061689
    ABC           agent=  0.394308  base=  0.061689  gens=  19  adapt=285

  F14 Different Powers (20D)
  --------------------------------------------------

[Agent] F14 Different Powers – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for PSO on F14 Different Powers ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.504448 |     0.000000
    PSO           agent=  0.000000  base=  0.000000  gens=  39  adapt=157

[Agent] F14 Different Powers – using direct properties (preferred)
    modality     = unimodal
    ruggedness   = 0.20  (raw: smooth)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Default case (no specific match) – using default values
        adapt_interval = 20
        convergence_tol = 1e-09
    Final: adapt_interval = 20, convergence_tol = 1e-09


    --- Per-generation data for ABC on F14 Different Powers ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.000000 |     0.000000
    ABC           agent=  0.000000  base=  0.000000  gens=5000  adapt= 20

  F15 Rastrigin Rotated (20D)
  --------------------------------------------------

[Agent] F15 Rastrigin Rotated – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F15 Rastrigin Rotated ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |   129.863983 |    45.768011
    PSO           agent= 28.886594  base= 45.768011  gens=  19  adapt= 79

[Agent] F15 Rastrigin Rotated – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F15 Rastrigin Rotated ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |   141.298389 |    98.501264
    ABC           agent=141.298389  base= 98.501264  gens=  19  adapt=188

  F16 Weierstrass (20D)
  --------------------------------------------------

[Agent] F16 Weierstrass – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for PSO on F16 Weierstrass ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     5.824356 |     1.008478
    PSO           agent=  1.008478  base=  1.008478  gens=  39  adapt= 98

[Agent] F16 Weierstrass – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for ABC on F16 Weierstrass ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     4.261252 |     4.237956
    ABC           agent=  4.261252  base=  4.237956  gens=  19  adapt=306

  F17 Schaffers F7 (20D)
  --------------------------------------------------

[Agent] F17 Schaffers F7 – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F17 Schaffers F7 ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     2.572000 |     0.823733
    PSO           agent=  0.321431  base=  0.823733  gens= 359  adapt=102

[Agent] F17 Schaffers F7 – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F17 Schaffers F7 ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     3.651578 |     3.652287
    ABC           agent=  3.651578  base=  3.652287  gens=  19  adapt=168

  F18 Schaffers F7 Ill (20D)
  --------------------------------------------------

[Agent] F18 Schaffers F7 Ill – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F18 Schaffers F7 Ill ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     2.347965 |     2.192283
    PSO           agent=  2.197653  base=  2.192283  gens=  99  adapt= 68

[Agent] F18 Schaffers F7 Ill – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F18 Schaffers F7 Ill ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    10.312764 |    10.317428
    ABC           agent= 10.312764  base= 10.317428  gens= 359  adapt= 24

  F19 Griewank-Rosenbrock (20D)
  --------------------------------------------------

[Agent] F19 Griewank-Rosenbrock – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F19 Griewank-Rosenbrock ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     7.592069 |     3.397908
    PSO           agent=  1.810897  base=  3.397908  gens=  19  adapt= 43

[Agent] F19 Griewank-Rosenbrock – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F19 Griewank-Rosenbrock ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     4.131841 |     4.034750
    ABC           agent=  4.131841  base=  4.034750  gens= 139  adapt=195

  F20 Schwefel (20D)
  --------------------------------------------------

[Agent] F20 Schwefel – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for PSO on F20 Schwefel ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 | -5693.315209 | -4752.991876
    PSO           agent=-5693.315209  base=-4752.991876  gens=5000  adapt=158

[Agent] F20 Schwefel – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for ABC on F20 Schwefel ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 | -9057.465346 | -9057.465346
    ABC           agent=-9057.465346  base=-9057.465346  gens=5000  adapt=346

  F21 Gallagher 101 (20D)
  --------------------------------------------------

[Agent] F21 Gallagher 101 – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F21 Gallagher 101 ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    86.565401 |    86.565401
    PSO           agent= 86.565401  base= 86.565401  gens=  19  adapt=348

[Agent] F21 Gallagher 101 – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F21 Gallagher 101 ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    86.565401 |    86.565401
    ABC           agent= 86.565401  base= 86.565401  gens=  19  adapt=348

  F22 Gallagher 21 (20D)
  --------------------------------------------------

[Agent] F22 Gallagher 21 – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for PSO on F22 Gallagher 21 ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    86.565401 |    86.565401
    PSO           agent= 86.565401  base= 86.565401  gens=  19  adapt=348

[Agent] F22 Gallagher 21 – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.50  (raw: moderate)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 4: Multimodal, adequate global structure (F15–F19)
        adapt_interval decreased: 20 → 10
        convergence_tol = 1e-8 (looser)
    Final: adapt_interval = 10, convergence_tol = 1e-08


    --- Per-generation data for ABC on F22 Gallagher 21 ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    86.565401 |    86.565401
    ABC           agent= 86.565401  base= 86.565401  gens=  19  adapt=348

  F23 Katsuura (20D)
  --------------------------------------------------

[Agent] F23 Katsuura – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for PSO on F23 Katsuura ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     0.987899 |     0.871325
    PSO           agent=  0.704038  base=  0.871325  gens= 219  adapt= 95

[Agent] F23 Katsuura – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for ABC on F23 Katsuura ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |     1.088831 |     1.090958
    ABC           agent=  1.088831  base=  1.090958  gens=  19  adapt=310

  F24 Lunacek bi-Rastrigin (20D)
  --------------------------------------------------

[Agent] F24 Lunacek bi-Rastrigin – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for PSO on F24 Lunacek bi-Rastrigin ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |    55.237257 |    57.345851
    PSO           agent= 55.237257  base= 57.345851  gens= 899  adapt= 42

[Agent] F24 Lunacek bi-Rastrigin – using direct properties (preferred)
    modality     = high_multimodal
    ruggedness   = 0.80  (raw: rugged)
    separability = 0.10  (raw: non_separable)
    adapt_interval before tuning = 20
    → Case 5: Multimodal, weak global structure (very hard) (F20–F24)
        adapt_interval decreased aggressively: 20 → 5
        convergence_tol = 1e-6 (very loose, avoid early stop)
    Final: adapt_interval = 5, convergence_tol = 1e-06


    --- Per-generation data for ABC on F24 Lunacek bi-Rastrigin ---
     Gen |   Agent best | Baseline best
    ---- | ------------ | ------------
    5000 |   120.638843 |   120.626818
    ABC           agent=120.638843  base=120.626818  gens=  19  adapt=197

============================================================
SUMMARY — swarm_based
Problem                 PSO         ABC
---------------------------------------
F1 Sphere          0.000000    0.000000
F2 Ellipsoidal     0.000000    0.000000
F3 Rastrigin      19.932736    0.000000
F4 Bueche-Rastrigin   19.932736    0.000000
F5 Linear Slope    0.000000    0.000000
F6 Attractive Sector    0.000000    0.000000
F7 Step Ellipsoidal    0.000000    0.000000
F8 Rosenbrock      5.942824    0.049122
F9 Rosenbrock Rotated    9.558213    7.511610
F10 Ellipsoidal Rotated  672.413241 3415.972320
F11 Discus         1.741345   45.783070
F12 Bent Cigar     0.860336    0.038545
F13 Sharp Ridge    0.322180    0.394308
F14 Different Powers    0.000000    0.000000
F15 Rastrigin Rotated   28.886594  141.298389
F16 Weierstrass    1.008478    4.261252
F17 Schaffers F7    0.321431    3.651578
F18 Schaffers F7 Ill    2.197653   10.312764
F19 Griewank-Rosenbrock    1.810897    4.131841
F20 Schwefel    -5693.315209 -9057.465346
F21 Gallagher 101   86.565401   86.565401
F22 Gallagher 21   86.565401   86.565401
F23 Katsuura       0.704038    1.088831
F24 Lunacek bi-Rastrigin   55.237257  120.638843
  Plot saved -> comparison_swarm_based.png

Done — compared 2 algorithms in 'swarm_based' across 24 problem(s).

============================================================
Generating comparative report -> comparison_report.html
============================================================
  Report saved -> comparison_report.html
