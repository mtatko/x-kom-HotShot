### Storing secrets
```
$ wrangler secret put DISCORD_TOKEN
$ wrangler secret put DISCORD_PUBLIC_KEY
$ wrangler secret put DISCORD_APPLICATION_ID
```

//Register commands from commands.js, first time and every file change
$ curl http://localhost:8787/register