Usages
===

1. Install from Homebrew
```bash
brew install pyenv pyenv-virtualenv
```

2. Setup in `~/.zshrc`
```bash
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

3. Install virtualenv
```bash
pyenv install 3.9.13
pyenv virtualenv 3.9.13 my-ansible
pyenv virtualenv-delete my-ansible
```

4. Localize virtualenv
```bash
pyenv local my-ansible
```

5. Export and import packages
```bash
pip freeze > requirements.txt
pip install -r requirements.txt
```
