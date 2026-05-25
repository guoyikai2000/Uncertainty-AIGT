```markdown
# On the Salience of Low-Probability Tokens for AI-Generated Text Detection: A Multiscale Uncertainty Perspective

This repository contains the implementation and datasets for evaluating **Uncertainty** and **Uncertainty++** methodologies.

---

## 📂 Project Structure
.
├── datasets/                          # Main experimental data
├── scripts/
│   ├── uncertainty_black.py           # Script to run Uncertainty
│   ├── uncertainty++_black.py         # Script to run Uncertainty++
├── Proxy_LLMs/                        # Directory for Proxy Models (User created)
└── README.md
```

---

## 🛠 Preparation

**Important:** Before running the code, you must download the proxy models and place them in the following path:
`./Proxy_LLMs/`

---

## 🚀 Running the Experiments

All execution scripts are located in the `scripts` directory. Please follow this order:

### 1. Navigate to the scripts folder

```bash
cd scripts
```

### 2. Run Uncertainty

To execute the standard Uncertainty evaluation:

```bash
python uncertainty_black.py
```

### 3. Run Uncertainty++

To execute the enhanced Uncertainty++ evaluation:

```bash
python uncertainty++_black.py
```

---

## 📚 Acknowledgements

We utilize main datasets from the **Lastde_Detector** repository. Please refer to the original source for more details:
[https://github.com/TrustMedia-zju/Lastde_Detector](https://github.com/TrustMedia-zju/Lastde_Detector)

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

```

```
