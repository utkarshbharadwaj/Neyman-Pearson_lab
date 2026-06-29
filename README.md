# 🧪 Neyman-Pearson Lab

**An interactive hypothesis testing instrument to derive the most powerful (MP), uniformly most powerful (UMP), and uniformly most powerful unbiased (UMPU) tests.**

The Neyman-Pearson Lab is a single-file web application that builds optimal rejection regions in real time. Powered by the Neyman-Pearson lemma, the Karlin-Rubin theorem, and unbiasedness conditions, it provides live derivations, exact mathematical test functions, and interactive visualizations.

## ✨ Features
* **Live Mathematical Derivations:** Automatically generates step-by-step proofs for the selected distribution and hypothesis pair.
* **Interactive Visualizations:** Renders SVG charts of sampling distributions, highlighting critical regions on the fly.
* **Exact Discrete Handling:** Calculates exact randomized boundary probabilities for discrete distributions to hit the target alpha perfectly.
* **Single-File Portability:** The entire application (UI, logic, and rendering) is contained within a single `neyman-pearson-lab.html` file with zero dependencies.

## 📊 Supported Distributions
* **Normal:** Mean (known variance) & Variance (known mean)
* **Exponential:** Rate
* **Poisson:** Mean
* **Binomial:** Success probability
* **Gamma:** Rate (known shape)
* **Uniform:** Upper bound
* **Lognormal:** Log-mean (known variance)
* **Beta:** Shape (beta = 1 fixed)

## 🚀 Getting Started
Because this project is entirely self-contained, there is no installation or build step required.
1. Clone the repository: `git clone https://github.com/utkarshbharadwaj/Neyman-Pearson_lab.git`
2. Open `neyman-pearson-lab.html` in your preferred modern web browser.

_Note: The application fetches [KaTeX](https://katex.org/) via CDN to render the mathematical equations, so an active internet connection is required for optimal text rendering._

## 🛠️ How to use
* **Setup your Distribution:** Select one of the 9 supported one-parameter families and input any known nuisance parameters.
* **Define the Sample:** Set your sample size ($n$).
* **Formulate Hypotheses:** Set the parameter value for the null hypothesis ($H_0$) and choose the direction of the alternative hypothesis ($H_1$).
* **Adjust Significance:** Use the slider to dial in your desired Type I error rate ($\alpha$).
* **Analyze the Results:** Watch the right-hand panel update instantly with the test classification (MP/UMP/UMPU), the derivation steps, the optimal test function $\phi(x)$, and the plotted critical region.

## 🤝 Contributing
* Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/utkarshbharadwaj/Neyman-Pearson_lab/issues) if you want to contribute.

## 📝 License
This project is open-source and available under the MIT License.
