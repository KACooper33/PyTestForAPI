# PyTestForAPI
Initially following https://youtu.be/7dgQRVqF1N0?si=ac4dzr8SfYiK4g7E to get started

# Python Setup
Install pyenv
 - brew Update
 - brew install pyenv
 - Add the following to ~/.zprofile
    $ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zprofile
    $ echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zprofile
    $ echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zprofile
 - Install supporting libraries with brew: brew install openssl readline sqlite3 xz zlib
 - Install specific version of python: pyenv install 3.12.2
 - After installing a new python version run: pyenv rehash
 - Set python version: pyenv local 3.12.2




