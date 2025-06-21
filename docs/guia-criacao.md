# 🛠️ Guia de Criação de VM no Azure

Este guia apresenta o passo a passo para criar uma máquina virtual no Microsoft Azure usando o **Azure Portal**.

## Passos

1. Acesse [https://portal.azure.com](https://portal.azure.com)
2. Pesquise por “Máquinas Virtuais” e clique em **Criar > Máquina Virtual**
3. Preencha os campos obrigatórios:
   - Assinatura
   - Grupo de Recursos
   - Nome da VM
   - Região (ex: Brazil South)
   - Imagem (ex: Ubuntu 20.04 LTS ou Windows Server 2022)
   - Tipo de autenticação (Senha ou SSH)
4. Configure as portas de acesso (SSH/RDP)
5. Clique em **Revisar + Criar**
6. Após a validação, clique em **Criar**

⏱️ A criação da VM pode levar alguns minutos.

## Resultado

A máquina virtual será provisionada com IP público e estará pronta para conexão.
