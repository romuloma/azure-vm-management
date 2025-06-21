# ☁️ Gerenciamento de Máquinas Virtuais no Microsoft Azure

Este repositório contém tutoriais, exemplos e automações para gerenciar **Máquinas Virtuais (VMs)** no **Microsoft Azure** utilizando o portal, a CLI, scripts e boas práticas de segurança e monitoramento.

## 📌 Objetivos

- Criar VMs pelo portal e via CLI
- Automatizar inicialização e desligamento
- Acessar VMs com segurança (SSH e RDP)
- Monitorar uso de CPU, disco e rede
- Aplicar políticas de segurança e shutdown automático

## 🧱 Estrutura

| Pasta        | Descrição                                                |
|--------------|----------------------------------------------------------|
| `docs/`      | Guias detalhados de cada funcionalidade                  |

## 🧭 Tutoriais Disponíveis

### 1. [Criar uma VM via Portal](docs/guia-criacao.md)


### 2. [Acessar VM via SSH ou RDP](docs/guia-acesso.md)


### 3. [Monitorar e aplicar alertas](docs/guia-monitoramento.md)


### 4. [Automatizar desligamento/ligamento de VMs](docs/guia-automatizacao.md)


## 🔧 Requisitos

- Conta no [Azure Portal](https://portal.azure.com)
- Azure CLI instalada (opcional)
- Acesso com permissões para criar recursos

## 🚀 Scripts de Automação

- `create-vm.sh`: cria uma VM via Azure CLI
- `start-stop-vm.sh`: liga e desliga uma VM
- `auto-shutdown.ps1`: configura desligamento automático via PowerShell

## 📚 Fontes Oficiais

- [Documentação de VMs no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [Azure CLI - Virtual Machines](https://learn.microsoft.com/pt-br/cli/azure/vm)

## 🛡️ Segurança

- Nunca exponha portas RDP/SSH sem necessidade
- Use NSGs e Just-in-Time Access
- Configure o Azure Defender for Cloud para alertas e recomendações

## 🧑‍💻 Contribuições

Pull requests são bem-vindos! Sinta-se livre para adicionar scripts, tutoriais ou corrigir algo.

## 📜 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.
