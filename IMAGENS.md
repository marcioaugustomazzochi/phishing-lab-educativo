# 📸 **GALERIA DE EVIDÊNCIAS**
## 🚀 **Execução Prática — Phishing Lab Educativo**

> 📌 Documentação visual da execução do laboratório em ambiente controlado (**Kali Linux + Python**).  
> 🎯 Finalidade exclusivamente educacional.

---

## 🔹 **1. Criação e Ativação do Ambiente Virtual**

### 📌 Objetivo
Criar um ambiente isolado para execução segura do projeto.

### 💻 Comandos Executados

```bash
python3 -m venv venv
source venv/bin/activate
```

### 🖼️ Evidência

![Figura 1 — Criação e ativação do ambiente virtual (venv) no Kali Linux](https://github.com/user-attachments/assets/dd4195aa-5245-4915-b3f5-c18b8ada461a)

---

## 🔹 **2. Instalação das Dependências**

### 📌 Objetivo
Instalar as bibliotecas necessárias definidas no arquivo `requirements.txt`.

### 💻 Comando Executado

```bash
pip install -r requirements.txt
```

### 🖼️ Evidência

![Figura 2 — Instalação das dependências no ambiente virtual (venv)](https://github.com/user-attachments/assets/711ed35a-0b02-4127-a725-446769044929)

---

## 🔹 **3. Execução do Servidor Flask**

### 📌 Objetivo
Inicializar a aplicação web local para simulação educativa.

### 💻 Comando Executado

```bash
python app.py
```

### 🌐 Aplicação Disponível em

```
http://localhost:5000
```

### 🖼️ Evidência

![Figura 3 — Servidor Flask em execução no Kali Linux](https://github.com/user-attachments/assets/b1099280-2dc8-49d6-8570-6a229d7adef6)

---

## 🔹 **4. Registro de Logs da Simulação**

### 📌 Objetivo
Registrar automaticamente as interações realizadas na página educativa.

- 📄 Armazenamento em **CSV**
- 🗄️ Armazenamento em **SQLite**
- 📊 Coleta de dados para análise educacional

### 🖼️ Evidência

![Figura 4 — Registro de interação e logs gerados](https://github.com/user-attachments/assets/7e08d0ba-df87-45e8-8c62-1bb2faacc80d)

---

# 🛡️ **OBSERVAÇÃO DE SEGURANÇA**

> ⚠️ Este laboratório foi desenvolvido exclusivamente para:
>
> - 🎓 **Estudos acadêmicos**
> - 🧠 **Conscientização em Segurança da Informação**
> - 🧪 **Simulações controladas**
> - ✅ **Ambiente autorizado**
>
> ❗ **Não deve ser utilizado para fins maliciosos.**
