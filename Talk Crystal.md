# Talk Crystal



> Slick as Ruby, fast as C

Syntaxe proche, inspirée de Ruby, sans pour autant vouloir être source compatible(Crystal ne peut compiler du code Ruby).

Type inference, strong macro system, batteries included standard lib

Performance : benchmarks

Language créé par des développeurs rubyistes de Manas (boîte argentine) en 2011.



Au début, language écrit en Ruby puis compilateur écrit  en Crystal  lui-même utilisant LLVM.

Nombreux rubystes se sont greffés au projet, en portant notamment des gems.



## Concrètement, à quoi ça ressemble ?

Installable sur Linux et mac.

`crystal init app my-first-crystal-app`

`crystal format`

`shards install`

`crystal run app.src`

`crystal build --release app.src`

`crystal spec`

Linter / analyse statique de code : Ameba



## Les shards

Pas de dépôt centralisé, mais des sites, listes (awesome crystal shards)

shards.yml



## Points de repères pour Rubyistes



Rspec == crystal spec

Sinatra == Kemal



[Crystal for rubyists](https://www.crystalforrubyists.com/)

Pas de REPL, mais Crystal play ou carc.in



## Eco-système

Avant tout : api.crystal-lang.org

JSON, YAML, XML, CSV, HTML et même Markdown

Http, openssl, OAuth2

zip, gzip...

Puis awesome crystal shards

Développement web :

* Kemal
* Amber
* Lucky

OpenFaas, Heroku, ...

Auto-promo :

Cadmium pour NLP

## Communauté

gitter

crystal forums

### Futur

**Crystal 1.0**

- Parallélisme par défaut
- Support de Windows
- Ce que LLVM apportera (WASM, openCL, Vulkan..)

### Crystal est-il pour vous ?

Oui, si la performance est clé.

Oui, si c'est un micro-service ou  une API.

Non, si vous avez besoin de windows(pour le moment)

Non, si vous avez besoin de l'éco-système de Ruby et de RoR pour sortir un projet complet rapidement.



