# 💰 Sistema Bancário em Python

![Status](https://img.shields.io/badge/Projeto-Concluído-green)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)


> Sistema bancário simples desenvolvido em **Python**, com funcionalidades essenciais como **depósitos**, **saques**, **extrato**, **cadastro de usuários** e **criação de contas**.
> Ideal para iniciantes praticarem conceitos de **lógica de programação**, **funções**, **estruturas condicionais**, **listas** e **manipulação de dados**.

---

## 🧩 Funcionalidades

✅ Menu interativo com as seguintes operações:

* 📥 **Depósito** em conta
* 💸 **Saque** com limite de valor e quantidade diária
* 📄 **Extrato** com histórico detalhado de transações
* 🧑 **Cadastro de usuários** com verificação de CPF único
* 🏦 **Criação de contas bancárias** associadas a usuários existentes
* 🧾 **Listagem de contas** cadastradas
* ❌ **Encerramento do sistema**

---

## 📌 Regras de Negócio

* ✅ **Depósito**: apenas valores **positivos** são aceitos
* ✅ **Saque**:

  * Máximo de **3 saques diários**
  * Limite de **R$ 500,00 por saque**
  * O valor **não pode exceder o saldo disponível**
* ✅ Cada usuário é identificado unicamente pelo **CPF**
* ✅ Cada conta está associada a **um único usuário**
* ✅ O **extrato** exibe todas as movimentações e o **saldo final**

---

## 🚀 Como Executar

### Pré-requisitos

* Python **3.10 ou superior** instalado na máquina

### Passos

1. Clone este repositório:

```bash
git clone https://github.com/MaduSantoss/sistema-bancario-atualizado
```

2. Acesse a pasta do projeto:

```bash
cd sistema-bancario-atualizado
```

3. Execute o script:

```bash
python sistema_bancario_atualizado.py
```

*(ou `python3 sistema_bancario_atualizado.py`, dependendo do seu sistema)*

---

## 🤝 Contribuições

Contribuições são bem-vindas!
Sinta-se à vontade para abrir uma **Issue** ou enviar um **Pull Request** com sugestões, melhorias ou correções.

---
