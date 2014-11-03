# Yeoman Bourbon Neat Generator

> [Yeoman](http://yeoman.io) generator for Bourbon Neat.


## Getting Started

###sd-generator-bourbon-neat
An easy and straight-forward generator to get you up and running with a full web framework using [Bourbon](http://bourbon.io/) and [Neat](http://neat.bourbon.io/). The generator installs Sass, Bourbon and Neat and gives an [HTML5 Boilerplate](http://html5boilerplate.com/) (it also auto generates a useful directory structure for a web project).

######Optional:
The generator also gives you options for installing [Normalize.css](http://necolas.github.io/normalize.css/) and [Modernizr](http://modernizr.com/)

Please let us know if you have any difficulties and comments/suggestions.

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```bash
$ npm install -g yo
```

### Running the generator

At this point, you have a working generator. The next logical step would be to run it and see if it works.

Since you're developing the generator locally, it's not yet available as a global npm module. A global module may be created and symlinked to a local one, using npm. Here's what you'll want to do:

On the command line, from the root of your generator project (in the generator-name/ folder), type:

```bash
npm link
```

```bash
$ yo sd-bourbon-neat
```

That'll install your project dependencies and symlink a global module to your local file. After npm is done, you'll be able to call yo name and you should see the console.log, defined earlier, rendered in the terminal. Congratulations, you just built your first generator!

### Getting To Know Yeoman

Yeoman has a heart of gold. He's a person with feelings and opinions, but he's very easy to work with. If you think he's too opinionated, he can be easily convinced.

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).

## License

MIT
=======
generator-bourbon-neat
======================

Yeoman generator for a website using thoughtbot's Bourbon Neat. Options for Normalize and Modernizr!
