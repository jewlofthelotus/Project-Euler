Project Euler
=============


## Makefile

Each language and problem can be run via the Makefile `make <language> ###`, for example:

```$ make sass 001```


## Language Notes

### Sass

I'm using [libsass](https://github.com/hcatlin/libsass) and [node-sass](https://github.com/andrew/node-sass) to ensure the fastest compile times.  This does mean that some standard (`@debug`) and edge (3.3 list functions) Sass features are unavailable.
