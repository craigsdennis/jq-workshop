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

## Learn more

The [tutorial is great](https://stedolan.github.io/jq/tutorial/) and [the manual](https://stedolan.github.io/jq/manual/) is thorough and well documented. Make sure to check out all the awesome things you can do!

Remember to use [jq play](https://jqplay.org) to explore!