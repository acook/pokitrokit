PokitRokit
===========

So, I'm playing around with sockets and TCP servers.

I was just going to call it "socket" but that was clearly going to cause issues. Then I was just going to go with "sock" but thats no good either, then I realized "pocket" was kinda like a sock and it also rhymed with socket, and it was all downhill from there.

Usage
-----

0. Just run the script
  `./pokitrockit`
0. And then you can connect to it however you want, its runs on port 2000. I recommend telnet for the lulz.
  'telnet localhost 2000'
0. It only knows two commands
  * disconnect : closes the connection to the client
  * die : which kills the server

It will also echo whatever you type back at you (and in the sever output) and every 10 seconds it will give you a timestamp after a solitary carriage return.

