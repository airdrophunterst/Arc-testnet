# ᝰ.ᐟ Arc testnet multidapp, interact onchain

Link: [https://rewards.arcterminal.ai/loyalty](https://rewards.arcterminal.ai/loyalty?referral_code=KKFXDY2K)

Source: https://amautomarket.com/products/arc-testnet-automate

Tool được phát triển bởi nhóm tele Airdrop Hunter Siêu Tốc (https://t.me/airdrophuntersieutoc)

## 🚨 Attention Before Running Cli Version

I am not `responsible` for the possibility of an account being `banned`!

## 📎 Node cli version Script features

- Auto gm onchain
- Auto mint nft
- Auto add liquidity
- Auto faucet
- Auto swap
- Auto mint domain
- Auto deploy token
- Support proxy or not
- Mutiple threads, multiple accounts

## ✎ᝰ. RUNNING

- Install Dependency

```bash
pip install -r requirements.txt

playwright install chromium
```

- Setup config in .env

```bash
nano .env
```

- Setup input value

* proxy: http://user:pass@ip:port

```bash
nano data/proxy.txt
```

- privateKeys: how to get privateKeys => join my channel: https://t.me/airdrophuntersieutoc

```bash
nano data/privateKeys.txt
```

- Run the script

```bash
python main.py
```

#faucet

```bash
python faucte.py
```
