# inviterator
script to invite everyone on a slack team to a particular channel.

## Usage
```
git clone git@github.com:makesaltlake/inviterator.git && cd inviterator
bundle install
SLACK_API_TOKEN="xoxp-..." bundle exec bin/inviterator some_channel
```

will invite all users on your Slack team to `#some_channel`. `xoxp-...` is a token you'll need to grab from <https://api.slack.com/custom-integrations/legacy-tokens>.
