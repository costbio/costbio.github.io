---
layout: tools
title: "Tools"
permalink: /tools
tools:
  - name: "gRINN"
    icon: "fas fa-project-diagram"
    description: "A tool for calculation of residue interaction energies and protein energy network analysis of molecular dynamics simulations. gRINN calculates pairwise residue interaction energies from GROMACS MD trajectories and builds energy-based protein networks."
    features:
      - "Trajectory and ensemble analysis modes"
      - "Electrostatic and van der Waals energy calculations"
      - "Protein Energy Network (PEN) construction"
      - "Interactive web dashboard for 3D visualization"
    github: "https://github.com/osercinoglu/grinn"
    web: "https://grinn.bio-cloud.site"
    docs: "https://grinn.readthedocs.io"

  - name: "PocketHunter"
    icon: "fas fa-crosshairs"
    description: "A command-line tool for detecting and analyzing potential small molecule binding sites in protein molecular simulation trajectories. PocketHunter identifies druggable pockets including cryptic binding sites that appear during protein dynamics."
    features:
      - "Binding site detection from MD trajectories"
      - "Cryptic pocket identification"
      - "Pocket clustering across frames"
      - "Interactive residue composition heatmaps"
    github: "https://github.com/costbio/PocketHunter"

  - name: "consensus_docking"
    icon: "fas fa-compress-arrows-alt"
    description: "A molecular docking pipeline that runs multiple docking tools simultaneously and compares their results. Automates protein-ligand docking by orchestrating several docking engines with consensus analysis."
    features:
      - "Multi-tool docking (Smina, Gnina, LeDock, GOLD)"
      - "Adaptive exhaustiveness optimization"
      - "RMSD analysis across docking tools"
      - "Automated file conversions and pose extraction"
    github: "https://github.com/costbio/consensus_docking"
---

# Software Tools

Our group develops open-source software tools for computational structural biology research. All tools are freely available on GitHub.

<div class="d-flex gap-3 mb-4">
  <a href="https://github.com/costbio" class="btn btn-dark" target="_blank">
    <i class="fab fa-github me-2"></i>costbio
  </a>
  <a href="https://github.com/osercinoglu" class="btn btn-dark" target="_blank">
    <i class="fab fa-github me-2"></i>osercinoglu
  </a>
</div>

---
