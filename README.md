<p align="center">
  <img src="logoi.png" alt="TidyMind Logo" width="180px">
</p>

# <p align="center">HashDash — painel # hash</p>

<p align="center">
  O <b>HashDash</b> é um gerador de hash (SHA-256) rápido, minimalista e com interface moderna. Ideal para desenvolvedores e entusiastas que precisam validar strings de texto ou gerar tokens de verificação instantaneamente.
</p>

<p align="center">
  <a href="https://github.com/sueh0/Hash-Dash/releases/download/HashDash/HashDash.exe">
    <img src="https://img.shields.io/badge/DOWNLOAD-HashDash%20(.EXE)-success?style=for-the-badge&logo=windows&logoColor=white&color=2ecc71" alt="Botão de Download TidyMind" height="50px">
  </a>
</p>

---

## 🛠️ Como funciona?
O **HashDash** utiliza a biblioteca padrão `hashlib` do Python para implementar o algoritmo de criptografia **SHA-256**. O funcionamento é simples e eficiente:

* **Entrada em Tempo Real**: A interface utiliza eventos de teclado para capturar sua entrada instantaneamente[cite: 1].
* **Processamento**: O texto inserido é codificado em `UTF-8` e convertido em um hash hexadecimal de 256 bits[cite: 1].
* **Interface**: Construído com `customtkinter`, garantindo uma experiência fluida no modo escuro (*dark mode*).

---

## 💻 Stack usada
* **Linguagem**: Python 3
* **Interface Gráfica**: CustomTkinter
* **Criptografia**: Hashlib (SHA-256)
* **Empacotamento**: PyInstaller

---

## 📋 Rodar pelo Git
Se preferir rodar direto pelo código em vez do executável:

1. Clone o repositório:
   ```bash
   git clone [https://github.com/m4hun0/HashDash.git](https://github.com/m4hun0/HashDash.git)
