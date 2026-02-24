# 📸 Evidências da Execução do Laboratório

Esta seção apresenta a execução prática do **Phishing Lab Educativo** em ambiente controlado (Kali Linux + Python), demonstrando cada etapa do processo.

---

## 🔹 1️⃣ Criação e Ativação do Ambiente Virtual

Comando utilizado:

```bash
python3 -m venv venv
source venv/bin/activate
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/dd4195aa-5245-4915-b3f5-c18b8ada461a" width="900">
</p>

<p align="center"><em>Figura 1 — Criação e ativação do ambiente virtual (venv)</em></p>

---

## 🔹 2️⃣ Instalação das Dependências

Comando utilizado:

```bash
pip install -r requirements.txt
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/711ed35a-0b02-4127-a725-446769044929" width="900">
</p>

<p align="center"><em>Figura 2 — Instalação das dependências no ambiente virtual</em></p>

---

## 🔹 3️⃣ Execução do Servidor Flask

Comando utilizado:

```bash
python app.py
```

Aplicação disponível em:

```
http://localhost:5000
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/b1099280-2dc8-49d6-8570-6a229d7adef6" width="900">
</p>

<p align="center"><em>Figura 3 — Servidor Flask em execução</em></p>

---

## 🔹 4️⃣ Interação e Registro de Logs

Após a interação com a página educativa, os dados foram registrados automaticamente em log (CSV / SQLite).

<p align="center">
  <img src="https://github.com/user-attachments/assets/7e08d0ba-df87-45e8-8c62-1bb2faacc80d" width="900">
</p>

<p align="center"><em>Figura 4 — Registro de interação e evidência prática</em></p>

---

## 🛡️ Observação

Todas as execuções foram realizadas em ambiente controlado, exclusivamente para fins educacionais e de conscientização em Segurança da Informação.

---
