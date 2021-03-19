# tipping-bot

Azure function which calls a slack channel webhook to post a leaderboard from the ESPN Footy Tipping competition. Needs two app configuration variables:
- `COMP_URL` The *widget* URL for the tipping competition. 
- `SLACK_HOOK_URL` A slack channel webhook.
