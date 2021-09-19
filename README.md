# bounty5
this is bounty 5 project for gnolang

# Note
I checked the code of romelukaku and he changed much both in base source and base logic of gnokey. I see it as so dangerous in the long run.
 
I implement only ed25519 generation while preserving as much base code and base logic as I can. 
 
I borrow Entropy functionality from romelukaku code.

I am not sure if romelukaku way or my way is better.

# Installing
1. Run install_gnokey.sh to install gnokey lib

```
bash install_gnokey.sh
```

2. To add secp256k1 key using gnokey and custom entropy

```
gnokey add your_key_name_1 --type secp256k1 --entropy
```

3. To add ed25519 key using gnokey and custom entorpy

```
gnokey add your_key_name_2 --type ed25519 --entropy
```
