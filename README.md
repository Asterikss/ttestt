<h1 align="center">
  <!-- <img src="https://github.com/Asterikss/ttestt/blob/visuals/RevAnalyzerImg.png?raw=true" alt="RevAnalyzer"> -->
  <img src="https://github.com/Asterikss/ttestt/blob/visuals/RevAnalyzer.png?raw=true" alt="RevAnalyzer">
</h1>

<!-- [![contributions](https://img.shields.io/badge/contributions-welcome-orange)](https://github.com/Asterikss/rev-analyzer/pulls) -->
<!-- [![Downloads](https://img.shields.io/github/downloads/neovim/neovim/total.svg?maxAge=2592001)](https://github.com/neovim/neovim/releases/) -->
<p align="center">
    <!-- <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a> -->
    <!-- <a href="#-general-machine-learning" title="Project Count"><img src="https://img.shields.io/badge/projects-100-blue.svg?color=5ac4bf"></a> -->
    <a href="https://github.com/Asterikss/rev-analyzer/pulls" title="Contributing"><img src="https://img.shields.io/badge/contributions-welcome-orange"></a>
    <!-- <a href="https://github.com/jrieke/best-of-streamlit/releases" title="Updates"><img src="https://img.shields.io/github/release-date/jrieke/best-of-streamlit?color=green&label=updated"></a> -->
</p>
<!-- [watch this repo](https://github.com/user/repository/subscription) -->
<!-- [create issue](https://github.com/user/repository/issues/new) -->

**RevAnalyzer** is a Streamlit-based app that leverages machine learning for
efficient review analysis. It's designed to provide straightforward insights
into customer feedback while enabling heavy customization of the porcess.


## Demo


## Run Locally

Clone the project

```bash
  git clone https://github.com/Asterikss/rev-analyzer.git
  cd rev-analyzer
```

Create a new environment
*  Venv
    * Linux
    ```bash
    python -m venv rev-analyzer
    source env_name/bin/activate
    ```
    * Windows

    ```bash
    python -m venv rev-analyzer
    env_name\Scripts\activate
    ```

* Conda

    ```bash
    conda create --name rev-analyzer python=3.10
    conda activate rev-analyzer
    ```

Install dependencies

```bash
  pip install -r requirements.txt
```

Run the app

```bash
  streamlit run 1_🔬_Analyzer.py
```
