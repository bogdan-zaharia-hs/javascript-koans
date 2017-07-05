# javascript-koans
Based on Edgecase's fantastic
[Ruby koans](http://github.com/edgecase/ruby_koans), the goal of the
Javascript koans is to teach you Javascript programming through
testing.

When you first run the koans, you'll be presented with a runtime error and a
stack trace indicating where the error occurred. Your goal is to make the
error go away. As you fix each error, you should learn something about the
Javascript language and functional programming in general.

Your journey towards Javascript enlightenment starts in the koans/1-AboutExpects.test.js file. These
koans will be very simple, so don't overthink them! As you progress through
more koans, more and more Javascript syntax will be introduced which will allow
you to solve more complicated problems and use more advanced techniques.

## Running the Koans

### Installing dependencies
First, you need to have [node](https://nodejs.org/en/)(which also comes with npm) and then [yarn](https://yarnpkg.com/en/) installed:
```sh
$ npm i -g yarn
```

Next, after cloning this repo, install dependencies with:
```sh
$ yarn
```

### Solving koans
For each file in `koans` folder, run the tests and make them pass one by one. The runner is in watch mode by default, so you just need to save the file and tests will run again.

```sh
$ yarn test koans/1-AboutExpects.test.js
```

### Suggested workflow
You can make a branch for each test and have your teammates review that for you, and merge into master only after adjusting the code to pass the review.

```sh
$ (master) git checkout -b 1-AboutExpects
$ (1-AboutExpects) git commit -m 'fix expect true'
... maybe other commits
$ (1-AboutExpects) git push origin 1-AboutExpects
```

### Acknowledgements
*  Dick Wall (the Java posse) - for bringing the idea of koans to my attention
*  Edgecase - for the great Ruby Koans
*  Douglas Crockford - for Javascript; the good bits

### [MIT Licensed](LICENSE)
