# {{ cookiecutter.repository_name }}

Check out the repository's documentation [here](https://{{ cookiecutter.domain }}{{ cookiecutter.subpath }})


```cmd
cd docs

# only run this initially, and then whenever you make changes to the Gemfile
bundle install

# to run the site locally
sudo bundle exec jekyll serve --livereload
```