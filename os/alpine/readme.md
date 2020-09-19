# ALPINE

in order to connect to shell just:

```docker run -it alpine```

when --rm is used it removes the container when you exit it
```docker run -it --rm alpine```

so the real deal (for me) is to create a specific image with a specific name if i want to keep it after

```docker run -it -name aName alpine```
