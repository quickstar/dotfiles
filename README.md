## Installation

```sh
git clone git@github.com:quickstar/dotfiles.git
cd dotfiles/git
git config --global include.path "$(pwd)/.gitconfig.template"
```
The first command clones the repository into your current directory. Then we switch to that directory and adding the template file to our global git config.

>WARNING: If you already have an include section in your .gitconfig file, the previous command will overwrite it. In that case, just edit your include section and add another path property with the path to the gitconfig.aliases file.