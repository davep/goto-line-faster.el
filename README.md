# goto-line-faster.el

## Commentary

`goto-line-faster.el` provides a utility command that binds <kbd>M-g</kbd>
followed by a number (<kbd>1</kbd> through <kbd>9</kbd>) to an invocation of
`goto-line` with the number pre-populated in the input in the minibuffer.

I wrote this because I've never liked <kbd>M-g</kbd> <kbd>g</kbd> (or
<kbd>M-g</kbd> <kbd>M-g</kbd>) as a way to go to a line number and my muscle
memory from way back (and other editing environments) is that <kbd>M-g</kbd>
alone starts prompting for a line number; but I'd like to use some of the
other <kbd>M-g</kbd>-prefixed key bindings too. This pretty much gives me
the best of both worlds.

Please note that this version of the code is very different from [the
original
version](https://github.com/davep/goto-line-faster.el/blob/775ed4916eb8028252db4dae5a0b71d865568638/goto-line-faster.el),
with [@phil-s](https://github.com/phil-s) [providing a much cleaner
approach](https://github.com/davep/goto-line-faster.el/issues/1).

[//]: # (README.md ends here)
