---



```markdown
# 📊 Guia de Monitoramento de VMs no Azure

Monitore o desempenho e a integridade das suas máquinas virtuais no Azure.

## 🔎 Monitoramento Básico

1. Vá até sua VM no portal
2. Clique em **Monitorar > Métricas**
3. Selecione métricas como:
   - Porcentagem de CPU
   - Bytes de Rede
   - Operações de Disco

## 📈 Log Analytics (opcional)

1. Ative o **Azure Monitor**
2. Vincule a VM a um **workspace do Log Analytics**
3. Acesse **Logs** para executar queries em KQL

Exemplo:

```kql
Perf
| where ObjectName == "Processor"
| summarize avg(CounterValue) by bin(TimeGenerated, 5m)
