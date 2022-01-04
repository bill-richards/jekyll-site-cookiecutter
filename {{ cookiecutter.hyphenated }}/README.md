# [_{{ cookiecutter.repository_name }}_](https://github.com/{{ cookiecutter.github_user }}{{ cookiecutter.subpath }})

Check out the repository's documentation [here](https://{{ cookiecutter.github_user }}.github.io{{ cookiecutter.subpath }}), it's a tale and one half ...

## Developing stuff

I'm doing this all on LINUX, and if you have any sense, you'll be doing that too: though, admittedly mine is running on WSL, so it seems that even the worst of us (that's me, not you) is capable of at least a modicum of redemption.

### What you'll need

- Ruby 

  get it installed like this `sudo apt-get install ruby`
- jekyll
  
  do that like this `gem install bundler jekyll`

### How you'll use it

1. Get the source code
   > did you know, that using most modern IDEs, you can also clone the repository using a Git plugin/extension/connector (usually)

```cmd
# using HTTPS
git clone https://github.com/{{ cookiecutter.github_user }}{{ cookiecutter.subpath }}
```

```cmd
#using SSH
git@github.com:{{ cookiecutter.github_user }}{{ cookiecutter.subpath }}.git
```

```cmd
# using Github.Cli
gh repo clone {{ cookiecutter.github_user }}{{ cookiecutter.subpath }}
```

2. Prepare your environment

```cmd
cd {{ cookiecutter.subpath }}/docs/

# Run this initially, and subsequently when you make changes to the Gemfile
bundle install
```
 3. Open up the code in your IDE of choice (or even in vi, notepad, whatever is your poison, you strange and bizarre individual).

 4. Run the website using [Jekyll](https://jekyllrb.com/)

```cmd
# to run the site locally
[sudo] bundle exec jekyll serve --livereload
```

### Making changes

If you want to make changes to the _Site Title_, for example, make that change [here](docs/_config.yml)

#### _**Nota bene**_

You do not need to invoke Jekyll on the server; it will be invoked every time a change is made to the containing repository.

## Don't repeat yourself (DRY)

Did I mention that you should out the repository's documentation [here](https://{{ cookiecutter.github_user }}.github.io{{ cookiecutter.subpath }}), and also, it's a tale and one half ...

## Other important stuff

> This repostory was generated from the [bill-richards/jekyll-site-template](https://github.com/bill-richards/jekyll-site-template), a [_template_]((https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-repository-from-a-template)) repository, which itself uses [bill-richards/jekyll-site-cookiecutter](https://github.com/bill-richards/jekyll-site-cookiecutter), a _cookiecutter_ repository. Go check them out to see how they work together, it's a pretty cool concept -and sadly I cannot take the credit for it, I was inspired by [this](https://github.com/simonw/python-lib-template-repository) repository by [simonw](https://github.com/simonw)
