# ☁️ Conceitos EC2

## 🧭 Sobre o Repositório

Este repositório contém **anotações, resumos e insights** adquiridos durante o estudo sobre o serviço **Amazon EC2 (Elastic Compute Cloud)**, um dos pilares da computação em nuvem na AWS.  

O objetivo é reunir **conceitos teóricos e práticos**, com **casos de uso reais**, **exemplos visuais** e **descrições claras**, servindo como material de apoio para estudos e futuras implementações em projetos cloud.

---

## 🚀 O que é o Amazon EC2?

O **Amazon Elastic Compute Cloud (EC2)** é um serviço da **AWS (Amazon Web Services)** que oferece **capacidade de computação elástica e sob demanda**.  

Em outras palavras, é possível criar **máquinas virtuais (instâncias)** na nuvem, configuradas de acordo com a necessidade de processamento, memória, armazenamento e sistema operacional.

💡 **Significado de “elástico”**:  
Refere-se à capacidade de **aumentar ou diminuir recursos automaticamente** conforme a demanda da aplicação.

---

## ⚙️ Conceitos Fundamentais

| Conceito | Descrição |
|-----------|-----------|
| **Instância** | É uma máquina virtual executando na AWS. |
| **AMI (Amazon Machine Image)** | Modelo de imagem que define o sistema operacional e as configurações da instância. |
| **Tipo de Instância** | Define o tamanho e a capacidade da máquina (CPU, memória, rede). |
| **Key Pair** | Par de chaves para autenticação segura via SSH. |
| **Security Groups** | Conjunto de regras que controlam o tráfego de rede (entrada e saída). |
| **Elastic IP** | Endereço IP fixo associado a uma instância. |
| **Auto Scaling** | Ajuste automático da quantidade de instâncias conforme a demanda. |
| **Load Balancer** | Distribui o tráfego entre múltiplas instâncias. |

---

## 💼 Casos de Uso do EC2

O EC2 é extremamente versátil e pode ser utilizado em diversos contextos, como:

- 🖥️ **Hospedagem de sites e aplicações web**
- 🧠 **Treinamento de modelos de Machine Learning**
- 🧮 **Processamento de grandes volumes de dados**
- 🧱 **Serviços de backend para APIs**
- 🔐 **Ambientes de testes e desenvolvimento isolados**
- 🗄️ **Servidores de banco de dados ou cache**

---

## 🌍 Importância do EC2 na Arquitetura AWS

O **Amazon EC2** é um dos serviços **centrais da AWS**, pois fornece a base computacional sobre a qual diversos outros serviços são construídos.  

Ele permite que empresas e desenvolvedores:
- Evitem o custo e a complexidade de manter servidores físicos;  
- Dimensionem recursos de acordo com o uso real;  
- Implantem aplicações globalmente em minutos;  
- Tenham **alta disponibilidade**, **segurança** e **resiliência**.

---

## 🖼️ Exemplo Visual — Arquitetura com EC2

> Representação simplificada de uma aplicação hospedada na AWS utilizando instâncias EC2:
> <img src="/Images/Diagrama EC2.png">

**Descrição do Diagrama:**
- O **usuário** acessa a aplicação via **Load Balancer**;  
- O tráfego é distribuído entre múltiplas **instâncias EC2**;  
- Os dados são armazenados em um **banco RDS**;  
- Todos os recursos estão protegidos dentro de uma **VPC (Virtual Private Cloud)**.

---

## 🧠 Insights e Aprendizados

📘 Durante o estudo sobre o EC2, foram identificados os seguintes pontos-chave:

1. **Elasticidade e escalabilidade automática** tornam o EC2 ideal para aplicações com variação de carga.  
2. **Segurança em camadas** é garantida via IAM, Security Groups e VPC.  
3. O **custo sob demanda** é uma vantagem, mas requer atenção ao tempo de execução das instâncias.  
4. A integração com **outros serviços AWS (S3, RDS, CloudWatch, IAM)** aumenta a eficiência e observabilidade.  
5. O uso de **scripts de inicialização (User Data)** automatiza a configuração das instâncias.

---

## 🧩 Tecnologias Relacionadas

- 🐧 **Linux / Windows Server**
- ☕ **Java, Python, Node.js**
- 🧱 **AWS CLI e SDK**
- 🧮 **CloudFormation e Terraform**
- 🔍 **AWS CloudWatch e CloudTrail**

---
