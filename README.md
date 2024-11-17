const { Client,Discord } = require('discord.js-selfbot-v13');
const client = new Client(); 
////
client.on('ready', () => {
  console.log(client.user.tag)
})
const {userAccount} = require("sphinx-run");
new userAccount(client, Discord).autoReaction({
    channel: 1304400447565598730'',
    user: '',
    customBotId: ['']
});
client.login(process.env.token);
