# Bourbon example
[Bourbon](http://bourbon.io/), [Neat](http://neat.bourbon.io/), [Bitters](http://bitters.bourbon.io/), [Refills](http://refills.bourbon.io/) usage example.  
This example is forked from [moreformore's bourbon example](https://github.com/moremorefor/bourbon_example).


## Preview
<img src="./preview/example.png" alt="example preview" width="90%" height="90%" />

## Getting Started
#### Install gems
```
$ gem install sass
$ gem install bourbon
$ gem install neat
$ gem install bitters
```

#### Install Borbon, Neat, Bitters
Import bourbon and neat with leading underscores.

```
$ cd css/
$ bourbon install --path _bourbon/
$ neat install --path _neat/
$ bitters install
```

#### Neat grid settings and functions
This fork enables Neat functions in Bitters. I've added @import "grid-settings" before Neat, and imported the rest of bitters after.

```
@import "bourbon"
@import 'normalize'
@import "base/grid-settings"
@import "neat"
@import "base/base"

```

#### Compile
```
$ sass --watch css/app.sass:css/app.css
```
