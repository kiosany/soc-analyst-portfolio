# 🛡️ SOC Analyst / Blue Team Portfolio

> **Nome:** LUCAS SOARES  
> **Formação:** Graduação em Análise e Desenvolvimento de Sistemas | Pós-graduação em Segurança da Informação  
> **Objetivo:** SOC Analyst Nível 1 / Blue Team  
> **LinkedIn:** [linkedin.com/in/seu-perfil]  
> **Contato:** KUKIUON@HOTMAIL.COM

---

## 📋 Índice

1. [Sobre este repositório](#sobre-este-repositório)
2. [Roadmap de Estudos](#roadmap-de-estudos)
3. [Labs Resolvidos](#labs-resolvidos)
4. [Projetos](#projetos)
5. [Certificações](#certificações)
6. [Ferramentas que domino](#ferramentas-que-domino)
7. [Contato](#contato)

---

## 🎯 Sobre este repositório

Este repositório documenta minha jornada de aprendizado em cibersegurança defensiva (Blue Team) e operações de segurança (SOC). Aqui você encontra:

- Write-ups de labs práticos resolvidos
- Projetos de home lab
- Análises de incidentes simulados
- Documentação de ferramentas e técnicas aprendidas

> **Nota:** Este portfólio está em constante atualização. Última atualização: [DATA]

---

## 🗺️ Roadmap de Estudos

| Fase | Período | Status | Descrição |
|------|---------|--------|-----------|
| 🟢 Fase 1: Reconstrução | Meses 1-3 | ⏳ Em andamento | Redes, Linux, Windows, SQL |
| 🟡 Fase 2: Ferramentas SOC | Meses 4-6 | ⏳ Pendente | Splunk, LetsDefend, Wireshark |
| 🔴 Fase 3: Blue Team Prático | Meses 7-9 | ⏳ Pendente | BTLO, CyberDefenders, Forense |
| 🟣 Fase 4: Mercado | Meses 10-12 | ⏳ Pendente | Portfólio, currículo, entrevistas |

---

## 🧪 Labs Resolvidos

### LetsDefend

| # | Alerta/Incidente | Tipo | Data | Status | Link |
|---|-----------------|------|------|--------|------|
| 1 | [Título do alerta] | [Phishing/Malware/Network] | DD/MM/AAAA | ✅ Resolvido | [Write-up](./letsdefend/alerta-01.md) |
| 2 | [Título do alerta] | [Phishing/Malware/Network] | DD/MM/AAAA | ✅ Resolvido | [Write-up](./letsdefend/alerta-02.md) |
| 3 | ... | ... | ... | ... | ... |

### Blue Team Labs Online (BTLO)

| # | Desafio | Categoria | Dificuldade | Data | Status | Link |
|---|---------|-----------|-------------|------|--------|------|
| 1 | [Nome do desafio] | [Network Forensics/Memory/Logs] | Starter | DD/MM/AAAA | ✅ Resolvido | [Write-up](./btlo/desafio-01.md) |
| 2 | ... | ... | ... | ... | ... | ... |

### CyberDefenders

| # | Lab | Categoria | Data | Status | Link |
|---|-----|-----------|------|--------|------|
| 1 | [Nome do lab] | [Memory/Network/Disk] | DD/MM/AAAA | ✅ Resolvido | [Write-up](./cyberdefenders/lab-01.md) |
| 2 | ... | ... | ... | ... | ... |

---

## 🏗️ Projetos

### 1. Home Lab SOC

**Descrição:** Ambiente completo de simulação de SOC para prática de análise de logs e detecção de ameaças.

**Componentes:**
- SIEM: [Splunk Free / ELK Stack]
- Firewall/IDS: [Suricata / Snort]
- Endpoint: [Windows 10 VM + Sysmon]
- Atacante: [Kali Linux VM]

**Arquitetura:**
```
[Internet] → [Firewall] → [SIEM] → [Endpoints Windows/Linux]
                ↓
            [IDS/IPS]
```

**Documentação:** [Link para pasta do projeto](./home-lab/)

---

### 2. Análise de Tráfego de Rede

**Descrição:** Captura e análise de tráfego de rede suspeito usando Wireshark.

**Arquivos:**
- [Captura PCAP 1](./projetos/wireshark/captura-01.pcap) — Análise de tráfego DNS suspeito
- [Captura PCAP 2](./projetos/wireshark/captura-02.pcap) — Análise de comunicação C2

**Write-ups:**
- [Análise 1](./projetos/wireshark/analise-01.md)
- [Análise 2](./projetos/wireshark/analise-02.md)

---

### 3. Análise de Logs Windows

**Descrição:** Identificação de atividade suspeita em logs do Windows Event Viewer.

**Ferramentas:** Event Viewer, PowerShell, Splunk

**Casos:**
- [Login suspeito fora do horário](./projetos/logs-windows/login-suspeito.md)
- [Execução de PowerShell malicioso](./projetos/logs-windows/powershell-malicioso.md)

---

## 📜 Certificações

| Certificação | Instituição | Data | Status | Credencial |
|-------------|-------------|------|--------|------------|
| Introdução à Cibersegurança | Cisco Networking Academy | DD/MM/AAAA | ✅ Concluído | [Verificar](link) |
| Splunk Fundamentals 1 | Splunk | DD/MM/AAAA | ✅ Concluído | [Verificar](link) |
| Segurança da Informação para Todos | Escola Virtual.GOV | DD/MM/AAAA | ✅ Concluído | [Verificar](link) |
| CompTIA Security+ | CompTIA | DD/MM/AAAA | ⏳ Em andamento | - |

---

## 🛠️ Ferramentas que Domino

### SIEM
- [x] Splunk (básico)
- [ ] QRadar
- [ ] Microsoft Sentinel
- [ ] ELK Stack

### Análise de Rede
- [x] Wireshark
- [ ] Zeek / Bro
- [ ] NetworkMiner

### Forense
- [ ] Volatility
- [ ] Autopsy
- [ ] Redline
- [ ] FTK Imager

### Endpoint
- [ ] Sysmon
- [ ] Velociraptor
- [ ] OSSEC / Wazuh

### Outras
- [x] Linux (comandos básicos)
- [x] Windows Event Viewer
- [x] PowerShell (básico)
- [ ] Python para segurança
- [ ] YARA

---

## 📊 Estatísticas de Progresso

```
Labs resolvidos:        [██░░░░░░░░] 15/100
Desafios BTLO:          [██░░░░░░░░] 5/50
Certificações:          [███░░░░░░░] 3/10
Horas de estudo:        [████░░░░░░] 120/500
```

---

## 📝 Template de Write-up

Use este template para documentar cada lab:

```markdown
# Título do Incidente/Lab

## Informações Gerais
- **Plataforma:** [LetsDefend / BTLO / CyberDefenders]
- **Data:** DD/MM/AAAA
- **Dificuldade:** [Fácil / Médio / Difícil]
- **Categoria:** [Phishing / Malware / Network Forensics / Memory Forensics]

## Descrição do Incidente
[Resumo do que aconteceu — o alerta, o desafio, o cenário]

## Análise

### Passo 1: [Primeira ação]
[O que você fez, o que encontrou]

### Passo 2: [Segunda ação]
[O que você fez, o que encontrou]

## Indicadores de Compromisso (IOCs)
| Tipo | Valor |
|------|-------|
| IP | 192.168.1.100 |
| Domínio | malicious-domain.com |
| Hash | abc123... |
| Email | attacker@evil.com |

## Conclusão
[O que aconteceu, quem foi o atacante, como foi resolvido]

## Lições Aprendidas
[O que você aprendeu com este lab]

## Referências
- [Link 1]
- [Link 2]
```

---

## 📞 Contato

- 💼 LinkedIn: [linkedin.com/in/seu-perfil]
- 📧 Email: [seu-email@email.com]
- 🐦 Twitter/X: [@seu-usuario]
- 💬 Discord: [seu-usuario#0000]

---

> ⭐ **Se este repositório te ajudou, deixe uma estrela!**  
> 🔄 **Este portfólio é atualizado semanalmente.**
