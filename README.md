# 🛡️ Phishing Lab Educativo – Automação em Python 🐍

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange)](https://github.com/marcioaugustomazzochi/phishing-lab-educativo)
[![Security Focus](https://img.shields.io/badge/Security-Blue%20Team-blue)]()

---

## 🎯 Objetivo do Projeto

O **Phishing Lab Educativo** é um laboratório controlado desenvolvido em Python com foco em:

- Simulação segura de campanhas de phishing
- Medição de comportamento do usuário
- Geração de métricas de conscientização
- Apoio a programas de Security Awareness
- Desenvolvimento de controles preventivos (Blue Team)

> ⚠️ Uso exclusivo em ambiente controlado e autorizado.

---

## 🧠 Conceitos Abordados

- Engenharia Social  
- Phishing Awareness  
- Segurança Defensiva (Blue Team)  
- Métricas de Taxa de Clique (CTR)  
- Monitoramento de Interações  
- Automação em Python aplicada à Segurança  
- Princípios alinhados à LGPD  

---

## ✅ Funcionalidades

- 🔹 Criação automática de páginas educativas de phishing  
- 🔹 Simulação de envio de e-mails em ambiente de laboratório  
- 🔹 Registro estruturado de interações (SQLite / CSV)  
- 🔹 Captura automática de screenshots  
- 🔹 Geração de relatórios em PDF  
- 🔹 Dashboard estatístico com gráficos  
- 🔹 Personalização de campanhas educativas  

---

## 🛠 Tecnologias Utilizadas

- **Python 3.x**
- **Flask**
- **SQLite**
- **Matplotlib**
- **ReportLab**
- **HTML / CSS / Jinja2**
- **pyautogui**

---

## 📊 Métricas Geradas

O laboratório permite acompanhar:

- Número total de usuários impactados  
- Taxa de clique em links simulados  
- Registro de interações por ação  
- Estatísticas consolidadas por campanha  
- Evidências visuais (screenshots)  

Essas métricas podem ser utilizadas para:

- Treinamentos internos  
- Relatórios de conscientização  
- Demonstração de maturidade em segurança  

---

## 📂 Estrutura do Projeto

```text
phishing-lab-educativo/
│
├─ app.py
├─ requirements.txt
├─ templates/
├─ logs/
│   ├─ interacoes.db
│   ├─ relatorio_campanha.pdf
│   └─ dashboard.png
├─ impressões/
├─ emails/
├─ utils/
│   ├─ logger.py
│   ├─ relatorio.py
│   └─ dashboard.py
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
🔐 Boas Práticas e Conformidade

Não utilizar contra terceiros

Não coletar dados reais

Executar apenas em ambiente isolado

Finalidade exclusivamente educacional

📈 Roadmap

 Sistema de autenticação para painel administrativo

 Dashboard web integrado ao Flask

 Múltiplas campanhas simultâneas

 Exportação automática em CSV

 Integração com métricas de risco

 Versão 1.0.0 estável

👨‍💻 Autor

Marcio Augusto Mazzochi
Analista de Segurança da Informação
Automação em Python | GRC | LGPD | Gestão de Riscos

📜 Licença

MIT License – Uso educacional em ambiente controlado.
