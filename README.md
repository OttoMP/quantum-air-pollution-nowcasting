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

The dataset was sourced from the iSCAPE (Improving the Smart Control of Air Pollution in Europe) project public platform. Data were collected from two Living Lab Stations situated in Guildford, UK, a region characterized by significant vehicle-induced pollution. The monitoring stations, Sutherland Memorial Park (DS\_TS\_099; June--October 2019) and Stoke Park (DS\_TS\_103; February--September 2019), provided hourly open-road measurements. The primary feature space comprised concentrations of key pollutants (PM$_{2.5}$, CO, NO$_2$, O$_3$) alongside critical atmospheric variables (air temperature, relative humidity, and atmospheric pressure).

---

## Repository Structure

```bash
├── analysis/          # Loss values, Predictive Intervals and Performance Metrics of our models.
├── data/              # Available preprocessed datasets used in the experiments
├── notebooks/         # Jupyter notebooks containing the statistical analysis of our results
├── plots/             # Plotted graphs using Matplotlib
├── requirements.txt   # Project Dependencies
└── README.md          # Main documentation
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

