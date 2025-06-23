# Guia Prático: Gestão de Máquinas Virtuais no Microsoft Azure

## 📌 Descrição

Este repositório faz parte do desafio da DIO: **"Gerenciamento de Máquinas Virtuais no Azure"**.

Aqui você encontrará anotações, comandos, dicas e capturas de tela das etapas práticas realizadas para criação, configuração e gerenciamento de VMs na plataforma Azure.

---

## 🎯 Objetivos do Projeto

- Aplicar conceitos aprendidos no curso.
- Documentar de forma clara o processo de criação e gerenciamento de máquinas virtuais no Azure.
- Compartilhar o conteúdo com outros alunos e profissionais de TI.

---

## 🧱 Conteúdo

### 1. O que é uma Máquina Virtual no Azure?

- Definição de VM
- Casos de uso
- Tipos de workloads comuns

### 2. Principais Conceitos Abordados

- **Grupos de Recursos (Resource Groups)**
- **Tipos de Imagem:** Windows Server, Ubuntu, entre outros
- **Tamanhos de VM:** B1s, D2s_v3, etc.
- **Rede Virtual (VNet)** e Sub-redes
- **Endereçamento IP:** Público e Privado
- **Discos:** Disco do SO e Discos de Dados

### 3. Etapas Práticas Realizadas

#### ✅ Criação de uma Máquina Virtual

- Escolha da imagem (Ex: Ubuntu, Windows Server)
- Seleção de tamanho (SKU)
- Configuração de usuário e senha ou chave SSH
- Configuração de regras de firewall (NSG - Network Security Group)

#### ✅ Acesso à VM

- Conexão via **SSH** (Linux)
- Conexão via **RDP** (Windows)

#### ✅ Gerenciamento de Recursos

- Iniciar / Parar / Reiniciar VM
- Redimensionamento de tamanho (scale up / down)
- Configuração de IP fixo (opcional)

#### ✅ Monitoramento e Diagnóstico

- Uso básico do **Azure Monitor**
- Visualização de logs de desempenho
- Métricas de utilização (CPU, Disco, Rede)

---

## 💡 Dicas Importantes

- Sempre utilizar o **Azure Portal** ou o **Azure CLI** conforme o cenário.
- Verificar os **custos estimados** antes de iniciar uma VM de produção.
- Excluir recursos após os testes para **evitar cobranças indevidas**.
- Usar **tags** nos recursos para facilitar a organização e controle de custos.

---

## 🔗 Links Úteis

- [Portal do Azure](https://portal.azure.com)
- [Documentação Oficial do Azure - Virtual Machines](https://learn.microsoft.com/azure/virtual-machines/)
- [Azure CLI - Documentação](https://learn.microsoft.com/cli/azure/)

---

## ✅ Status do Projeto

| Item                           | Status       |
|--------------------------------|--------------|
| Curso assistido                | ✅ Concluído |
| Laboratório executado          | ✅ Concluído |
| Documentação criada            | ✅ Concluído |
| Repositório público no GitHub  | ✅ Concluído |

---

## 📝 Autor

[Elidio Mendes Jr]

