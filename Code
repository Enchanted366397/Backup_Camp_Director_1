const Discord = require("discord.js");
const client = new Discord.Client();

const prefix = "+"
client.on('ready', () => {
  client.user.setGame(prefix + "IsThePrefix")
  console.log(`Logged in as ${client.user.username}!`);
});



client.on('message', msg => {
  if (msg.content === prefix + 'Ping') {
    msg.reply('Pong!');
  }
});
client.on('message', msg => {
  if (msg.content === prefix + 'Good Morning') {
    msg.reply('Good Morning Half-Blood!');
  }
});
client.on('message', msg => {
  if (msg.content === prefix + 'CodeAlpha!') {
    msg.reply('Attention All Campers, Monsters Are Attacking!');
  }
});


client.login('token')
