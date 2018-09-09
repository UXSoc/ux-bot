# Howdy, bot builder!
## When you see "Show Live" in the upper left corner, your new bot app is live.
## Click the sunglasses to view your app, then go back to [Botkit Studio](https://studio.botkit.ai) to finish up.

### Having trouble?
* You should check [that your .env file](?path=.env:1:0) has all the correct tokens as created in your [provisioning step](https://github.com/howdyai/botkit/blob/master/docs/provisioning/).

* The [Botkit Studio knowledge base](https://botkit.groovehq.com/) contains in-depth information about using Botkit Studio, or you can [contact us](https://botkit.groovehq.com/knowledge_base/topics/contact-us-23) directly.

* *Raise your hand!* - Glitch allows users to ask the community for help directly from the editor! For more information on raising your hand, [read this blog post.](https://medium.com/glitch/just-raise-your-hand-how-glitch-helps-aa6564cb1685)

* Join our thriving community of Botkit developers and bot enthusiasts at large. Over 4500 members strong, [our open teams group](http://community.botkit.ai) is _the place_ for people interested in the art and science of making bots.

testing testing testing

# Syncing to Slack **Modfied from basic bot**

To sync the github repo with the slack page by first committing them running `npm run update`.

This should work if you have access the api-keys private repo and have it installed. To get access you need to be a contributor to https://github.com/jhburns/api-keys. Notify Jonathan Burns @jburns on slakc or email jburns@chapman.edu.

The keys for this project are under the sync-config-slack.json file and are required in the sync script.

## Getting books to work

The /books command uses a file in ./data/db/json/urls.json to store and read urls to distribute.

If it doesn't already exist, create it locally in glitch, NOT github. This ensures it is not changed between git reloads.