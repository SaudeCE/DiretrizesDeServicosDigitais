## Sobre este projeto

O Programa Brasil é um remix de iniciativas que emergiram no Brasil e no mundo na última década, a partir da proposta de atualização de governos para o século 21. Acreditamos em um governo construído por pessoas e para as pessoas.

Para tanto, nos propomos a organizar uma rede de profissionais de tecnologia, comunicação e artes gráficas que trabalhe junto com os governos do Brasil para desenvolver aplicações de código aberto e, com isso, promover a abertura, participação e eficiência, assim como gerar uma rede multisetorial de praticantes da inovação cívica dentro de uma plataforma de "civic hacking".

## Queremos ouvir você
We encourage your feedback and suggestions on these documents. Content and feature suggestions and discussions are welcome via [GitHub Issues](https://github.com/WhiteHouse/playbook/issues). You may also propose changes to the content directly by submitting a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests").

You don't need to install any software to suggest a change. To propose a change from your browser, [select a play in the `_plays` folder](https://github.com/WhiteHouse/playbook/tree/gh-pages/_plays "Link to the Plays Markdown files"), or open the [TechFAR file](https://github.com/WhiteHouse/playbook/blob/gh-pages/_includes/techfar-online.md "Link to the TechFAR Markdown File"). You can use Github's in-browser editor to edit files and submit a "pull request" for your changes to be merged into the document. 

If you would like to see and discuss the changes that other people have proposed, [visit the "Pull Requests" section](https://github.com/WhiteHouse/playbook/pulls "Link to the Pull Requests Section of Github") and [browse the issues](https://github.com/WhiteHouse/playbook/issues "Link to the Issues Section of Github").

Feedback collected before September 1, 2014 will be considered for inclusion in the next release of the Digital Services Playbook and the TechFAR Handbook.

## Technical Details

The Playbook and the TechFAR Handbook are compiled from [Markdown](https://help.github.com/articles/github-flavored-markdown "Link to More Information About Markdown") files using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). To propose a specific change, you can submit a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") with your change to one of these source Markdown files. The Plays from the Playbook are [available in the `_plays` folder](https://github.com/WhiteHouse/playbook/tree/gh-pages/_plays "Link to the Plays Markdown files"), while the [TechFAR is contained in this markdown file](https://github.com/WhiteHouse/playbook/blob/gh-pages/_includes/techfar-online.md "Link to the TechFAR Markdown File").

You can also use Github's in-browser editing feature to make an edit to one of these Markdown files and submit your change for consideration without needing to install any additional software.

### Running the Site Locally

To run the site locally on your own computer (most helpful for previewing your own changes), you will need to install Jekyll and other dependencies:

If you don't already have Ruby and Bundler installed, follow [the first two steps in these Jekyll installation instructions](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll "Installation instructions for Jekyll").

Next, [fork this repository](http://help.github.com/fork-a-repo/ "Instructions for Forking Your Repository") and clone it on your computer.

Navigate to the folder on your computer, and run the command `$ bundle install` at the command line prompt.

To run the site locally, run `jekyll serve --watch`, then visit `http://localhost:4000/` in your browser to preview the site.

### Editing the Stylesheets

This project uses [Sass](http://sass-lang.com/ "Link to Learn More About Sass") for managing its style sheets. If you would like to make changes to the site's styles, you should edit the `assets/sass/styles.css.scss` file. 
**Do not** make changes to the `styles.css` file directly, as this file is auto-generated from the `styles.css.scss` file.

To compile changes in the `styles.css.scss` Sass file into a new `styles.css` file, you can run: `$ sass --watch assets/sass/styles.css.scss:assets/css/styles.css`. This command will watch for any changes you make to the Sass file and automatically update the CSS file, making it easy to check your work when you are running the site locally (see above).

## License
As a work of the United States Government, this project is in the public domain within the United States.

Additionally, we waive copyright and related rights in the work worldwide through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
