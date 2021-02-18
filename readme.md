# Git, Github & Open Source Software
> Materiale di riferimento al corso.

### Software
* [Git](https://git-scm.com/) (official download)
* [Gitkraken](https://www.gitkraken.com/) (GUI client)
* [gh-pages](https://www.npmjs.com/package/gh-pages) (pacchetto NPM per pubblicazione su GH Pages da riga di comando)

### Documentazione
* [Creazione chiavi SSH](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
* [Creazione di "secrets"](https://docs.github.com/en/actions/reference/encrypted-secrets)
* [Aggiungere domini custom su GH Pages](https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain)
* [Come pubblicare app React create in CRA su GH Pages](https://create-react-app.dev/docs/deployment/#github-pages)

### Concetti
* [Git handbook](https://guides.github.com/introduction/git-handbook/) (basi)
* [Choose a license](https://choosealicense.com/) (comparazione licenze Open Source)
* [GitFlow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) (pattern branching/collaborazione)
* [Sane Github labeling](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63) (considerazioni sulle nomenclature della labels di un repo)

### Actions workflows
* [React + GH pages](./workflows/react-pages.yml) - a ogni commit su `master` viene buildata un'applicazione React e pubblicata nella relativa Github Page.
<!-- 
* Test on PR - a ogni pull request su `master` vengono eseguiti unit test con Jest e E2E test con Cypress.
* Flutter .apk - a ogni commit su `master` viene buildata un'applicazione Android da una codebase Flutter e il file `.apk` viene poi pubblicato nelle releases del repo.
-->

### License
MIT