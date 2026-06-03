---
layout: post
title: "New Publication: i-gRINN Web Server in Nucleic Acids Research"
date: 2026-05-27
categories: research publication software
---

We are excited to announce the publication of **i-gRINN** in *Nucleic Acids Research*, the successor to our [gRINN](https://doi.org/10.1093/nar/gky381) web server for protein energy network analysis.

### i-gRINN: a next-generation web server for protein energy network analysis of heterogeneous biomolecular systems with natural language-based data exploration

Protein energy networks (PENs) employ force-field calculations to weight residue interaction networks, enabling identification of functionally critical residues and allosteric pathways from molecular dynamics data. i-gRINN is a fully redesigned platform that resolves compatibility issues of the original tool while introducing major new capabilities:

- **Extended system support:** pairwise interaction energy calculations now encompass small molecules and non-standard residues, beyond standard amino acids.
- **Frame-by-frame analysis:** interaction energy matrices and PENs are constructed independently for each trajectory frame, preserving temporal dynamics rather than relying solely on ensemble averages.
- **LLM-powered chatbot:** natural language interrogation of results, grounded in UniProt annotations and PubMed literature through a two-stage interpretation pipeline.

The server accepts GROMACS trajectories or PDB ensembles and provides interactive visualization through dedicated panels for energetics and network metrics alongside integrated 3D structure viewing. It is freely accessible without authentication at [https://grinn.bio-cloud.site](https://grinn.bio-cloud.site).

Read the full paper [here](https://doi.org/10.1093/nar/gkag516).
