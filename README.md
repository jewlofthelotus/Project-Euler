Project Euler
=============


## Makefile

Each language and problem can be run via the Makefile `make <language> ###`, for example:

```$ make sass 001```


## Language Notes

### LibSass

I'm using [libsass](https://github.com/hcatlin/libsass) and [node-sass](https://github.com/andrew/node-sass) to ensure the fastest compile times.  This does mean that some standard (`@debug`) and edge (3.3 list functions) Sass features are unavailable.

```$ make sass 001```


### Sass 3.3

I wanted to be able to use fancy Sass 3.3 list functions. So now just append `-33` to your `eulerXXX` filenames and use the `make sass33` command to run them.

```$ make sass33 001```
