## Willkommen, mutiger Maintainer der LUG-LD Webseite!

Dieses README gibt einen kurzen Überblick darüber, was wo ist, wie was funktioniert und was wie getan werden kann.

Die LUG-LD Webseite lug-ld.de wird als **Github** **Pages** gehostet. Alles was dafür nötig ist liegt in diesem Repo.

### Zwei Möglichkeiten der Bearbeitung

1. Direkt in Github mit dem eingebauten Web-Editor. Dazu braucht man die passenden Rechte im Repo, vergeben kann das @casartar und @halbrot.
2. Das Repo auf den lokalen Rechner clonen, bearbeiten, pushen (Pull request erzeugen). Einer der Admins muss den PR dann prüfen und mergen.


### Gestaltung

Github Pages funktionieren so, das nach jeder Änderung im Repo eine statische Seite erzeugt wird. Änderungen sind meist nach wenigen Sekunden bis Minuten sichtbar, man muss nix tun. Der Generator für die statische Seite ist **Jekyll**. Jekyll verwendet __Templates__ zur Darstellung, zusammen mit dem CSS und ein paar Scripts macht das das **Theme** aus. Die lug-ld.de Webseite verwendet das Theme **jekyll-theme-minimal**.

In der Datei **_config.yaml** wird festgelegt
- welches Theme verwendet wird
- wie bestimmte Variablen gesetzt werden. Welche Variablen das Theme zur Verfügung stellt, findet man im [Repo der Template](https://github.com/pages-themes/minimal) .





## Welcome to Linux User Group Landau

You can use the [editor on GitHub](https://github.com/LUG-LD/lug-ld.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LUG-LD/lug-ld.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
