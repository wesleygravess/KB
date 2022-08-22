# 🔏 How Secure Are My Funds on the ShapeShift Mobile App?

Your funds are secure as long as you maintain access to your password and/or your 12 word recovery phrase. If you lose one you can still access your funds using the other. However, if you lose your password AND your recovery phrase you will lose access to your funds forever and ShapeShift will not be able to recover your funds!

The ShapeShift Mobile App uses end-to-end encryption in order to allow users to maintain absolute and sole control over their private keys without the risk of losing access to their wallet if they misplace their device containing the only copy of their private key.&#x20;

All cryptographic keys are generated and managed by the user on their devices, and all encryption is done locally in the Client. ShapeShift servers are never in the position of learning your cryptographic keys. When the already encrypted data travels between the user’s device and our servers, it is encrypted and authenticated by TLS. All of the user’s sensitive data is encrypted when they create their account using 64 random bytes generated on the Client, protected using a password that they select.&#x20;

Nobody on earth knows this password besides the user as it never leaves the Client. Using a KDF algorithm, a Backup Recovery Phrase is derived from the password, to offer users a means of resetting their password in case they forget it. We do not have the ability to recover users’ data if they forget their password and lose their Backup Recovery Phrase (because of end-to-end security).

Stay safe out there - and store your backup seed phrase in a safe place.
