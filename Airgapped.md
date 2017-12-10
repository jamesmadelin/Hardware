## Air Gapped Computer

An air gapped computer is a computer that has been fully configured and is then disconnected from the Internet and all other networks.  This helps to secure the data on the computer from hackers as physical access to the computer is needed in order to use it. 

It is advised that, once air gapped the computer is NEVER reconnected to any network, EVER.

It is also advisable to use full disk encryption on an air gapped computer to prevent unauthorised physical access.

It is possible to configure a computer with the necessary tools to handle seeds, keys and to sign bitcoin transactions.  Then air gap it, and only then do you then load it with your private keys.  This allows you to keep your keys offline yet available to sign transactions.  For setup instructions please visit http://docs.electrum.org/en/latest/coldstorage.html

Please note an online computer is needed to create a transaction and to broadcast it to the network after it has been signed.  You transfer the unsigned transaction to and from the air gapped computer using a webcam or removable media, never a network connection. 

Always backup any private keys used on an air gapped computer, preferably using Mnemonic wallet as outlined above.
