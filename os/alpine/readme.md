# ALPINE

in order to connect to shell just:

```docker run -it alpine```

when --rm is used it removes the container when you exit it
```docker run -it --rm alpine```

so the real deal (for me) is to create a specific image with a specific name if i want to keep it after

```docker run -it -name aName alpine```

if you don't see that container after exiting it like i do with a simple ```docker ps``` you will need a ```docker ps -a```

next thing you need to do is to start/restart it in order to docker to consider it as a real container ```docker restart aName```

So the rules are like all other containers if you want to rm it just ```docker stop aName``` into ```docker rm aName```

maybe not the best way to do all this things but im that newbie, i guess mail me.