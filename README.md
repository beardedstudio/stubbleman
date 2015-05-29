# Stubbleman
## A Middleman Project Template with Stubble Integration.

This is an opinionated [Middleman](http://middlemanapp.com) template to get the team at [Bearded](http://bearded.com) building static sites quickly.

It encourages third-party asset management via [Bower](http://bower.io), and includes a default `bower.json` file.

It also enables Bearded's [Middleman Patterns](https://github.com/beardedstudio/middleman-patterns) by default.

### Features
* Sass
* Haml
* Bower for package management
* Modernizr
* Middleman Patterns
* LiveReload
* A `Procfile`, `Rakefile`, and `config.ru` for easy deployment to [Heroku][http://heroku.com]

### Installation
1. Clone (or download) this repository to: `~/.middleman/stubbleman`

	`git clone git@github.com:beardedstudio/stubbleman ~/.middleman/stubbleman`
2. Initialize a new Middleman project with the Stubbleman project template:

	`middleman init my_project --template=stubbleman`
3. You'll need to have [Bower](http://bower.io) installed to grab the third party asset packages. Then, run `bower install`.

### Updating
Once Stubbleman is in your `~/.middleman` directory, you can just pull the repository periodically to stay up-to-date!
```
cd ~/.middleman/stubbleman
git pull
```

