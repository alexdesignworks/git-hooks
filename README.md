[![Circle CI](https://circleci.com/gh/alexdesignworks/git-hooks.svg?style=svg)](https://circleci.com/gh/alexdesignworks/git-hooks)

Useful git hooks
================

commit-msg
----------
Allows to reject incorrectly formatted commit messages.

Shipped with self testing functionality to ease custom rule development.

Possible commit formats:
* [PRJ-123] Verb in the past tense ending with a dot at the end.
* [PRJ, PRJ-123] Verb in the past tense ending with a dot at the end.
* [PRJ-321, PRJ-123] Verb in the past tense ending with a dot at the end.
* [PRJ] Verb in the past tense ending with a dot at the end.
* Verb in the past tense ending with a dot at the end.
* Verb in the past tense ending with a dot at the end. Another sentence with a dot.

## Installing
Run from directory where hook needs to be installed:
```
curl -O -s https://raw.githubusercontent.com/alexdesignworks/git-hooks/master/commit-msg && php commit-msg INSTALL && rm commit-msg
```

Or manually check out this repo and run `php commit-msg INSTALL`.
