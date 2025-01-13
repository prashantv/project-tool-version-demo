## Mise (self-bootstrapped)

This is a demo of a modified version of `mise generate bootstrap`
to bootstrap tools set up by mise automatically on first tool run.

It relies on direnv to modify PATH to include the tool bootstrap,
using `exa` as an example. Users can run it once in the dir without
any additional bootstrap.
