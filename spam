const Discord = require('discord.js');
const client = new Discord.Client();
const token1 = "" //توكن حساب السبام
const idroom = ""// اي دي الروم


client.on('ready', async () => {
      let ReBeL = ["هلا بلزين تراني بوت تبند اشيلك","هي انا بولعها كريديتس لوووووول","Hi Im Credits Agaaaaaaaaain"]
  setInterval(() => {
client.channels.get(idroom).send(`${ReBeL[Math.floor(Math.random() *ReBeL.length)]}`);//لا تنسى تحط أيدي الروم
},4000);
});

client.on('message',function(message) {

  let args = message.content.split(" ").slice(1).join(" ");
  if(message.content.startsWith("1d")) {
    if(!args) return;
    message.channel.send(`${args}`); 
}
});




client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});



client.login(token1);
