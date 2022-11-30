# Starterkit für das Anfertigen von Qualifikationsarbeiten mit LaTeX

## Installation

### Installation durch GitHub Fork (präferierte Installation)

- Erstellen Sie sich einen GitHub-Account
- Erstellen Sie einen GitHub Fork dieses GitHub-Repository - folgen Sie dazu der Anleitung : https://docs.github.com/en/get-started/quickstart/fork-a-repo?tool=webui#forking-a-repository
- Optional: Erstellen Sie einen Verweis (upstream-Link) auf das originäre GitHub-Repository - folgen Sie dazu der Anleitung : https://docs.github.com/en/get-started/quickstart/fork-a-repo?tool=webui#configuring-git-to-sync-your-fork-with-the-original-repository
- Optional: Synchronisieren Sie Ihren Fork mit diesem originären GitHub-Repository bei Bedarf - folgen Sie dazu der Anleitung: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork

Zu den optionalen Schritten in Kurzform:

`git remote add upstream https://github.com/Lehrstuhl-BWL-EvIS/latex-starterkit-abschlussarbeiten.git` 

`git fetch upstream`

`git checkout main`

`git merge upstream/main`


Ihre Verbesserungsvorschläge für das Starterkit können Sie uns gerne per "Pull Request" zur Verfügung stellen - folgen Sie dazu der Anleitung : https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests


### Installation durch "Download ZIP" 

- Klicken Sie auf den grünen Button "<> Code" auf der Startseite dieses GitHub-Repository und wählen Sie "Download ZIP", um ein Zip-Archiv des Starterkits zu erhalten
- Entpacken Sie das Zip-Archiv in ein Verzeichnis Ihrer Wahl

## Test und Setzen des Beispieldokuments

`pdflatex main.tex`

`biber main`

`pdflatex main.tex`

`pdflatex main.tex`

oder mit LaTeXmk : siehe https://ctan.org/pkg/latexmk :

`latexmk main.tex`

## Anleitung 

Für Hinweise zur Nutzung und Konfiguration siehe das Beispieldokument (main.pdf)
