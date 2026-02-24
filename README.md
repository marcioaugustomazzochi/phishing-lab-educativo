# 🛡️ Phishing Lab Educativo – Automação em Python 🐍

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![WIP](https://img.shields.io/badge/Status-Em%20Andamento-orange)](https://github.com/marcioaugustomazzochi/phishing-lab-educativo)
[![GitHub stars](https://img.shields.io/github/stars/marcioaugustomazzochi/phishing-lab-educativo)](https://github.com/marcioaugustomazzochi/phishing-lab-educativo/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/marcioaugustomazzochi/phishing-lab-educativo)](https://github.com/marcioaugustomazzochi/phishing-lab-educativo/network/members)
[![GitHub issues](https://img.shields.io/github/issues/marcioaugustomazzochi/phishing-lab-educativo)](https://github.com/marcioaugustomazzochi/phishing-lab-educativo/issues)
[![GitHub commits](https://img.shields.io/github/commit-activity/m/marcioaugustomazzochi/phishing-lab-educativo)](https://github.com/marcioaugustomazzochi/phishing-lab-educativo/commits/main)

---

## 🔹 Visão Geral

**Phishing Lab Educativo** é um **laboratório seguro** desenvolvido em Python para **simular ataques de engenharia social de forma controlada**, permitindo aprendizado e demonstrações sobre ataques de phishing e boas práticas de segurança, sem comprometer terceiros.

> ⚠️ **Atenção:** Este projeto deve ser usado **apenas em ambiente controlado e para fins educativos**. Não execute testes em sistemas de terceiros sem autorização.

---

## ✅ Funcionalidades

- Criação automática de **páginas de phishing educativas**
- Envio de **e-mails simulados** para usuários de teste (lab seguro)
- Registro de interações em **logs locais (CSV/SQLite)**
- Captura automática de **screenshots** durante a execução
- Geração de **relatórios e estatísticas** sobre campanhas de teste
- Personalização de campanhas e templates educativos

---

## 🛠 Tecnologias Utilizadas

- **Python 3.x** – linguagem principal  
- **Flask** – servidor web para páginas educativas  
- **pyautogui** – captura de tela automatizada  
- **SQLite / CSV** – armazenamento de logs  
- **smtplib** – envio de e-mails simulados  
- **HTML / CSS / Jinja2** – criação de páginas e templates  
- **Matplotlib / Plotly (opcional)** – gráficos e dashboards  

---

## 📂 Estrutura do Repositório

```text
phishing-lab-educativo/
│
├─ README.md               # Documentação do projeto
├─ requirements.txt        # Bibliotecas Python necessárias
├─ app.py                  # Script principal do servidor web
├─ templates/              # Páginas HTML educativas
├─ logs/                   # Logs de interações (CSV ou DB)
├─ impressões/             # Capturas de tela automáticas
├─ emails/                 # Scripts de envio de e-mails seguros
├─ utils/                  # Funções auxiliares (relatórios, análise)
└─ examples/               # Exemplos de campanhas educativas

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

Confira as interações em:

logs/
impressões/
📸 Captura de Screenshots

O projeto possui captura automática de telas durante a execução, salvando os prints na pasta impressões/.

Cada screenshot recebe um timestamp único para evitar sobrescrita.

Exemplo:
import pyautogui
from datetime import datetime

timestamp = datetime.now().strftime("%Y%m%d_%H%M%S")
pyautogui.screenshot(f"impressões/screenshot_{timestamp}.png")
💡 Sugestões e Feedbacks

Feedbacks e sugestões são muito bem-vindos!
Abra issues ou pull requests para contribuir.

📜 Licença

MIT License – Uso restrito a fins educativos e em ambiente controlado.
