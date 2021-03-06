# Girl Develop It: Intermediate Python

These are the slides for the [Girl Develop It](https://www.girldevelopit.com/) Intermediate Python class.
This class was originally taught by the Central VA chapter by Steven
Loria. Feel free to fork and modify this.

## Prerequisites for students

* Python 3 installed
* A text editor
* A terminal
* Basic Python knowledge (basic data types, flow control, loops)

## Classes

* Class 1: Object-oriented programming; Classes and objects; Inheritance; Errors
* Class 2: Modules; Packages; Installing and using 3rd party packages (pip and virtualenv)
* Class 3: How web apps work; Hands-on practice with Django
* Class 4: Hands-on practice cont'd; Testing; Putting it all together (final project)
    * Accompanying code for the final project is [here](https://github.com/sloria/smiles)

## For instructors

### Setting up

```
npm install
```

### Writing slides

Slides are written in Markdown and are built using [reveal-md](https://github.com/webpro/reveal-md).

Open class1.md and run the following to edit the class 1 slides with
livereload:

```
npm run class1
```

This will open the class1 slides and will autoreload when class1.md is
modified.


### Building and serving all slides

```
npm run serve
```

### Deploy to surge

```
npm run deploy
```

## License

[MIT Licensed](https://sloria.mit-license.org/).
