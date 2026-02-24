
# 📌 Projeto – Infraestrutura de Cloud Híbrida

![Planta](images/1.%20planta.png)

Implementação de uma infraestrutura de **Cloud Híbrida**, integrando ambiente **on-premises** com a nuvem 

O cenário simula uma pequena empresa com usuários internos, acesso remoto seguro e integração com a nuvem para backup e continuidade do negócio.

---

## 🏢 Ambiente Local (On-Premises)

- 13 estações integradas ao domínio  
- 3 impressoras de rede  
- 1 servidor **Windows Server 2022**  
- **Active Directory**  
- File Server com controle de permissões  
- Autenticação e gerenciamento centralizado de usuários  

Responsável por identidade, autenticação e armazenamento principal de arquivos.

---

## 🌐 Acesso Remoto

### 👤 Usuário 1 – VDI
- Acesso via **Virtual Desktop Infrastructure (VDI)**  
- Processamento no ambiente local  
- Conexão segura via **FortiClient VPN**  

### 👤 Usuário 2 – VPN
- Acesso remoto à rede corporativa  
- Autenticação via domínio  
- Conexão segura com **FortiClient VPN**  

---

## ☁️ Integração com AWS

- Conectividade entre rede local e VPC na AWS  
- Backup em nuvem  
- Suporte à continuidade do negócio  
- Expansão futura para novos serviços  

Comunicação via **VPN Site-to-Site**, garantindo tráfego seguro entre os ambientes.

---