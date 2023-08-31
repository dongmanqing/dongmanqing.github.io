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
   


