Les prompts sont à executer dans l'ordre.

Vous pouvez utiliser n'importe quel assistant IA (ex: Le Chat de Mistral AI, ChatGPT de OpenAI, Claude de Anthropic, Gemini de Google, etc.).

Remarque: ils ont été testés avec Le Chat et ChatGPT.

Vous trouverez des fichiers d'exemples dans le dossier "Exemples": une annonce d'emploi et deux fiches de poste au format PDF.

Les fichiers sont nommés comme suit:
- Fichier 1: "Acme, Inc. - Annonce - Responsable du Support Client.pdf" : une annonce d'emploi pour le poste de Responsable du Support Client.
- Fichier 2: "Acme, Inc. - Fiche de Poste – Responsable du Support Client.pdf" : une fiche de poste pour un responsable du support client qui a servi de base pour l'annonce.
- Fichier 3: "Acme, Inc. - Fiche de Poste - Business Developer Senior - Permanent.pdf" : une fiche de poste pour un business developer senior que nous utiliserons pour générer une description de poste.

Le prompt que nous utiliserons pour générer la description de poste 'Business Developper Senior' est la suivante: 
```
Génère moi l'annonce pour la fiche de poste "Business Developper Senior" en prenant l'annonce "Responsable du Support Client" que j'ai mis en attachement comme modèle.
```
En attachant le fichier 1 et le fichier 3, l'assistant IA devrait générer une description de poste pour le poste de Business Developer Senior.

Les instructions à utiliser sont entre triple "Backtick" ```<prompt_a_utiliser/>```

Remarque: le caractère "Backtick" '`' (qui ressemble à un accent grave) est utilisé pour entourer du code. Il n'a pas de nom "officiel" en français.

Pour réaliser les exercices, créez une nouvelle conversation et suivez les instructions des fichiers dans l'ordre en copiant les instructions entre triple-backtick.