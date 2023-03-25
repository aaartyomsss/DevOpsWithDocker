Website can be checked at: https://small-violet-4260.fly.dev/

It is nothing but react + vite + ts template for the project

Only thing that should have been chaged in the provided default dockerfile from the fly.io is installation of the dev dependencies as the project uses TS and tsc is required in order to make build possible.

Rest was done accrodingly to the fly.io documentation and use of:

```
flyctl deploy
```

command
