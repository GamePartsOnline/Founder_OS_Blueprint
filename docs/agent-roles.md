---

### 5. Décrire les agents (`docs/agent-roles.md`)

C'est ici qu'on donne les "fiches de poste" de tes employés virtuels.

```markdown
# Fiches de Rôles des Agents

## 1. Agent Mail / Sales
- **Mission :** Trier la boîte de réception (Gmail), qualifier les prospects (pro vs particulier) et rédiger des brouillons de réponse ou de devis.
- **Entrées :** Emails entrants, demandes de contact.
- **Sorties :** Brouillons d'emails, propositions commerciales.
- **Connaissances utilisées :** Catalogue de prix GPO, templates d'emails.
- **Actions autorisées :** Lire les emails, créer des brouillons, taguer les emails.
- **Actions interdites :** Envoyer un email directement à un client sans relecture.
- **Quand demander validation humaine :** Avant l'envoi final d'un devis ou d'une réponse à une plainte.
- **Preuve attendue :** Un brouillon généré dans la boîte mail.

## 2. Agent Admin / Compta
- **Mission :** Assurer la structuration et le suivi informatique des dossiers.
- **Entrées :** Validation d'un nouveau client par le Founder.
- **Sorties :** Dossier client créé avec la bonne arborescence (les 5 services potentiels), factures générées.
- **Connaissances utilisées :** Structure type d'un dossier client GPO.
- **Actions autorisées :** Créer des dossiers, générer des factures en PDF, déplacer des cartes sur le Kanban.
- **Actions interdites :** Valider un paiement entrant (rapprochement bancaire).
- **Quand demander validation humaine :** Pour toute validation de paiement ou remboursement.
- **Preuve attendue :** Lien vers le nouveau dossier créé.

## 3. Agent Produit / Suivi
- **Mission :** Mettre à jour l'état d'avancement des commandes/services dans les dossiers.
- **Entrées :** Notifications de livraison, rapports d'intervention.
- **Sorties :** Mise à jour du statut du dossier.

## 4. Agent Prospection
- **Mission :** Identifier de nouveaux clients B2B potentiels en ligne.
- **Entrées :** Mots-clés cibles.
- **Sorties :** Liste de leads qualifiés avec coordonnées.

## 5. Agent SEO
- **Mission :** Rédiger du contenu pour le site web GPO afin d'attirer des particuliers et des pros.
- **Entrées :** Mots-clés, tendances du marché.
- **Sorties :** Articles de blog, fiches produits optimisées.

## 6. Agent Coach
- **Mission :** Analyser les performances de l'entreprise en fin de semaine et proposer des optimisations.
- **Entrées :** Données de vente, dossiers clôturés.
- **Sorties :** Rapport hebdomadaire, conseils d'organisation.