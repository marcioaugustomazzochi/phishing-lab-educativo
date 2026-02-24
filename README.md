# 🛡️ Phishing Lab Educativo – Automação em Python 🐍

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange)]()

---

## 🔹 Visão Geral

O **Phishing Lab Educativo** é um laboratório seguro desenvolvido em Python para simular campanhas educativas de engenharia social em ambiente controlado.

> ⚠️ Uso estritamente educacional e apenas em ambientes autorizados.

---

## ✅ Funcionalidades

- Criação automática de páginas educativas
- Simulação de envio de e-mails para ambiente de teste
- Registro de interações em logs (CSV/SQLite)
- Captura automática de screenshots
- Geração de relatórios simples
- Templates personalizáveis

---

## 🛠 Tecnologias Utilizadas

- Python 3.x
- Flask
- SQLite / CSV
- pyautogui
- smtplib
- HTML / CSS / Jinja2

---

## 📂 Estrutura do Repositório

```text
phishing-lab-educativo/
│
├─ README.md
├─ requirements.txt
├─ app.py
├─ templates/
├─ logs/
├─ impressões/
├─ emails/
├─ utils/
└─ examples/
🚀 Como Executar

Clone o repositório:

git clone https://github.com/marcioaugustomazzochi/phishing-lab-educativo.git
cd phishing-lab-educativo

Instale as dependências:

pip install -r requirements.txt

Execute o servidor:

python app.py

Acesse no navegador:

http://localhost:5000
📸 Exemplo de Captura de Tela
import pyautogui
from datetime import datetime

timestamp = datetime.now().strftime("%Y%m%d_%H%M%S")
pyautogui.screenshot(f"impressões/screenshot_{timestamp}.png")
💡 Contribuição

Sugestões e melhorias são bem-vindas.
Abra uma issue ou envie um pull request.

📜 Licença

MIT License – Uso educacional.
