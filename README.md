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

## Estrutura do Projeto

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

## Descrição dos Componentes

### `data/`
Contém os dados utilizados nos experimentos.
⚠️ **Importante:** os dados originais não devem ser versionados.
Inclua apenas scripts para processamento e exemplos sintéticos, se necessário.

### `notebooks/`
Jupyter Notebooks contendo as análises, testes e experimentos realizados.
Organize-os por data ou tema, por exemplo:
`notebooks/2025-01-analisando-correlacoes.ipynb`

### `src/`
Scripts e módulos em Python que implementam as funcionalidades principais do projeto.
Estruture de forma modular para reuso entre notebooks.

### `models/`
Modelos treinados, checkpoints, ou artefatos resultantes do processo de aprendizado.

### `results/`
Saídas dos experimentos — gráficos, métricas, tabelas e logs.
Evite armazenar arquivos muito grandes.

---

## Configuração do Ambiente

Para configurar o ambiente virtual e instalar dependências:

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

---

## Execução dos Experimentos

Após configurar o ambiente, execute os notebooks ou scripts principais:

```bash
jupyter notebook
```

Ou diretamente via linha de comando:

```bash
python src/main.py
```

---

## Reproduzindo Resultados

Para reproduzir os experimentos principais:

```bash
# 1. Configurar ambiente
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# 2. Executar pré-processamento
python src/preprocess.py --input data/raw/ --output data/processed/

# 3. Treinar modelo
python src/train.py --config configs/exp1.yaml

# 4. Gerar resultados
python src/evaluate.py --model models/exp1.pkl --output results/
```

---

## Dependências Principais

```txt
Python >= 3.9
JupyterLab
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
```

Adicione outras conforme o projeto evolui em `requirements.txt`.

---

## Licença

This project is distributed under the [MIT](LICENSE) license.
See the `LICENSE` file for more details.

---

## Histórico de Versões

