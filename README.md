# az104-lab02-monitoramento

# Resumo da Etapa de Monitoramento de VMs na AZ-104
O monitoramento no Azure é essencial para garantir a disponibilidade, desempenho e segurança dos recursos em nuvem. O Azure oferece diversas ferramentas integradas para coletar, analisar e agir com base em dados de telemetria.

#
# Principais Serviços de Monitoramento no Azure

# 1.1 Azure Monitor
### Função: 
 - Coleta, analisa e age sobre dados de desempenho e disponibilidade.

### **Componentes principais:**
  - Métricas: Dados numéricos em tempo real (ex.: uso de CPU, memória).
  - Logs: Armazenamento e análise de logs (via Log Analytics).
  - Alertas: Notificações baseadas em condições definidas.
  - Application Insights: Monitoramento de aplicações (APM).

# 1.2 Azure Security Center (Azure Defender)
- Monitora ameaças à segurança e recomenda ações de proteção.

- Oferece proteção contra vulnerabilidades e detecção de ameaças.

# 1.3 Azure Network Watcher
- Monitora e diagnostica problemas de rede.

- Recursos como Packet Capture, Monitor de Conexão e NSG Flow Logs.

# 1.4 Azure Service Health
- Mostra o status de serviços Azure e impactos em sua assinatura.

- Inclui Service Issues, Planned Maintenance e Health Advisories.

# 1.5 Azure Log Analytics (parte do Azure Monitor)
- Armazena e consulta logs de diferentes fontes usando KQL (Kusto Query Language).

- Permite criar dashboards personalizados e relatórios.

# 1.6 Azure Application Insights
- Monitora aplicações web e móveis.

- Rastreia requisições, erros, dependências e desempenho.

#
# Principais Etapas para Implementar Monitoramento

# 2.1 Habilitar Azure Monitor
- Configurar coleta de métricas e logs para recursos (VMs, bancos de dados, aplicações).

# 2.2 Configurar Log Analytics

- Criar um workspace e conectar recursos para centralizar logs.

# 2.3 Definir Alertas

- Criar regras de alerta para métricas (ex.: CPU > 90%) ou logs (erros críticos).

# 2.4 Implementar Application Insights

- Instrumentar aplicações para rastrear desempenho e falhas.

# 2.5 Usar Dashboards e Workbooks

- Visualizar dados em painéis personalizados no Azure Portal.

# 2.6 Configurar Exportação de Dados

- Enviar logs para armazenamento externo ou SIEMs (ex.: Sentinel).

# 2.7 Automatizar Respostas

- Usar Azure Automation ou Logic Apps para ações automáticas (ex.: reiniciar VM em caso de falha).

#
# Benefícios do Monitoramento no Azure

✔ Detecção proativa de problemas antes que afetem os usuários.  
✔ Otimização de custos identificando recursos subutilizados.  
✔ Maior segurança com detecção de ameaças em tempo real.  
✔ Conformidade com relatórios e auditorias automatizadas.  

#
# Conclusão
#
A implementação de monitoramento no Azure é crucial para operações confiáveis e seguras. Utilizando **Azure Monitor**, **Security Center**, **Log Analytics** e **Application Insights**, as organizações podem garantir visibilidade completa e resposta rápida a incidentes.

📌 **Dica para a AZ-104:** Entenda como configurar alertas, consultar logs com KQL e integrar Application Insights em aplicações web.
