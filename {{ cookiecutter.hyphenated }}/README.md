# {{ cookiecutter.repository_name }}

Check out the repository's documentation [here](https://{{ cookiecutter.domain }}{{ cookiecutter.subpath }})


```cmd
cd {{ cookiecutter.repository_name }}/docs/

# Run this initially, and subsequently when you make changes to the Gemfile
bundle install

# to run the site locally
[sudo] bundle exec jekyll serve --livereload
```

#### _**Nota bene**_

You do not need to invoke Jekyll on the server; it will be invoked every time a change is made to the containing repository.