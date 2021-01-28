# whatsapp-text-to-html
Convert whatsapp backup text to beautiful html

An original backup whatsapp text file looks like this:
```
18/10/2019 à 13:10 - Me: message ...
18/10/2019 à 13:10 - You: message ...
18/10/2019 à 10:41 - Me: ‎ message
18/10/2019 à 10:41 - You: message ...
```

With your favourite text editor and good replace commands, convert it into that:
```
<div class="message"><div class="date">18/10/2019 à 13:10</div><div class="msg-body me">message ...</div></div>
<div class="message"><div class="date">18/10/2019 à 13:10</div><div class="msg-body you">message ...</div></div>
<div class="message"><div class="date">18/10/2019 à 13:10</div><div class="msg-body me">message ...</div></div>
<div class="message"><div class="date">18/10/2019 à 13:10</div><div class="msg-body you">message ...</div></div>
```

Then copy all to the `whatsapp-conversation.html` body.
