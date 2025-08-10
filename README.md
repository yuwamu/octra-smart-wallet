# octra smart wallet

a simple crypto wallet that works like a website with passkey login.

## how it works

- visit wallet.octra.app 
- create wallet with face id/fingerprint (no passwords, no seed phrases)
- your passkey generates your private key
- send transactions by confirming with face id/fingerprint
- works on any device that supports passkeys

## for users

```
first time: create passkey → wallet created
returning: use passkey → wallet unlocked
send money: confirm with passkey → transaction sent
```

## features

- no browser extension needed
- no seed phrases to lose
- works across all your devices
- popup confirms each transaction
- standard octra wallet (eoa)

## security

- private key derived from your passkey
- passkey stored securely on your device
- only you can access with biometrics
- no servers store your keys

simple as a website, secure as hardware wallet.
