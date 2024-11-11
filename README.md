# digital_transversality_ontology

Une ontologie unifiée pour les bâtiments intelligents intégrant tous les aspects: capacités, systèmes, équipements, espaces et utilisateurs.

## 🎯 Objectif

Cette ontologie vise à fournir un modèle de données standardisé pour le concept de transversalité digitale

## 📚 Structure de l'Ontologie

L'ontologie est organisée autour de concepts clés :
- **Attentes (Expectations)** : Objectifs et niveaux de performance visés
- **Capacités (Capabilities)** : Moyens mis en œuvre
- **Systèmes (Systems)** : Composants techniques
- **Équipements (Equipment)** : Matériel physique
- **Espaces (Spaces)** : Organisation spatiale
- **Utilisateurs (Users)** : Acteurs et rôles
- **Transversalité Numérique** : Continuité et cohérence des données

## 🛠 Technologies

- Format : OWL (Web Ontology Language)
- Compatibilité : Protégé, TopBraid, etc.
- Validation : Shapes Constraint Language (SHACL)


## 📋 Roadmap

- [ ] Validation SHACL complète
- [ ] Ajout de cas d'usage supplémentaires
- [ ] Intégration avec d'autres standards (BrickSchema, Project Haystack, etc.)
- [ ] Extension pour les smart cities
- [ ] Développement d'outils de visualisation

## 🤝 Comment Utiliser

```turtle
# Exemple d'utilisation en SPARQL
PREFIX smart: <http://www.synaptik.tech/smart_building#>

SELECT ?system ?capacity
WHERE {
    ?system a smart:System ;
            smart:provides ?capacity .
}
```

## 📄 Licence

Ce projet est sous licence BSD 3-Clause. Vous êtes libre de contribuer et de réutiliser cette ontologie pour des applications variées dans le Smart Building, tout en respectant les conditions de la licence.


## Contact
Pour toute question, n’hésitez pas à nous contacter via la section "Issues" ou par email à contact@synaptik.tech



