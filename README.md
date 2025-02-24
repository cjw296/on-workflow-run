# Exploring Github's `on: workflow-run` actions trigger

...which is pretty limited, sadly.

[This stack overflow answer](https://stackoverflow.com/a/65081720/216229) gives more detail on 
what's going on, but basically,  it appears that the trigger only runs workflows on the default 
branch, `main` for this repo, so you can't develop these workflows on a branch, which is annoying.

