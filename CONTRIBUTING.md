# Contributing to G6CODERS

Merci de contribuer. / Thank you for contributing.

## English

### Before you start

- Read the repository README and `DEPLOYMENT.md` if it exists.
- Check open issues and discussions before starting work.
- For security issues, do **not** open a public issue — see [SECURITY.md](SECURITY.md).

### Access model

- **Contributors** have read access and work from a fork: fork → branch → pull request.
- **Maintainers** have write access and merge pull requests.
- Never push directly to `main`.

### Workflow

1. Fork the repository (or create a branch if you are a maintainer).
2. Create a short-lived branch:
   - `feat/<slug>`
   - `fix/<slug>`
   - `chore/<slug>`
   - `docs/<slug>`
3. Make focused commits using [Conventional Commits](https://www.conventionalcommits.org/):
   - `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, `test:`, `ci:`
4. Open a pull request against `main` and fill the template.
5. Wait for CI and one maintainer approval.
6. The maintainer squash-merges and deletes the branch.

### Quality bar

- Tests pass locally and in CI.
- No secrets, credentials, `.env` files, logs, or build artifacts.
- New behavior is documented in the README or `docs/`.
- Database changes include a migration and a rollback note.

### Review

- One maintainer approval is required.
- Authors do not merge their own pull requests, except documentation-only changes approved by a maintainer.
- Reviewers check correctness, security, tests, and documentation.

### Code of conduct

By participating, you agree to follow [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

---

## Français

### Avant de commencer

- Lisez le README du dépôt et `DEPLOYMENT.md` s'il existe.
- Consultez les issues ouvertes avant de commencer.
- Pour un problème de sécurité, n'ouvrez **pas** d'issue publique — voir [SECURITY.md](SECURITY.md).

### Modèle d'accès

- Les **contributeurs** ont un accès en lecture et travaillent depuis un fork : fork → branche → pull request.
- Les **mainteneurs** ont l'accès en écriture et fusionnent les pull requests.
- Ne poussez jamais directement sur `main`.

### Flux de travail

1. Forkez le dépôt (ou créez une branche si vous êtes mainteneur).
2. Créez une branche courte : `feat/<slug>`, `fix/<slug>`, `chore/<slug>`, `docs/<slug>`.
3. Faites des commits ciblés avec les [Conventional Commits](https://www.conventionalcommits.org/).
4. Ouvrez une pull request vers `main` et remplissez le modèle.
5. Attendez la CI et l'approbation d'un mainteneur.
6. Le mainteneur fait un squash merge et supprime la branche.

### Niveau de qualité

- Les tests passent en local et en CI.
- Aucun secret, identifiant, fichier `.env`, journal ou artefact de build.
- Le nouveau comportement est documenté dans le README ou `docs/`.
- Les changements de base de données incluent une migration et une procédure de rollback.

### Revue

- Une approbation de mainteneur est requise.
- Les auteurs ne fusionnent pas leurs propres pull requests, sauf pour une modification de documentation approuvée par un mainteneur.
- Les relecteurs vérifient la justesse, la sécurité, les tests et la documentation.

### Code de conduite

En participant, vous acceptez de respecter [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
