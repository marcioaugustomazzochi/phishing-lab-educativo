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

![Ambiente Virtual Criado](imagens/01_ambiente_virtual.png)

---

## 🔹 2. Instalação das Dependências

Instalação das bibliotecas necessárias conforme o arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

Evidência da instalação das dependências:

![Dependências Instaladas](imagens/02_dependencias_instaladas.png)

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

![Servidor Flask Rodando](imagens/03_servidor_flask_rodando.png)

---

## 🔹 4. Interação e Registro de Logs

Simulação de interação na página educativa e registro automático das informações em log (CSV / SQLite).

Evidência da interação registrada:

![Interação Registrada](imagens/04_interacao_registrada.png)

---

## 🛡️ Observação de Segurança

Este laboratório foi desenvolvido exclusivamente para:

- Estudos de Engenharia Social
- Conscientização de usuários
- Simulações controladas
- Ambiente autorizado

Não deve ser utilizado para fins maliciosos.

---
