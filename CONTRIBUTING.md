# Contributing

* FILES: if contributing a script, it should be named after the data it gets, e.g., RAIS.r or CEIS.py. if you have several scripts under the same institution, make a folder, e.g. /IBGE/censo.jl, /IBGE/PNAD.sh.

* OPEN-SOURCE: this is an open-source project. therefore, everything in it should be open-source (programming languages, file formats, etc).

* LANGUAGE: this project's language is English, even if most of our contributors are Brazilian and we're working with Brazilian data. Our purpose is to make this project welcoming of international contributors and maybe even spread its idea abroad.

* STANDARDS: whenever possible use (or convert things to) the international standard. for most data, this will mean changing the encoding from latin1 to UTF-8 and changing the date format from DD/MM/YYYY to YYYY-MM-DD. standardizing will make it easier to work with several databases together. if you find something that should be an exception, open an issue or talk to the coordinators.

* ATTRIBUTION: please be aware when employing third-party software: check if their license is compatible with your use. (if unsure, ask). **always** attribute someone else's work to them. similarly, when you complete any work, you must attribute it to yourself under an open-source license. check [here](https://choosealicense.com/) if unsure about a license, or just pick the MIT license which is our default. all files contributed must be prefixed by their license and author in a comment. 

* DOCUMENTATION: all code must be thoroughly documented. undocumented code or incomprehensible code will not be accepted. choose clarity over performance unless you absolutely have to pick the latter. (hint: [you almost never will](http://softwareengineering.stackexchange.com/questions/80084/is-premature-optimization-really-the-root-of-all-evil).)
    - for Python, this would mean something like [this](http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html). you can propose a standard for your language of use, talk to the coordinators.

* 

## step-by-step

let's review the steps to start contributing:

* Fork the project to your account.

* Choose a path in your computer to store the project, go to it.

* Clone the fork that you have just done to this path using the terminal command

    `git clone https://github.com/YOUR-USERNAME/alea-gov`

* At this point, you should have an exact copy of the latest version of the project on your machine.

Congratulations! Now you have a version of the repository in your machine. If you want to contribute and help to build this incredible project, keep reading!

* do your modifications.

* now you must check if your version is up-to-date with the original repository:

    `git pull https://github.com/labFGV/alea-gov`

* if you have a merge conflict, you must solve it before committing your work.

* now you stage and commit your work:

    ```
    git add YOUR_FILES
    git commit -m "YOUR COMMIT MESSAGE"
    ```

* now you push the changes to your repo:
    `git push origin master`

* finally, you go to https://github.com/labFGV/alea-gov and complete your pull request.

## HOW-TOs

* git: google and stackoverflow are your best friends.
    - dudler's simple guide: [en](https://rogerdudler.github.io/git-guide/), [pt-br](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
    - [official docs](https://git-scm.com/doc)
    - [oh, sh*t, git!](http://ohshitgit.com/)
    - github [guides](https://guides.github.com/) & [help](https://help.github.com/)

* 

## contributors

contributors are listed under [contributors.md](CONTRIBUTORS.md). only people who have had a pull request accepted are listed as contributors.