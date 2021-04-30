Hello ,

How i can create role with mentionable 

```js
mentionable: true
```
Let's fix this code
```js
client.on('message', async message=> {
  if(message.content.startsWith(prefix+"create-role")) {
 //  console.log("✅ test 1 ");
 message.guild.roles.create({data:{ name: "mox", color: "#ff98ff", mentionable:true, permissions:[]} ,reason: "need role for cool preson"
 })
message.channel.send("done")
  }
})

```
it's work


How i can edit role 
