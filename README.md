# Criação de Máquina Virtual no Azure

Este repositório documenta o processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure, como parte do desafio da DIO.

---

## Objetivos

- Praticar a criação de uma máquina virtual (VM) no Azure.
- Documentar o processo técnico de forma clara e estruturada.
- Compartilhar anotações, dicas e prints úteis para estudos futuros.

---

## Tutorial Utilizado

Todo o processo de criação da máquina virtual foi baseado no guia oficial da Microsoft:

[Início Rápido: Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

---

## Etapas Realizadas

1. Acesso ao [Portal do Azure](https://portal.azure.com/)
2. Criação de grupo de recursos: `myVM_group`
3. Seleção da imagem: **Windows Server 2022 Datacenter - Azure Edition**
4. Tamanho da VM: **Standard B1s (1 vCPU, 1 GiB RAM)**
5. Configuração de rede com IP público e RDP habilitado
6. Criação da VM e verificação do status
7. Acesso remoto via RDP

---

## Detalhes da Configuração da VM

- **Grupo de Recursos:** myVM_group  
- **Local:** Brazil South (Zona 1)  
- **Sistema Operacional:** Windows Server 2022 Datacenter - Azure Edition  
- **Tamanho da VM:** Standard B1s (1 vCPU, 1 GiB de memória)  
- **Geração da VM:** V2  
- **Arquitetura:** x64  
- **IP Público:** 20.201.121.11  
- **IP Privado:** 10.0.0.4  
- **Rede Virtual/Sub-rede:** myVM-vnet/default  
- **Status:** Em execução  
- **Horário de Criação:** 26/04/2025, 04:04 UTC  
- **Nome da VM:** myVM  
- **Extensões:** Nenhuma instalada  
- **Desligamento automático:** Não habilitado  
- **Segurança:**  
  - Inicialização segura: habilitada  
  - vTPM: habilitado  
  - Criptografia no host: desabilitada  
- **Status do Agente:** Not Ready (possivelmente pendente de conexão RDP)

---

## Dicas Importantes

- Desligue a VM ao terminar para evitar cobranças.
- Sempre valide o status do agente após a criação da VM.
- Use **tags** nos recursos para melhor organização.
- Salve prints das etapas para futuras consultas.

---

## Capturas de Tela

As capturas das principais etapas estão disponíveis na pasta `/images`.

---

## Referências

- [Criar uma VM no Azure (Microsoft Docs)](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)  
- [Guia de Markdown para GitHub](https://www.markdownguide.org/basic-syntax/)  
- [Guia completo do GitHub](https://docs.github.com/)

---

> Feito com 💜 para o desafio da DIO!
