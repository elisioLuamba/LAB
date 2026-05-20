# LAB## 📦 Quick Install

### PY
```bash
pip install pyserial websockets python-socketio pyqt6 PyQt6-WebEngine pyqtgraph pyinstaller pygame pillow
```
### JS
```bash
npm install three@0.183.2 vite gsap cannon-es @dimforge/rapier3d socket.io-client lil-gui postprocessing three-stdlib howler gl-matrix three-ik
```

## 📦 Full Setup - Anaconda + Arduino CLI

<p align="center">
  <img src="https://img.shields.io/badge/Anaconda-Python-blue?logo=anaconda&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-CLI-red?logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white" />
</p>

```bash
# ---------------------------
# 1️⃣ Anaconda Environment
# ---------------------------
# Siga o link oficial se Anaconda não estiver instalada:
# https://www.anaconda.com/products/distribution

# Criação de ambiente isolado
conda create -n engineering-lab python=3.10
conda activate engineering-lab

# Instalar pacotes científicos
conda install numpy scipy pandas matplotlib opencv-python mediapipe

# ---------------------------
# 2️⃣ Arduino CLI
# ---------------------------
# Windows: baixar MSI oficial
# macOS/Linux: via Homebrew ou apt

arduino-cli core update-index
arduino-cli core install arduino:avr

# Teste de instalação
arduino-cli board list
