# A Hybrid Quantum-Classical Framework for Accelerating the Discovery of High-Performance Energy Materials

**IIM ATM 2025 Poster Presentation**

## Overview

This project presents a novel, scalable pipeline that seamlessly integrates machine learning, classical density functional theory (DFT), and quantum computation (VQE) to provide chemically accurate predictions of NMC intercalation voltage. This framework aims to accelerate the discovery of high-performance energy materials, specifically addressing the cathode design crisis in Li-ion batteries.

## Authors

*   **Kovuru Hemamruth** (First Author) - Dept. of Computer Science & Engineering
*   **Harsh Deep** (Co-Author) - Dept. of Electronics & Communication Engineering
*   **M John Silvister Raju** (Co-Author) - Dept. of Mechanical & Automobile Engineering

**Affiliation:** School of Engineering & Technology, Christ University, Bangalore

## Key Features

*   **Hybrid Pipeline:** Combines ML screening (XGBoost), Classical DFT, and Quantum VQE.
*   **Quantum Correction:** Systematically corrects DFT correlation errors using a VQE ansatz with Hadamard and CNOT gates.
*   **Performance:** Achieved a systematic voltage correction of |ΔV| ~0.11 V and a 10x-100x computational speedup via ML pre-filtering.

## Deployment

This project is a static website designed for deployment on Vercel.

### Vercel Deployment

1.  Push this repository to GitHub.
2.  Import the project into Vercel.
3.  Vercel will automatically detect the static site configuration.
4.  Deploy!

The `vercel.json` file is included for configuration:
```json
{
  "cleanUrls": true
}
```

## Acknowledgement

Centre of Excellence, Frontier Materials Research, CHRIST (Deemed to be University), Bengaluru, Kengeri.
