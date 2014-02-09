Started this program in C but realized that python will be much easier.  
First attempt at python program.  Same functionality as previous TCP 
server client model.  This implementation is half duplex.

client:send server:recieve -> client:recieve server:send
<p>This is how the communication works.  Once one end has sent message, sits idle until recieves message, then loops.</p>
<p>exit command is '.logout'</p>
