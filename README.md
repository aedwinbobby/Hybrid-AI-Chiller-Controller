# Hybrid-AI-Chiller-Controller
This project uses Artificial Intelligence to automatically determine the optimal chilled water supply temperature (CHWS) for large buildings, based on real-time conditions like TR Load, ambient temperature, and electricity consumption.
It combines:

Machine Learning (Reinforcement Learning) for data-driven control

Physics-based rules to ensure realistic temperature ranges

This hybrid approach makes the chiller system both intelligent and energy-efficient.

🧩 Key Features

✅ Predicts chilled water temperature dynamically
✅ Adapts to load and ambient temperature changes
✅ Combines AI learning with physical HVAC principles
✅ Interactive Gradio Web Interface
✅ Realistic trend — colder water for higher load

🧠 How It Works

The model takes three inputs:

TR Load (Tons of Refrigeration)

Ambient Temperature (°C)

Electricity Consumed (kW)

and outputs:

Recommended Chilled Water Supply Temperature (°C)

Working Flow:

Generate or collect chiller operation data

Train a Reinforcement Learning model using PyTorch

Apply hybrid logic (AI + HVAC physics)

Deploy as a Gradio interface for real-time prediction

