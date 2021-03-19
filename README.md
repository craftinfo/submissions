# submissions

📩 Submit a craftinfo or crafthelp

If you have a craftinfo or a crafthelp, create an issue and send a link to your repository. 
If it is accepted your repository will be cloned and end up here.

Memo: the `-craftinfo` is there to disambiguate from the actual project (and the possibility of naming clashes in the cache).

## Craftinfo

A craftinfo is created whenever you say `mulle-sde craftinfo set` to tweak the build of a dependency.
It will contain various build flags or even a custom build script.

## Crafthelp

Many dependencies, maybe even most, don't need a special craftinfo. Possibly they don't even need any
tweaks to the dependency. Even then it is good to have a crafthelp, that either verifies that this
isn't needed or gives some help to the user, what he should do.
The help is just the README.md file in the repository.

A craftinfo is also a crafthelp and its README.md is also used.

