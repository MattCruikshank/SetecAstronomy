SetecAstronomy
==============

Explore ideas of how to have private communication on the internet.

The Moving Parts
----------------

- Everyone generates a Public / Private Key pair, used ONLY to sign for authentication (Signing Key)
- Everyone makes a promise, to generate a new Public / Private Key pair, at some high frequency (eg: daily)
- Everyone makes a promise, to only preserve Public / Private Key pairs, for some low multiple of that frequency (eg: three days)
- Everyone uses a mechanism to publish their current contact information, in a way that obfuscates who did the sending (low frequency onion routing), and everyone does it at the high frequency (eg: daily)
  - Alias
  - Current Public Key
  - Public Key used only for Signing (their real unique identifier)
  - Then they Sign the whole thing with their Signing Key

Discussion
----------

Imagine the government records all of your encrypted communications for five years.  Imagine that they have a particular message sent to you, that they want decrypted.  You no longer posess the Private Key, because you kept your promise of destroying them every three days, so you cannot be forced (by any means) to aid the government.
