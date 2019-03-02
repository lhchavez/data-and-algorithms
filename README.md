# data-and-algorithms

Let's go over data structures and algorithms together!

We will use [Cracking the Coding Interview Book](http://www.crackingthecodinginterview.com/) as reference.

Feel free to add your solutions in your programming language of choice 😃

## Contributing

To get started...
 
1. 🍴 [Fork](https://github.com/techqueria/data-and-algorithms#fork-destination-box) this repository
2. 🔨 Commit your changes to your forked repo
3. 🎉 Open a new [pull request](https://github.com/techqueria/data-and-algorithms/compare) with changes from your forked repo and get it approved!
    * To pull down the most recent changes on this repo, make this branch your upstream

Check out [Noé Lomelí](https://github.com/noelomeli)'s video for [visual directions](https://www.youtube.com/watch?v=sv97x3yPbrw)

## Join Slack Channel

Request an invite here: [techqueria.org/slack](https://techqueria.org/communities/slack/)

Follow along with the community on the `#data-and-algorithms` channel on our Slack.

Make sure to also check out our `#python` `#ruby` `#javascript` and `#golang` channels while you're there.

## General advice

* Try to keep [all your changes
  small](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/).
  By splitting your change in more manageable chunks you'll be able to make
  progress faster since non-controversial chunks will be approved and merged
  faster. Since each individual program is <200LOC, it is ideal to make each
  one be its own review. You'll get better mileage out of the small network of
  (volunteer!) reviewers.
    * It is also [very hard to correctly
      review](https://blog.skyliner.io/ship-small-diffs-741308bec0d1) large
      changes. Sometimes there's a psychological barrier to simply start doing
      a large review.
* Try running an automated tool that ensures all your code is [formatted
  consistently](https://medium.freecodecamp.org/the-100-correct-coding-style-guide-5b594a1655f0).
  Most code editors can be configured to automatically invoke the tool upon
  saving to not even have to think about it. Some recommendations:
    * Python: [yapf](https://github.com/google/yapf).
    * JavaScript: [prettier](https://prettier.io).
    * C++/Java: [clang-format](https://clang.llvm.org/docs/ClangFormat.html).
    * Go: [go fmt](https://golang.org/cmd/gofmt/).
* Try following an industry standard [style
  guide](http://google.github.io/styleguide/). In addition to code formatting,
  each of those guides is written to further increase consistency, reduce
  discussions about presentation, and prevent some common mistakes. The
  following have been arbitrarily chosen since they have an automated tool:
    * Python: [flake8](https://gitlab.com/pycqa/flake8).
    * Go: [golint](https://github.com/golang/lint).
* Structure your programs like unit tests. That way you are able to clearly
  define test cases, which lets you follow [Test-Driven
  Development](https://en.wikipedia.org/wiki/Test-driven_development) and
  ensure that you don't accidentally introduce regressions once you start
  making changes to the code to fix bugs.
* More minor things:
    * Follow the [guard clause
      pattern](https://refactoring.com/catalog/replaceNestedConditionalWithGuardClauses.html)
      whenever it is possible.
