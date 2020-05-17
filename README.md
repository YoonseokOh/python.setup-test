# python.setup-test
Django setup test project

## Mac OS setup guide
### brew pyenv install
```
brew install pyenv
```
### use fixed python version
```
pyenv install 3.8.0
pyenv global 3.8.0
```

#### Set at the terminal
Init by .bash_profile
```
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n eval "$(pyenv init -)"\nfi' >> ~/.bash_profile
```
Init by .zshrc
```
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n eval "$(pyenv init -)"\nfi' >> ~/.zshrc
```

## set python venv
python -m venv venv