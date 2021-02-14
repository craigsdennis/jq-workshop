# Resources

## Dad Joke API

Get a random JSON formatted joke from [icanhazdadjoke API](https://icanhazdadjoke.com/api).

```bash
curl -H "Accept: application/json" -H "User-Agent: jq Workshop (https://github.com/craigsdennis/jq-workshop)" https://icanhazdadjoke.com/
```

## GitHub API

Get a list of recent events that occurred in the wonderful world of GitHub

```bash
curl https://api.github.com/events
```

## Patchbay Pub

Use the amazing [patchbay.pub](https://patchbay.pub/) to explore Webhook requests

```bash
curl https://patchbay.pub/pubsub/jq-workshop-webhook
```
