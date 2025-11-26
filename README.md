# 📔 Documentação: Configuração de Servidor Web com o Amazon EC2

Este repositório contém minha documentação prática: O Amazon Elastic Compute Cloud (Amazon EC2), é serviço que fornece capacidade computacional escalável na nuvem. Aprendi como o EC2 facilita a criação e configuração de servidores de forma rápida e prática, oferecendo controle total sobre os recursos utilizados e permitindo pagar apenas pelo que é consumido. Também compreendi como o serviço contribui para aplicações mais resilientes e com maior disponibilidade. como parte das atividades do programa **AWS re/Start - Escola da Nuvem ☁️**.

## 🧠 Conhecimentos Adquiridos
Ao final do laboratório, fui capaz de:
- 🚀 Iniciar uma instância EC2 configurada como servidor web, com proteção contra encerramento ativada.
- 📊 Monitorar métricas da instância, analisando desempenho e comportamento em tempo real.
- 🔒 Modificar grupos de segurança, liberando o tráfego HTTP para acesso ao servidor via navegador.
- 📈 Redimensionar a instância conforme a demanda, ajustando capacidade computacional.
- 🛡️ Testar a proteção contra encerramento, garantindo que a instância não seja encerrada acidentalmente.
- 🗑️ Finalizar a instância EC2 de forma segura ao concluir o laboratório.

---

## 🛠️ Tecnologias Utilizadas

<div align="left">

  <img src="https://img.shields.io/badge/Linux-%23000000?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Bash-%234EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/AWS%20EC2-%23FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS EC2" />
  <img src="https://img.shields.io/badge/Amazon%20Linux-%23232F3E?style=for-the-badge&logo=linux&logoColor=white" alt="Amazon Linux" />

</div>

---

## 📁 Estrutura do Repositório

`conhecendo-EC2-AWS/`

```
├── ec2-screenshots/ # Capturas de tela organizadas por etapa
├── README.md # Este arquivo
````

---

## 🖥️ Etapas Realizadas

### 1. Criação da Instância EC2

- Sistema: Amazon Linux 2023  
- Tipo: `t3.micro` (modificado posteriormente)  
- Armazenamento: 8 GiB (modificado posteriormente)  
- Nome da chave PEM: `vockey.pem`  

### ⚙️ Configuração da instância no console da AWS

#### Nome da instância
