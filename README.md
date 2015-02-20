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
```
$ cd css/
$ bourbon install
$ neat install
$ bitters install
```

#### Neat grid settings and functions
This app manifest enables Neat functions in Bitters. Bitters "base/grid-settings" and Neat are imported before the rest of Bitters.

```
@import "bourbon"
@import 'normalize'
@import "base/grid-settings"
@import "neat"
@import "base/base"
```

### Neat helper import
In "base/grid-settings", you must import neat-helpers with a relative path when not in Rails.
```
@import "../neat/neat-helpers";
```

#### Compile
```
$ sass --watch css/app.sass:css/app.css
```
