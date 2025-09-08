# 🎯 Bable Pet - Sistema Multiagente Dashboard

<div align="center">

![Bable Pet Logo](https://img.shields.io/badge/🐾-BABLE%20PET-blue?style=for-the-badge)

[![Sistema Status](https://img.shields.io/badge/Sistema-OPERACIONAL-brightgreen?style=for-the-badge&logo=checkmarx&logoColor=white)]()
[![Workflows Ativos](https://img.shields.io/badge/Workflows-2%20Ativos-blue?style=for-the-badge&logo=github-actions&logoColor=white)]()
[![Taxa Sucesso](https://img.shields.io/badge/Taxa%20Sucesso-100.0%25-brightgreen?style=for-the-badge&logo=target&logoColor=white)]()
[![Tempo Resposta](https://img.shields.io/badge/Tempo%20M%C3%A9dio-6.4s-brightgreen?style=for-the-badge&logo=stopwatch&logoColor=white)]()

**Última atualização:** `2025-09-08T19:03:17`

</div>

## 📊 Última Execução de Teste

- **ID da Execução:** `None`
- **Modo de Teste:** OTIMIZACAO
- **Status:** ✅ SUCESSO
- **Tempo de Execução:** 6.4s
- **Cenários Testados:** 3
- **Nodes Processados:** 0

## 🤖 Performance dos Agentes

| Agente | Score | Status | Última Atualização |
|--------|-------|--------|-------------------|
| Otimização 4-Agentes | 8.5/10 | 🟢 Ótimo | 2025-09-08 |
| Análise Performance | 10.0/10 | 🟢 Ótimo | 2025-09-08 |
| Qualidade | 1.0/10 | 🔴 Precisa Otimizar | 2025-09-08 |

## 🏗️ Arquitetura do Sistema

```mermaid
graph TD
    A[Cliente WhatsApp] --> B[ChatWoot]
    B --> C[N8N Webhook]
    C --> D[🎯 Agente Orquestrador]
    D --> E[👋 Agente Saudação]
    E --> F[💰 Comercial]
    E --> G[📅 Agendamento]
    E --> H[❓ FAQ]
    E --> I[🏢 Franquia]
    F --> J[👑 Agente Mestre]
    G --> J
    H --> J
    I --> J
    J --> K[Evolution API]
    K --> A
```

## 🚀 Status do Sistema

- **Operacional:** ✅ SIM
- **Total de Workflows:** 34
- **Workflows Ativos:** 2
- **Última Execução:** `None`

## 🛠️ Comandos de Teste

### Sistema Integrado com Dashboard
```bash
# Teste rápido com atualização do dashboard
python bable_pet_final.py --modo webhook

# Bateria completa com métricas detalhadas
python bable_pet_final.py --modo sequencial --cenarios 5

# Otimização com 4 agentes + dashboard
python bable_pet_final.py --modo otimizacao --cenarios 3

# Diagnóstico com análise completa
python bable_pet_final.py --modo diagnostico
```

## 📈 Histórico de Testes

**Execução mais recente:**
- **Timestamp:** 2025-09-08T19:03:17.642806
- **Resultado:** SUCESSO
- **Performance:** 100.0% de sucesso
- **Processamento:** 6.4s

## 🔗 Links Úteis

- [N8N Instance](https://n8n.synapseautointeligente.com.br)
- [Sistema de Testes](./bable_pet_final.py)
- [Documentação](./GUIA_FUNCIONAMENTO_COMPLETO.md)

---

<div align="center">

**🤖 Sistema atualizado automaticamente a cada execução de teste**

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=flat&logo=python&logoColor=white)](https://python.org)
[![Powered by N8N](https://img.shields.io/badge/Powered%20by-N8N-orange?style=flat&logo=n8n&logoColor=white)](https://n8n.io)
[![AI by Claude](https://img.shields.io/badge/AI%20by-Claude-purple?style=flat&logo=anthropic&logoColor=white)](https://claude.ai)

*Dashboard atualizado: 2025-09-08T19:03:17*

</div>
