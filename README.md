# Greetings!

Mnemonic phrase generators require you to trust a rancom number generator.  This tool leverages
the random number generator to create a phrase but then lets you personally modify all but the
last word (the check word) so you need not trust the random number generator and don't need to
trust yourself to change all words very randomly (forms start random anyways).

You are trusting:
* The code you download from this project like `./bip39-chooser.html`
* All packages in `./package.json` and exported in `./src/coin-exports.js` (see https://www.npmjs.com/)
* Your computer and applications which ideally are all open source

Choosing the last word programmatically ensures you'll always have a valid Bip39 phrase.

Some benefits:

* Easier offline access to new strong safe and easy to type mnemonic phrases
* Create or validate mnemonic phrases from cold-storage or warm-storage (mostly offline)

# Run

- Download or clone this repository
- Run `npm install` then `npm run build` then open `./bip39-chooser.html`

# Directions

Select the size of the phrase (**12**, 15, 18, 21, **24**).  Make sure you know the proper
size for compatability.  Wallets don't always support every size and may not support BIP-39
at all.

![image](https://user-images.githubusercontent.com/204121/105982333-c008ec00-605c-11eb-8387-c58c437e9825.png)

Start with a strong random computer-generated phrase, Tweak any or all words.

![image](https://user-images.githubusercontent.com/204121/105982783-62c16a80-605d-11eb-815c-ffd6248994a9.png)

The last word is computer generated making your phrase a **Valid** BIP-39 Mnemonic Phrase.

![image](https://user-images.githubusercontent.com/204121/105982881-84baed00-605d-11eb-8f49-6cc24f14eecd.png)

Come back at any time to check any BIP-39 phrase.

![image](https://user-images.githubusercontent.com/204121/105983214-00b53500-605e-11eb-9bd6-ba326883fe9c.png)

Each word is checked against the BIP-39 dictionary and suggestions offered.

![image](https://user-images.githubusercontent.com/204121/105983253-11fe4180-605e-11eb-9d25-c79ecd46aa59.png)
