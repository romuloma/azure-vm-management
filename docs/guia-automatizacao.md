```markdown
# 🤖 Guia de Automação no Gerenciamento de VMs

Automatize tarefas comuns como desligamento automático e start/stop programado.

## ☀️ Desligamento Automático (Auto-Shutdown)

1. Acesse a VM no portal
2. Vá em **Operações > Desligamento automático**
3. Ative e defina o horário desejado (UTC)

## ⚙️ Start/Stop via Script

### Bash Script (Azure CLI)

```bash
# Iniciar VM
az vm start --name NomeDaVM --resource-group NomeDoGrupo

# Parar VM
az vm deallocate --name NomeDaVM --resource-group NomeDoGrupo
