**Roadiz** is a polymorphic CMS based on a node system that can handle many types of services. 
It is based on *Symfony Flex*, *Doctrine ORM*, *API Platform*, *Twig* for maximum performances and security.

Roadiz node system allows you to create your data schema and to organize your content as you want. 
We designed it to break technical constraints when creating tailor-made websites architectures and layouts.

### Latest news

- [🚀 Roadiz v2 has launched](news/2022-09-09.md)

### Documentation

- https://docs.roadiz.io
- [Development changelog](https://github.com/roadiz/core-bundle-dev-app/blob/main/CHANGELOG.md) (since v2.1)
- [Old development changelog](https://github.com/roadiz/core-bundle/blob/main/CHANGELOG.md) (before v2.1)

### Selected works 

- Les Célestins, Théâtre de Lyon: https://www.theatredescelestins.com
- Modelec, High-End electrical equipment: https://www.modelec.com/en
- Opéra de Lyon: https://www.opera-lyon.com/en
- Cité musicale - Metz: https://www.citemusicale-metz.fr
- Fraîche Design Thinking: https://www.fraichedesignthinking.com
- Amiral Gestion: https://www.amiralgestion.com/en
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
| **Roadiz development monorepo** | [![Unit tests, static analysis and code style](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/run-test.yml) [![Packages Split](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/split.yaml/badge.svg?branch=develop)](https://github.com/roadiz/core-bundle-dev-app/actions/workflows/split.yaml) |
| Skeleton | [![Run test status](https://github.com/roadiz/skeleton/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/skeleton/actions/workflows/run-test.yml) |
| Models | [![Run test status](https://github.com/roadiz/models/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/models/actions/workflows/run-test.yml) |
| Documents | [![Run test status](https://github.com/roadiz/documents/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/documents/actions/workflows/run-test.yml) |
| Core Bundle | [![Run test status](https://github.com/roadiz/core-bundle/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/core-bundle/actions/workflows/run-test.yml) |
| Compat Bundle | [![Run test status](https://github.com/roadiz/compat-bundle/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/compat-bundle/actions/workflows/run-test.yml) |
| Rozier Bundle | [![Run test status](https://github.com/roadiz/rozier-bundle/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/rozier-bundle/actions/workflows/run-test.yml) |
| Rozier theme | [![Run test status](https://github.com/roadiz/rozier/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/rozier/actions/workflows/run-test.yml) |
| User Bundle | [![Run test status](https://github.com/roadiz/user-bundle/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/user-bundle/actions/workflows/run-test.yml) |
| Font Bundle | [![Run test status](https://github.com/roadiz/font-bundle/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/font-bundle/actions/workflows/run-test.yml) |
| TwoFactor Bundle | [![Static analysis and code style](https://github.com/roadiz/two-factor-bundle/actions/workflows/run-test.yml/badge.svg)](https://github.com/roadiz/two-factor-bundle/actions/workflows/run-test.yml) |
| Documentation generator | [![Run test status](https://github.com/roadiz/doc-generator/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/doc-generator/actions/workflows/run-test.yml) |
| Typescript documentation generator | [![Run test status](https://github.com/roadiz/dts-generator/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/dts-generator/actions/workflows/run-test.yml) |
| Entity generator | [![Run test status](https://github.com/roadiz/entity-generator/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/entity-generator/actions/workflows/run-test.yml) |
| Jwt | [![Run test status](https://github.com/roadiz/jwt/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/jwt/actions/workflows/run-test.yml) |
| Markdown | [![Run test status](https://github.com/roadiz/markdown/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/markdown/actions/workflows/run-test.yml) |
| OpenID | [![Run test status](https://github.com/roadiz/openid/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/openid/actions/workflows/run-test.yml) |
| Random | [![Run test status](https://github.com/roadiz/random/actions/workflows/run-test.yml/badge.svg?branch=develop)](https://github.com/roadiz/random/actions/workflows/run-test.yml) |
