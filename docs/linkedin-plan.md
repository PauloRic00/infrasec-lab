# Plano de Conteúdo — LinkedIn

O progresso do projeto é registrado publicamente a cada sprint, sempre amarrado a uma entrega real do repositório — nunca anunciando algo ainda em andamento como concluído.

## Princípios de Integridade
- Só posta o que já está commitado, com link de evidência (PR, commit ou print de `/evidencias`).
- Fala como aprendiz ("aprendi a configurar X"), não como especialista.
- Nunca expõe dados sensíveis (IPs reais, senhas, tokens) nos prints.

---

## 1. Tabela de Controle de Posts

| # | Post | Gatilho | Status |
| :---: | :--- | :--- | :---: |
| **0** | Kickoff do projeto | Ao fechar Sprint 0 | ✅ Publicado 2026-10-16 |
| **1** | Rede e firewall no ar | Ao fechar Sprint 1 | — |
| **2** | Hardening aplicado | Ao fechar Sprint 2 | — |
| **3** | Identidade centralizada (IAM) | Ao fechar Sprint 3 | — |
| **4** | SOC montado (SIEM/IDS) | Ao fechar Sprint 4 | — |
| **5a** | Ataque ao vivo (meio da sprint) | Durante Sprint 5 | — |
| **5b** | Ataque x Defesa (MITRE ATT&CK) | Ao fechar Sprint 5 | — |
| **6** | Resposta a incidente | Ao fechar Sprint 6 | — |
| **7** | Vídeo + encerramento do projeto | Ao fechar Sprint 7 | — |

---

## 2. Cronograma Organizacional (Sprints + Posts)

| Sprint | Duração Estimada | Semana | Post(s) LinkedIn |
| :--- | :---: | :---: | :--- |
| **0 — Planejamento** | 3-5 dias | Semana 1 | Post 0 (kickoff) |
| **1 — Rede e firewall** | 1-2 semanas | Semana 2-3 | Post 1 |
| **2 — Servidores e hardening** | 1-2 semanas | Semana 4-5 | Post 2 |
| **3 — IAM (Samba AD DC)** | 1 semana | Semana 6 | Post 3 |
| **4 — Monitoramento** | 1-2 semanas | Semana 7-8 | Post 4 |
| **5 — Ataque e detecção** | 2 semanas | Semana 9-10 | Posts 5a e 5b |
| **6 — Vulnerabilidades e resposta** | 1-2 semanas | Semana 11-12 | Post 6 |
| **7 — Vitrine** | 1 semana | Semana 13 | Post 7 (vídeo final) |

*Total estimado: ~13 semanas (3 meses), com cadência de 1 post a cada 1-2 semanas.*

---

## 3. Templates de Post

### Post 0 — Kickoff:
> Comecei um projeto pessoal de laboratório de redes e cibersegurança: o **InfraSec Lab**.
> 
> A ideia é simular, do zero, uma infraestrutura corporativa segmentada — firewall, gestão de identidade, monitoramento e resposta a incidentes — documentando tudo publicamente no GitHub.
> 
> Sou estagiário de Help Desk e estudante de ADS, e quero usar esse projeto pra aplicar na prática o que venho estudando em redes e cibersegurança.
> 
> Repositório (atualizado a cada sprint): [Link do Repositório]
> 
> #cibersegurança #infraestrutura #redes #homelab #helpdesk

---

### Post Padrão — Fechamento de Sprint (usar nas Sprints 1, 2, 3, 4, 6):
> Sprint [N] do InfraSec Lab concluída: [Título da Sprint].
> 
> O que foi feito:
> - [Entrega 1]
> - [Entrega 2]
> 
> O que eu aprendi:
> [1-2 frases sobre o conceito/dificuldade superada]
> 
> Evidência: [Link do PR ou commit]
> 
> #cibersegurança #[tecnologia específica]

---

### Post 5a — Ataque ao vivo (meio da Sprint 5):
> Simulei um ataque de força bruta contra o meu próprio laboratório pra testar se a defesa detectava.
> 
> Resultado: o Wazuh disparou o alerta em [X segundos/minutos], mapeado na técnica T1110 do MITRE ATT&CK.
> 
> [Print do alerta mascarado]
> 
> #blueteam #redteam #mitreattack

---

### Post 7 — Encerramento:
> Depois de [X] semanas, terminei o InfraSec Lab: um laboratório completo de rede segmentada, com firewall, Active Directory via Samba, SIEM, IDS e simulação de ataques mapeados no MITRE ATT&CK.
> 
> [Vídeo de demonstração de 3-5 minutos]
> 
> Repositório completo: [Link do Repositório]
> 
> Esse projeto consolidou o que venho estudando em cibersegurança e redes, e é o case que mais me orgulho até aqui.
> 
> #cibersegurança #infraestrutura #portfolio