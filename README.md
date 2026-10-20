<p align="center">
  <img src="banner.png" alt="Hybrid AI Chiller Controller" width="100%">
</p>

<h1 align="center">❄️ Hybrid AI Chiller Controller</h1>

<p align="center">
  <b>An intelligent control system that recommends the optimal chilled water supply temperature (CHWS) for large buildings — combining Reinforcement Learning with physics-based HVAC rules for energy-efficient cooling.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-Reinforcement%20Learning-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Gradio-Web%20UI-FF9800?logo=gradio&logoColor=white" alt="Gradio">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License: MIT">
</p>

---

## 🧠 Overview

Chiller plants are among the largest energy consumers in commercial buildings. Fixing the chilled water supply temperature wastes energy when conditions change. This project uses **Artificial Intelligence to automatically determine the optimal CHWS in real time**, based on the building's cooling load, ambient temperature and electricity consumption.

The **hybrid** approach is the key idea:

- 🤖 **Machine Learning (Reinforcement Learning)** learns data-driven control decisions
- 📐 **Physics-based rules** keep the recommended temperature within realistic, safe HVAC ranges

The result is a controller that is both intelligent and energy-efficient.

## 🚀 Key Features

- ✅ Predicts the chilled water supply temperature **dynamically**
- ✅ **Adapts** to load and ambient temperature changes in real time
- ✅ Combines **AI learning with physical HVAC principles**
- ✅ **Interactive Gradio web interface** for live prediction
- ✅ Realistic control trend — colder water for higher load

## ⚙️ How It Works

The model takes three inputs:

| Input | Unit |
|-------|------|
| TR Load (Tons of Refrigeration) | TR |
| Ambient Temperature | °C |
| Electricity Consumed | kW |

…and outputs one decision:

> **Recommended Chilled Water Supply Temperature (°C)**

**Working flow:**

1. Generate / collect chiller operation data
2. Train a **Reinforcement Learning** model using **PyTorch**
3. Apply **hybrid logic** — AI recommendation bounded by HVAC physics rules
4. Deploy as a **Gradio interface** for real-time prediction

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core language |
| **PyTorch** | Reinforcement Learning model |
| **Gradio** | Web interface |
| **pandas / NumPy** | Data handling |

## 📂 Project Structure

```
Hybrid-AI-Chiller-Controller/
├── hybrid_ai_chiller_controller.ipynb   # Model development & training
├── requirements.txt                     # Python dependencies
└── README.md
```

## ▶️ Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/aedwinbobby/Hybrid-AI-Chiller-Controller.git
cd Hybrid-AI-Chiller-Controller

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook and run through the training & demo
jupyter notebook hybrid_ai_chiller_controller.ipynb
```

## 🔮 Future Improvements

- Integration with live building-management-system (BMS) data streams
- Benchmarking energy savings against fixed-setpoint control
- Deployment as a standalone prediction API

## 👤 Author

**Aedwin Bobby** — Computer Engineering student at Mangalam College of Engineering, Kottayam, and AI/ML enthusiast.

- 🌐 Website: [aedwinbobby.github.io](https://aedwinbobby.github.io)
- 💼 LinkedIn: [linkedin.com/in/aedwinbobby](https://www.linkedin.com/in/aedwinbobby)
- 🐙 GitHub: [github.com/aedwinbobby](https://github.com/aedwinbobby)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
