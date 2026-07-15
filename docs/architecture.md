# Architecture de GPO Founder OS

Voici le schéma de fonctionnement de l'OS. L'orchestrateur reçoit la demande (ex: un email client) et la distribue au bon agent. La mémoire (Vault) est centralisée.

```mermaid
graph TD
    User((Client / Founder)) -->|Requête / Email| Orchestrateur[Orchestrateur OS]
    
    Orchestrateur --> AgentMail[Agent Mail / Sales]
    Orchestrateur --> AgentAdmin[Agent Admin / Compta]
    Orchestrateur --> AgentProduit[Agent Produit / Suivi Dossier]
    Orchestrateur --> AgentProspec[Agent Prospection]
    Orchestrateur --> AgentSEO[Agent SEO / Marketing]
    Orchestrateur --> AgentCoach[Agent Coach / Stratégie]

    AgentMail -.->|Lit/Écrit| Vault[(Vault / Mémoire Centrale)]
    AgentAdmin -.->|Lit/Écrit| Vault
    AgentProduit -.->|Lit/Écrit| Vault
    AgentProspec -.->|Lit/Écrit| Vault
    AgentSEO -.->|Lit/Écrit| Vault
    AgentCoach -.->|Lit/Écrit| Vault