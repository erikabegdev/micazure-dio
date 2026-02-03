# MicAzure – Arquitetura de Dados no Azure (DIO)

## 📌 Visão Geral
Este repositório contém um projeto prático desenvolvido durante o curso da **DIO**, com foco na criação e estruturação de uma **infraestrutura completa de dados no Azure**.  
O objetivo foi consolidar, na prática, os conceitos de cloud e engenharia de dados, entendendo o papel de cada serviço dentro de uma arquitetura realista.

Mais do que apenas criar recursos, o projeto buscou desenvolver **visão arquitetural**, organização e compreensão do fluxo de dados ponta a ponta.

---

## 🏗️ Arquitetura do Projeto
A infraestrutura foi organizada seguindo boas práticas de cloud, separando claramente as responsabilidades de cada serviço:

1. **Visão geral do Resource Group**  
   Centralização e organização dos recursos, garantindo governança e clareza da arquitetura.

2. **Azure Data Factory (ADF)**  
   Responsável pela orquestração dos pipelines e pela integração entre os serviços da plataforma.

3. **Azure Storage Account**  
   Camada de armazenamento dos dados, servindo como base para ingestão e persistência.

4. **Azure Databricks**  
   Utilizado para processamento distribuído, transformação e análise dos dados.

5. **Azure Event Hub**  
   Serviço de ingestão de dados em tempo real, simulando cenários de streaming.

6. **Azure Machine Learning e Monitoramento**  
   Camada avançada da arquitetura, incluindo observabilidade, experimentação e boas práticas para ambientes produtivos.

---
## 🧠 Aprendizados

- Como organizar recursos em **Resource Groups** para governança.
- Diferença entre **ingestão**, **processamento** e **orquestração** de dados.
- Criação e manipulação de recursos no **portal Azure**.
- Importância de serviços de **monitoramento e segurança** (Key Vault, Log Analytics).
- Visão de arquitetura aplicada em um ambiente de dados real.


---

## 📸 Evidências do Projeto
As imagens abaixo demonstram os recursos criados e a estrutura final da infraestrutura:
![01](https://github.com/user-attachments/assets/e83116e4-f87d-4399-b586-7315d8b6d932)
![10](https://github.com/user-attachments/assets/2731696b-4c4d-495c-a131-5ff14dec344b)
![05](https://github.com/user-attachments/assets/4875610a-144c-4b8f-a79b-17d277d7dc49)
![08](https://github.com/user-attachments/assets/a88d3a4c-f72e-487b-a7c3-a0d421f0bba1)
![12](https://github.com/user-attachments/assets/3f96506f-7a46-4919-84b3-bef932892ba0)
![13](https://github.com/user-attachments/assets/81af5620-c100-4b8b-884f-3f35f17956b0)
![14](https://github.com/user-attachments/assets/ef1a702b-c06b-4eb6-88d2-051d0d8277a8)
![17](https://github.com/user-attachments/assets/9d826ecc-f147-4f18-93b7-5d7205eef564)




