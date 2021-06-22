Using IRC with Mudlet!
======================

Hi! Mudlet has had support for IRC chat built into it since like the
sixteenth century. Except I discovered it myself like yesterday! So here
is how I've been using it:

**STEP 1:** Open https://web.libera.chat/ on your web browser and input
your desired nickname before clicking on big, green, Start button.

If it says the nickname is already registered, try a different nickname
with,

    /nick <different-nick-name>

That goes in the chat interface's input line!

**STEP 2:** Register your nickname with,

    /msg NickServ REGISTER YourPassword youremail@example.com

Switch out YourPassword with a password of your choosing and use an
actual email address there. You'll receive a verification code on it
with instructions on how to use that code to verify your account.

**STEP 3:** __VERY IMPORTANT!!__ Join the #libera-cloak channel with,

    /join #libera-cloak

And once you're in that channel, request a cloak with,

    !cloakme

Doing this much ensures your IP address is not visible to other users on
the network. If you've successfully received a cloak, attempting to join
the #libera-cloak channel again would forward you to the #libera-cloaked
channel.

You can read more about registration on the network here, https://libera.chat/guides/registration

**STEP 4:** Now that you have a cloaked nickname registered with the
libera network, you can close the session on the browser and switch to
Mudlet. Open Mudlet's profile preferences (`alt-P`) and switch to the
'Chat' tab. Fill in the following details:

    - Server address: irc.libera.chat
    - Port: 6667
    - Nickname: <the nickname you registered above>
    - Auto-join channels: ##playground

Click save to save and close the preferences dialog.

**STEP 5:** Download and install the MudletIRC package from:

    https://github.com/adayoung/MudletIRC

**STEP 6:** Open Mudlet's IRC client from the menu at Help > IRC. That
will open the IRC window and since Mudlet does not support supplying a
password, it'll be complaining about your nickname being registered and
requesting you to identify yourself. You can identify yourself with,

    /msg NickServ IDENTIFY YourNick YourPassword

Replace YourNick and YourPassword with the correct values.

**STEP 7:** Use the 'irc' alias in Mudlet's main window to talk! The IRC
chat lines will be formatted to resemble an in-game clan for you, except
the text is traveling through the IRC network instead of Achaea! Try,

    irc Hello, world!

The MudletIRC package implements the 'irc' alias to send messages to the
##playground channel, but feel free to join other channels or create
your own private channels!

Have a look at https://libera.chat/guides/creatingchannels for more
details. Be mindful of their namespace policy on how to create informal
channels! Their policy is documented here, https://libera.chat/chanreg

Please note stuff you send over IRC is not visible to the game's staff,
divine roles, or those sneaky mind sapiencing monks! The IRC network is
outside the game and should be used as an OOC channel (like Discord).
You are responsible for your activities and the game or anyone else for
that matter should not be held accountable in case you end up harming
yourself.

Welcome to IRC! The wild, wild west of the internet since 1988!

P.S.: Libera is only one of the many IRC networks out there. Do look
around for more! ^_^
