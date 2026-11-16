# -resumo-do-lab
 "Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
# ☁️ Resumo de Estudos: Microsoft Azure Fundamentals (AZ-900)

Este repositório reúne minhas anotações, aprendizados teóricos e práticas realizadas durante a trilha de preparação para a certificação **AZ-900 (Microsoft Azure Fundamentals)** na [DIO](https://www.dio.me/).

---

## 📌 1. Conceitos de Nuvem (Cloud Computing)

A computação em nuvem consiste na entrega sob demanda de recursos de TI pela internet com definição de preço conforme o uso (*Pay-as-you-go*).

### Principais Benefícios:
* **Alta Disponibilidade:** Garantia de que os serviços permaneçam operacionais sem interrupções prolongadas (baseado em SLAs).
* **Escalabilidade:** Capacidade de aumentar ou diminuir recursos conforme a demanda:
  * *Vertical (Scale Up/Down):* Adicionar mais CPU/RAM a uma máquina existente.
  * *Horizontal (Scale Out/In):* Adicionar ou remover instâncias de máquinas.
* **Elasticidade:** Capacidade do sistema de escalar automaticamente de forma dinâmica.
* **Agilidade e Tolerância a Falhas:** Implantação rápida de ambientes e redundância contra quedas físicas.

### Modelos de Despesa:
* **CapEx (Despesa de Capital):** Investimento inicial em infraestrutura física (data centers locais).
* **OpEx (Despesa Operacional):** Gasto contínuo conforme o consumo dos serviços na nuvem.

---

## 🏗️ 2. Modelos de Nuvem e Tipos de Serviço

### Modelos de Implantação:
* **Nuvem Pública:** Recursos pertencem e são gerenciados por um provedor (ex: Microsoft Azure) e compartilhados entre vários clientes.
* **Nuvem Privada:** Infraestrutura dedicada exclusivamente a uma única organização (on-premises ou hospedada).
* **Nuvem Híbrida:** Combinação entre nuvem pública e privada, permitindo movimentação de dados e aplicações entre ambas.

### Modelo de Responsabilidade Compartilhada:
A divisão de responsabilidades entre o cliente e a Microsoft varia conforme o modelo de serviço:

| Modelo | Descrição | Exemplos no Azure |
| :--- | :--- | :--- |
| **IaaS** *(Infraestrutura como Serviço)* | Controle máximo sobre o SO e aplicações; a Microsoft gerencia o hardware físico. | Azure Virtual Machines, Virtual Networks |
| **PaaS** *(Plataforma como Serviço)* | Foco no desenvolvimento e implantação da aplicação, sem gerenciar SO ou servidores. | Azure App Service, Azure SQL Database |
| **SaaS** *(Software como Serviço)* | Software pronto para uso final via navegador, totalmente gerenciado pelo provedor. | Microsoft 365, Dynamics 365 |

---

## ⚙️ 3. Arquitetura e Serviços Principais do Azure

### Hierarquia de Gerenciamento:
1. **Grupos de Gerenciamento (Management Groups):** Organizam múltiplas assinaturas com políticas unificadas.
2. **Assinaturas (Subscriptions):** Unidades de faturamento e limite de acesso.
3. **Grupos de Recursos (Resource Groups):** Contêineres lógicos que agrupam recursos relacionados de uma mesma solução.
4. **Recursos (Resources):** Instâncias de serviços criados (VMs, Bancos de Dados, Redes, etc.).

### Infraestrutura Física:
* **Regiões e Pares de Regiões:** Áreas geográficas contendo data centers interligados por rede de baixa latência.
* **Zonas de Disponibilidade (Availability Zones):** Data centers fisicamente separados dentro de uma mesma região (energia, refrigeração e rede independentes).

### Serviços Explorados nos Labs:
* **Computação:** Criação e configuração de *Azure Virtual Machines* e *App Services*.
* **Rede:** Configuração de *Virtual Networks (VNet)*, sub-redes e *Network Security Groups (NSG)* para filtragem de tráfego.
* **Armazenamento:** Criação de *Storage Accounts* utilizando *Blob Storage* para dados não estruturados e camadas de acesso (*Hot, Cool, Archive*).

---

## 🛡️ 4. Segurança, Governança e Gerenciamento de Custos

* **Microsoft Entra ID (antigo Azure AD):** Serviço de gerenciamento de identidade e acesso (IAM), autenticação multifator (MFA) e Single Sign-On (SSO).
* **RBAC (Controle de Acesso Baseado em Função):** Concessão de permissões granulares seguindo o princípio do menor privilégio.
* **Azure Policy e Resource Locks:** Governança para garantir conformidade e bloqueios (*CanNotDelete* / *ReadOnly*) contra exclusões acidentais.
* **Gerenciamento de Custos:** Uso da *Calculadora de Preços do Azure*, *Calculadora de TCO* e configuração de alertas no *Microsoft Cost Management*.

---

## 🚀 Conclusão e Próximos Passos

O desenvolvimento dos laboratórios consolidou a visão prática de como provisionar, gerenciar e proteger recursos na nuvem Microsoft, servindo como base sólida para avançar em trilhas de arquitetura, administração e segurança em nuvem.
