# Installation

Add `retweet_bot` to the main `playbook.yml`. Use `retweetbot` ansible tag to only deploy this role.

The application is installed `/apps/retweet_bot/`. Make sure you have a valid `config` file at `/apps/retweet_bot/config`. See: `/apps/retweet_bot/config.sample` for example.

The bot runs every 5mins by default, for search new tweetable tweets.
