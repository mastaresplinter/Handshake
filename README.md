# Handshake
Handshake protocol verification in ProVerif

The protocol was updated so that the injective correspondence holds properly. Removing (hopefully) the possibility of a replay attack

1. Generated a new nonce at the beginning of Alices process
2. Alice sends nonce to Bob in public
3. Bob receives nonce and adds it to his signature
4. Alices confirms that the nonce in the signature is the same as she generated.
