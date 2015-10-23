# aperoweb Toulouse

[http://toulouse.aperoweb.fr](http://toulouse.aperoweb.fr)

Le rendez-vous des gens qui font le web sur Toulouse

## Installer

Vous devez avoir [Node.js](https://nodejs.org/en/) d'installé sur votre machine.

Sous Mac OSX, je vous recommande d'utiliser [Homebrew](http://brew.sh/index_fr.html) ou [nvm](https://github.com/creationix/nvm).

Clônez le dépôt sur votre ordinateur et placez vous dans le répertoire correspondant, puis installez les dépendances du projet :

```
npm install
```

## Développer

Pour compiler la feuille de style et surveiller les changements apportés :

```
❯ npm run watch-css

> aperoweb-toulouse@1.0.0 watch-css ~/code/aperoweb-toulouse
> ./bin/watch-css

23 Oct 20:11:25 - [nodemon] 1.7.3
23 Oct 20:11:25 - [nodemon] to restart at any time, enter `rs`
23 Oct 20:11:25 - [nodemon] watching: *.*
23 Oct 20:11:25 - [nodemon] starting `npm run build-css && npm run clean-css`

> aperoweb-toulouse@1.0.0 build-css ~/code/aperoweb-toulouse
> ./bin/build-css

Rendering Complete, saving .css file...
Wrote CSS to ~/code/aperoweb-toulouse/css/styles.css

> aperoweb-toulouse@1.0.0 clean-css ~/code/aperoweb-toulouse
> ./bin/clean-css

23 Oct 20:11:26 - [nodemon] clean exit - waiting for changes before restart
```

## Licence

Ce code est publié sous [licence MIT](https://github.com/aperoweb-toulouse/aperoweb-toulouse.github.com/blob/master/LICENSE). 
