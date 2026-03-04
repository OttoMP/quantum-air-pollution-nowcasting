# An Annealing-based Quantum Neural Network with Discrete Wavelet Transforms for Enhanced Air Pollution Nowcasting

> **Abstract:** Air pollution poses a significant threat to public health, exacerbated by the rapid industrialization and urbanization of modern society.
While traditional deep learning offers predictive capabilities, recent advancements in quantum machine learning (QML) present a compelling alternative.
Here, we introduce a scalable hybrid framework that integrates variational quantum circuits with quantum annealing. Leveraging a neuromorphic quantum computing platform to transcend the qubit limitations of the NISQ era, we model particulate matter (PM$_{2.5}$) dynamics using high-density urban data from the UK.
We demonstrate that our Quantum Neural Networks (QNNs) exhibit an intrinsic resilience to input volatility, significantly outperforming classical baselines (MLP and LSTM) on raw, high-entropy environmental data.
Furthermore, we successfully scaled the model to 172 qubits, observing a synergistic enhancement when coupled with wavelet decomposition that achieves state-of-the-art predictive fidelity.
These findings establish a critical benchmark for quantum utility, proving that scalable, neuromorphic quantum machine learning can now address complex, non-linear real-world problems.

---

## Authors

| Nome | Contato |
|------|----------|
| Otto Menegasso Pires | otto.pires@fieb.org.br |
| André Saimon | andre.sousa@fbter.org.br |
| Samer Rahmeh | sam@dynex.co |
| Prashant Kumar | p.kumar@surrey.ac.uk |
| Marcelo Moret | mamoret@gmail.com |
| Erick Giovani Sperandio Nascimento | erick.sperandio@surrey.ac.uk |


---

## Dataset Description

### Raw Data (`data/`)
Contém os dados utilizados nos experimentos.

### Wavelets Data (`data/`)


---

## Key Findings

1. **Finding:**
  - a
2. **Finding:**
  - b

---

## Scripts Overview

- **`file.py`**: Implements classical neural network architectures for nowcasting
- **`notebook.ipynb`**: Generates the statistical analysis
---

## Repository Structure

```bash
├── data/              # Dados brutos e processados (não versionados)
├── notebooks/         # Jupyter notebooks com análises e experimentos
├── src/               # Códigos-fonte e funções utilitárias
├── models/            # Modelos treinados ou artefatos
├── results/           # Saídas e resultados experimentais
├── requirements.txt   # Dependências do projeto
└── README.md          # Documentação principal
```

---

## Citation

If you use this code or data in your research, please cite: 

```bibtex
@article{article,
  title={Title},
  author={names},
  journal={journal},
  year={2026}
}
```
---

