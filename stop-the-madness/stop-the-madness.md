I just heard a bone-chilling story:

An IT company is charging extra if the client wants tests in their software. Both UI tests & unit tests.

So, client pays extra.

For tests.

In other words, the company *incentivises* test-less software.

This is madness and it must stop.

## A Fable

... in which I will try to describe an equivalent situation to the one above:

Bunny comes into Bear's car repair shop to get her car fixed.

Bear says to Bunny: "Ok, we see the problem, and we'll fix it but you have a choice: Either we use our old crappy tools to fix it and it will cost you 250 carrots, or we use our new cool tools to fix it which will cost you 500 carrots."

Bunny is at first puzzled as to why she even has to think about which tools Bear uses to fix her car, but she's intrigued...

Bunny assumes: "Oh, so the new tools are slower to work with?"

To which Bear answers: "No, we're much faster with the new tools."

Bunny: "But I thought you charge by the hour?"

Bear: "Our new company policy dictates we charge by the size of the toolset, and the new toolset is twice as big as the old one."

Flummoxed by this "logic", Bunny drives to another repair shop.

## Explanation

The "new tools" in the fable are of course tests. They are not at all "new" since the modern concept of software testing has been well known at least since the end of the 20th century - so, over 20 years now - but writing software without tests has been going on for even longer and is much more widespread, so "new" is appropriate in that context.

The mechanic's hours in the fable are actual developer hours. The paradox of the fable is that Bear will charge more when he uses the new tools  although he will spend less time (i.e. money) when using them.

This reasoning only makes sense if you charge per line of code which is possible if your IT organisation has such a business model, but unlikely since almost everything in the world is based on cost per time (like developer salaries).

It's counter-intuitive, but writing *more* code (implementation + tests) takes *less* time in total. This is especially true if you're writing all that code in TDD cycles simply because the implementation code will have higher quality.

And quality means speed.

Test-driven development leads you not only to test all the logic (where most of the bugs hide) and have a dependable regression safety net but also forces you to re-think how your software is structured, what are the sub-components and how are the interfaces between the sub-components designed. All this leads to code that is more readable and easier to change, meaning it's faster to build new features.

## Change your company, or...

There exist all around us IT companies which are "classical". Their developers are handed requirements recited to them over chat or written down in documents or task management systems. They proceed to implement the requirements. Some write tests for parts of their code.

Some of those developers see their codebases gradually turn to code-swamps which are at best hard to navigate and change, and at worst a huge business risk and cost sink for the company itself. Some of *those* developers recognise the value of writing comprehensive test suites and/or using test-driven development to grow the codebase in a sustainable way.

These developers may want to change the way they work. The way their team works. Perhaps even the way their company works. This is hard.

Imagine a developer trying to get their team to start writing tests when most in the team either cannot grasp the value or shrug it off as too much work. Imagine them trying to get their team to start doing TDD when most in the team don't see the benefits or cannot begin to look where to start. Add to that other organisational issues like management pressure, optimistic estimates (especially when given to developers together with requirements), communication disfunction etc. It's like pushing a huge boulder up a hill, only the boulder gets heavier and the hill gets steeper.

Now imagine the developer trying to do all that in a company which has test-less software as a part of their *commercial offering*. If a client didn't pay extra for tests, the developer *mustn't write tests*.

When a developer doesn't like their environment, they'll usually take [Martin Fowler's](https://martinfowler.com/aboutMe.html) witty advice:

> Change your company, or change your company

So think again when questioning your developers do they think time spent writing tests was worthwhile. In the software business tests (and especially TDD done properly) mean quality, quality means speed, and speed means profit.

## Some Light Reading

You don't have to agree with me. I'm just an "ordinary" developer. I again refer you to Martin Fowler, who is not:

> [High quality software is cheaper to produce](https://martinfowler.com/articles/is-quality-worth-cost.html)

Check it out. Now. Stop the madness.