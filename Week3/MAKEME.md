# Homework Week 2

## Part 1 <small>- Reading material</small>

Read the HYF material on this week's topics:

- [ ] [try ... catch](https://github.com/HackYourFutureBelgium/fundamentals/blob/master/fundamentals/try_catch.md)
- [ ] [async & await](https://github.com/HackYourFutureBelgium/fundamentals/blob/master/fundamentals/async_await.md)
- [ ] [this keyword](https://github.com/HackYourFutureBelgium/fundamentals/blob/master/fundamentals/this.md)
- [ ] [OOP & ES6 classes](https://github.com/HackYourFutureBelgium/fundamentals/blob/master/fundamentals/oop_classes.md)

## Part 2 <small>- Finish last week's homework</small>
**Deadline: Tuesday evening**

This week's homework again builds upon that of last 2 weeks, so if you haven't already, finish that first, by following the [Week 1](../week1/MAKEME.md) and [Week 2](../week2/MAKEME.md) guides, step-by-step. If you want some intermediate comments/review after finishing that, go ahead and send it in with a pull request, as described there. Or you may immediately add this week's work and submit it as a whole.

## Part 3 <small>- Setup for this week</small>
**Deadline: Thursday evening**

Create a new branch based on the `week1` branch:

- [ ] Make sure that you committed all changes of your homework.
- [ ] Create a new `week3` branch:

   ```
   git checkout -b week3
   ```

## Part 4 <small>- This week's assignment</small>
**Deadline: Tursday evening**

You will continue to work on the file `index.js`.

- [ ] Refactor all `.then()` and `.catch()` methods with `async`/`await` and `try...catch`.

  > *Hint:* Make sure that your error handling code still works. See the [Week 2 guide](../week2/MAKEME.md) on how to force an error response from GitHub.

- [ ] Delcare your own `Repository` and `Contributor` classes. Give them all the properties that you're using in your app.

  > *Hint:* Use proper `camelCalse` for your classes' property names. Don't forget to update any references to these properties in the rest of your code!

- [ ] Your `Repository` class should also contain 2 methods:
  - `getContributors`, which fetches and returns an array of its `Contributor`s.
  - `getFormattedUpdateDate` which returns the properly formatted 'updated at' date and time, which you used during week 1.

- [ ] Your `Contributor` class should also contain a `render` method, which returns the `li` element with all its inner HTML; ready to be added to the `ul` element.

- [ ] Always immediately `map` fetched repositories and contributors into instances of these classes, and use their methods throughout your code.

- [ ] Bonus: feel free to add more methods to retrieve or transform more (related) data of these 2 entities.

## Part 5 <small>- Handing in your homework</small>
**Deadline: Thursday evening**

If necessary, review the instructions how to [Hand in homework](https://github.com/HackYourFuture/fundamentals/blob/master/fundamentals/homework_pr.md) using GitHub pull request.

To test whether your code will be accepted when you submit your homework as a pull request you need to ensure that it does not contain ESLinr errors. Open a terminal window in VSCode and type the following command:

```
npm test
```

If any errors or warnings are reported by this command you need to fix them before submitting a pull request.

In addition, check for the following:

- Have you removed all commented out code (should never be present in a PR)?
- Do the variable, function and argument names you created follow the [Naming Conventions](../../../../fundamentals/blob/master/fundamentals/naming_conventions.md)?
- Is your code well-formatted (see [Code Formatting](../../../../fundamentals/blob/master/fundamentals/code_formatting.md))?

If the answer is 'yes' to the preceding questions you are ready to follow these instructions:

1. Push your `week3` branch to GitHub:

   ```
   git push -u origin week3
   ```

2. Create a pull request for your `week3` branch.

Note:

1. Please remove all redundant, commented-out code and console.log's from your files before pushing your homework as finished. There is no need for your mentors to review this stuff.
2. Please make sure your code is well-formatted and follows the recommended naming conventions.

## Part 6 <small>- Prepare for the next module</small>
**Deadline: Before the start of the Node module**

Go trough the reading material in the [README.md](https://github.com/HackYourFuture/Node.js) of the Node repository to prepare for your next class.
