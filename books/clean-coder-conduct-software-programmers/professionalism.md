# Professionalism

## Professionalism = honor, pride, **responsability**, **accountability**

## Do no harm (software edition)

### Do no harm to **function**

Programmers, customers & employers all want the software to **work**.

Software developers shouldn't strive to be perfect, but to be responsible for their imperfections.

_Apologies are necessary, but insufficient._

Maturing in this profesion means bringing your error rate as close as you can to zero. It will never arrive at 0, but it's well worth the effort.

You should never ship buggy code to QA.

Side note: _[chagrined](https://dictionary.cambridge.org/dictionary/english/chagrined)_ is a very interesting word. It means _feeling disappointed or angry, especially by a failure or mistake_.

You must always test your code. All. Of. It.
100% code coverage is an asymptote, but then again, it's well worth the effort to strive towards it.

Some code is **hard to test** because it was **designed** to be hard to test. Code should be designed such that it is **easy** to test. The best way to do that is to write the tests first (e.g. practice **TDD**).

### Do no harm to **structure**

Don't sacrifice structure in the favor of function.
The structure of the code allows it to be flexible.

Compromising the structure = compromising the future.

_You must be able to make changes without exorbitant costs._

The _boy scout rule_

High test coverage = high confidence for developers to always keep making changes to the software. Code is kept flexible by flexing it all the time.

High test coverage also means a safety net for refactoring: you can run your test suites on a whim to check if the changes broke the software.
