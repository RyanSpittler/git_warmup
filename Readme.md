# Git Warmup
## for Building the Toolbelt of a Junior Ruby on Rails Developer
------

This is an inclass practice project for Git and Github.

Steps:
Command line:

```
    echo '2.1.5' > .ruby-version
    echo 'this_folder' > .ruby-gemset
    cd .
    mine .
```

RubyMine
Create Gemfile with:

```ruby
source 'https://rubygems.org'

gem 'guard-rubocop'
```

Command line:

```
    bundle
    guard init
    guard
```

RubyMine
Create .rubocop.yml with:

```ruby
AllCops:
  Exclude:
    - 'Guardfile'
StringLiterals:
  Enabled: false
```

Command line:

```
    git init
    git status
    git add .rubocop.yml .ruby-version .ruby-gemset Gemfile Gemfile.lock Guardfile Readme.md
    git commit -m 'Initial Commit'
    git log
```
