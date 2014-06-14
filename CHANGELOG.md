tellbot CHANGELOG
=================

### 0.3.3.0

- it’s now required to set a password when running the bot on a channel; that
  password will be asked when a user attempts to take control of the bot with
  `!do pwd action parameters`; that enables a user to reop, for instance, or
  make the bot say something, or whatever (!help for further information)
- removed the *!help* output when using `!help`
- made the bot a bit less rude ;)

### 0.3.2.0

- when a message is recorded for a specific user, the bot now lets you know
  in private

### 0.3.1.0

- tells are now private; the bot still outputs anything else on the channel

### 0.3.0.0

- it’s now possible to pass the nick of the tellbot on the command line

### 0.2.2.0

- The bot now only delivers a message at first message after join.

### 0.2.1.0

- The bot rejoins on kick

### 0.2.0.1

- Added support for IRC server anti-DDoS and netsplit
- Fixed issues with privileged folks
- The tellbot will not register stories for itself

### 0.2.0.0

- Fixed flood attempts
- Changed `!tell` behavior; now the tellbot will refuse to record your message(s) if
  the recipient is already in the same room as you and the tellbot – the
  recipient has to be out off the room – and it will tell the message(s) when
  the recipient joins

### 0.1.0.0

- Initial release