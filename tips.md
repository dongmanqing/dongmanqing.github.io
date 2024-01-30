### Checking the template on your personal devices

1. Check and set ruby status via rbenv.
   1. Check ruby version
      ```bash
      ruby -v
      ```
   2. If ruby version is incorrect (e.g., lower than 3.0), then use rbenv to set the correct ruby version
      ```bash
      export PATH="$HOME/.rbenv/shims:$PATH"
      rbenv local 3.1.4
      ```
   3. Check ruby version again, if it is correct, go to the next step.
2. Local setup
   ```bash
    bundle install
    bundle exec jekyll serve --lsi
   ```


### If python version is not correct, use pyenv
1. Check python 
   ```bash
   python --version
   ```
2. If no python. Check if pyenv is activated
   ```bash
   pyenv --version
   ```
3. If no pyenv, activate pyenv
   ```bash
   export PATH="$HOME/.pyenv/bin:$PATH"
   eval "$(pyenv init --path)"
   eval "$(pyenv virtualenv-init -)"
   ```

4. Set the python version
```bash
pyenv local 3.9.18
```

