**Roadiz** is a polymorphic CMS based on a node system that can handle many types of services. 
It is based on *Symfony Flex*, *Doctrine ORM*, *API Platform*, *Twig* for maximum performances and security.

Roadiz node system allows you to create your data schema and to organize your content as you want. 
We designed it to break technical constraints when creating tailor-made websites architectures and layouts.

### Documentation

- https://docs.roadiz.io
- [Development changelog](https://github.com/roadiz/core-bundle-dev-app/blob/main/CHANGELOG.md) (since v2.1)
- [Old development changelog](https://github.com/roadiz/core-bundle/blob/main/CHANGELOG.md) (before v2.1)
- [🚀 Roadiz v2 has launched](https://github.com/roadiz/.github/blob/main/news/2022-09-09.md)

### Selected works 

- CENTQUATRE - Paris: https://www.104.fr/
- Memento - Pôle des patrimoines de Vaucluse: https://memento.vaucluse.fr/
- Théâtre du Rond-Point - Paris: https://www.theatredurondpoint.fr/
- La Comédie - Saint-Étienne: https://www.lacomedie.fr/
- Cité internationale de la Tapisserie d'Aubusson: https://www.cite-tapisserie.fr/
- Les Nuits de Fourvière: https://www.nuitsdefourviere.com
- Musée du Mémorial de Verdun: https://memorial-verdun.fr
- Les Célestins, Théâtre de Lyon: https://www.theatredescelestins.com
- Modelec, High-End electrical equipment: https://www.modelec.com/en
- Opéra de Lyon: https://www.opera-lyon.com/en
- Cité musicale - Metz: https://www.citemusicale-metz.fr
- Fraîche Design Thinking: https://www.fraichedesignthinking.com
- Unanime Architectes: https://www.unanime.fr
- Centre de Musique Baroque de Versailles - Expodcast: https://expodcast.cmbv.fr/en 
- Klépierre: https://www.klepierre.com/en
- Les Fauteuils de l’Opéra de Paris: https://fauteuils.operadeparis.fr/en
- Prison Insider: https://www.prison-insider.com

### Development monorepo

Since Roadiz v2.1, all Roadiz packages have been moved to [a single monorepo](https://github.com/roadiz/core-bundle-dev-app) to ensure code and version consistency and a smooth development environment. Each Roadiz sub-package is automatically splitted by Github Actions and versioned into existing `roadiz/*` repositories. These repositories will be *read-only* from now.

### Development pipelines

| Package  | Github actions         |
| :------- | :--------------------- |
| **Roadiz development monorepo** | [![Unit tests, static analysis and code style](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/run-test.yml) [![Packages Split](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/split.yaml/badge.svg?branch=develop)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/split.yaml) [![Deploy VitePress documentation to Pages for production releases](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/deploy-docs.yml/badge.svg)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/deploy-docs.yml) [![Build Rozier static assets (JS/CSS)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/build-assets.yml/badge.svg)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/build-assets.yml) |
| Skeleton | [![Run test status](https://github.com/roadiz/skeleton/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/skeleton/actions/workflows/run-test.yml) |
