# KNOWLEDGE — ZEDECK Open Source

> Critérios de governança, lista viva de projetos e regra de ouro para o repositório vitrine.

---

## 🛑 Regra R6 (AGENTS.md) — Vitrine, Nunca Fonte

* **Regra R6:** O repositório `opensource` é uma **vitrine pública de exibição**, nunca a fonte de lógica de negócio da empresa. Se qualquer agente ou desenvolvedor for escrever código de produto ou faturamento aqui, a tarefa está no repositório errado.

---

## 📋 Lista Viva de Inclusão ("O que está dentro vs O que está fora")

| Projeto / Componente | Status na Vitrine | Justificativa |
| :--- | :--- | :--- |
| **`mozdev-platform`** | ✅ Listado | Iniciativa 100% comunitária e aberta. |
| **`core-sdk`** | ✅ Listado | Pacotes de consumo público para integrações OAuth2. |
| **`design-system/tokens`** | ⏳ Candidato Futuro | Tokens neutros de design assim que homologados. |
| **`core` (Identity/Mail/Drive)** | ❌ Fora | Infraestrutura crítica proprietária (privada). |
| **`dashboard`** | ❌ Fora | Centro de comando interno e dados sigilosos (privado). |
| **`hosting` (Billing/IaC)** | ❌ Fora | Núcleo de negócio fechado e provisionamento. |
| **`infra`** | ❌ Fora | Acesso e segredos de infraestrutura restritos. |
