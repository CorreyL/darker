0.2.0 / 2020-03-11
------------------

- Feature: Retry with a larger ``git diff -U<context_lines>`` option after producing a
  re-formatted Python file which fails to result in an identical AST.
- Bugfix: Run `isort` first, and only then do the detailed ``git diff`` for Black.
