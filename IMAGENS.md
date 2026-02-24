# 📸 Execução Prática do Laboratório

Esta seção apresenta as evidências reais da execução do **Phishing Lab Educativo** em ambiente controlado (Kali Linux + Python).

Todas as etapas foram realizadas localmente para fins educacionais.

---

## 🔹 1. Criação do Ambiente Virtual

Criação do ambiente isolado para execução do projeto:

```bash
python3 -m venv venv
source venv/bin/activate
```

Evidência da ativação do ambiente virtual:

<img width="1920" height="936" alt="Figura 1 — Criação e ativação do ambiente virtual (venv) no Kali Linux" src="https://github.com/user-attachments/assets/dd4195aa-5245-4915-b3f5-c18b8ada461a" />

---

## 🔹 2. Instalação das Dependências

Instalação das bibliotecas necessárias conforme o arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

Evidência da instalação das dependências:

<img width="1920" height="936" alt="Figura 2 — Instalação das dependências no ambiente virtual (venv)" src="https://github.com/user-attachments/assets/711ed35a-0b02-4127-a725-446769044929" />

---

## 🔹 3. Execução do Servidor Flask

Inicialização da aplicação web local:

```bash
python app.py
```

Servidor disponível em:

```
http://localhost:5000
```

Evidência do servidor em execução:

<img width="1920" height="936" alt="Figura 3 - phishing-lab-execution-proof png" src="https://github.com/user-attachments/assets/b1099280-2dc8-49d6-8570-6a229d7adef6" />

---

## 🔹 4. Interação e Registro de Logs

Simulação de interação na página educativa e registro automático das informações em log (CSV / SQLite).

Evidência da interação registrada:

<img width="1920" height="936" alt="Figura 4 — Servidor Flask em execução no Kali Linux" src="https://github.com/user-attachments/assets/7e08d0ba-df87-45e8-8c62-1bb2faacc80d" />

---

## 🛡️ Observação de Segurança

Este laboratório foi desenvolvido exclusivamente para:

- Estudos de Engenharia Social
- Conscientização de usuários
- Simulações controladas
- Ambiente autorizado

Não deve ser utilizado para fins maliciosos.

---
