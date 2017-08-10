
# 757rb OO TDD Workshop

Inspired by [Sandi Metz 99 Bottles Book](https://github.com/sandimetz/99bottles). The goal is to write only the code needed to make the test(s) pass. Progress through all 8 tests to complete the exercise.


## Setup Instructions

Clone this repo and bundle all required gems.

```bash
$ git clone https://github.com/757rb/tdd-workshop
$ cd tdd-workshop
$ bundle install
```

## Run The Tests

In the same terminal widow. Type the following:

```bash
$ bundle exec guard
```

This project bundles Guard which makes running your tests automatically happen once you save a file. The exercise is best done when your editor and terminal open side by side. You should see something like this.

![OO TDD Exercise Example - Side by Side Code & Tests](https://user-images.githubusercontent.com/2381/29176067-d1ab6026-7db8-11e7-99a6-0504dbd3fc59.png)


## The Exercise

The above image shows we have 1 failing test and 7 pending (skipped) tests. Your job is to write enough code to make the test pass. In this example, you would have to open up the `bottles.rb` file and write a method called `#verse` which outputs the needed string.

Once this test passes, proceed down to the second test and remove the line with the word/method `skip` on it. Hit save. You will presented with another test to make pass. Step and repeat till all 8 tests pass.

Beware! Sometimes making one test pass makes the previous test(s) fail. This is the fun part. You must refactor the code as you learn more about the objects interface. There are no wrong answers! Whatever makes the test pass is good code :)


## Share Your Work

Share your gist of your `bottles.rb` in a new issue or make a pull request. Share and learn.

