# NeurisAI Research

Published research, model architectures, and curated datasets supporting the NeurisAI forensic psychology platform.

## Papers

### Behavioral Trajectory Prediction in Forensic Contexts
*Working Paper — 2026*

We present a transformer-based approach for modeling behavioral trajectories from structured forensic evidence. Our method processes temporal sequences of documented actions, environmental conditions, and psychological indicators to generate probability distributions over future behavioral states. Preliminary evaluation on anonymized case data shows a 34% improvement in predictive accuracy over baseline statistical methods commonly used in forensic risk assessment.

### 3D Crime Scene Reconstruction from Sparse Evidence
*In Preparation*

A NeRF-based pipeline optimized for forensic scene reconstruction from limited photographic evidence. The system incorporates geometric priors derived from architectural standards and physical constraints to generate metrically accurate 3D models from as few as 12 calibrated photographs.

### Adaptive Trauma Assessment via Computational Psychometrics
*In Preparation*

An adaptive testing framework that dynamically selects assessment items from validated clinical instruments (PCL-5, CAPS-5, CTQ) based on real-time response analysis. The system reduces assessment time by approximately 40% while maintaining diagnostic reliability comparable to full-length instrument administration.

## Datasets

> Datasets will be published alongside their respective papers. All data undergoes rigorous de-identification in compliance with IRB protocols and applicable privacy regulations.

| Dataset | Description | Status |
|---------|-------------|--------|
| `forensic-behavioral-sequences` | Anonymized temporal behavioral data from forensic case studies | In preparation |
| `scene-reconstruction-benchmark` | Calibrated crime scene photographs with ground-truth 3D models | In preparation |
| `trauma-assessment-responses` | Simulated adaptive assessment sessions for instrument validation | In preparation |

## Model Weights

Pre-trained model weights will be released under restricted access for verified research institutions. Contact research@neurisai.me for early access.

## Citation

If you use our work, please cite:

```bibtex
@misc{neurisai2026,
  title={NeurisAI: AI-Driven Forensic Psychology and Behavioral Analysis},
  author={NeurisAI Research Team},
  year={2026},
  url={https://github.com/KylaCoquete/neurisai-research}
}
```

## Ethics Statement

All research conducted under the NeurisAI project adheres to established ethical guidelines for AI in criminal justice and mental health contexts. We are committed to transparency, fairness, and the responsible deployment of AI systems in sensitive domains.

Our work is developed in consultation with licensed forensic psychologists, law enforcement professionals, and ethics review boards to ensure that our tools augment — rather than replace — human expert judgment.

## License

Research content: CC BY-NC 4.0
Code: MIT License

## Contact

- **Research inquiries:** research@neurisai.me
- **Website:** [neurisai.me](https://neurisai.me)
