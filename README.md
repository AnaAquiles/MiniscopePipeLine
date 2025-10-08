### 🎯 Overview  
Welcome to the **Miniscope Pipeline** — a toolkit designed to bridge the gap between **INSCOPIX** data formats and **custom miniscope analysis**.  

This repository provides:  
- 🧩 **Conversion tools** to transform `.isxd` files (from **INSCOPIX** software) into `.tiff` format.  
- ⚙️ **A preprocessing pipeline** optimized for data acquired using the **miniscope** with a **7.4 mm GRIN lens**.
- 
  Get started by following these [step-by-step](https://hackmd.io/@aaquiles/StepByStep-MiniscopePP) instructions to launch your mamba environment.

Whether you’re exploring neural dynamics, preprocessing calcium imaging data, or preparing datasets for CNMF-E or Suite2p, this pipeline helps you get your data ready — clean, structured, and analysis-ready.  

---

### 💡 Inspiration & Acknowledgements  
This work builds upon tools developed by **INSCOPIX**.  
Some core functions and logic have been adapted from their **Data Processing API**.  

👉 For deeper insights, visit the official repository:  
[INSCOPIX pyisx on GitHub](https://github.com/inscopix/pyisx)

---

### 🧰 Features at a Glance  
- 🔄 Convert `.isxd` → `.tiff` with ease  
- 🧽 Apply customizable preprocessing steps (motion correction, normalization, filtering, etc.)  
- 🧪 Tailored for **miniscope + 7.4 mm GRIN lens** setups  
- 💻 Fully scriptable & modular for integration into your analysis pipeline  

---

### 🚀 Quick Start  
```bash
# Clone the repository
git clone https://github.com/yourusername/MiniscopePipeline.git
cd MiniscopePipeline

# Run the converter
python convert_isxd_to_tiff.py --input data/session.isxd --output data/session.tiff
