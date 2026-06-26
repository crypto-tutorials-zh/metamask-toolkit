# MetaMask Private Key Management Reference

# MetaMask Private Key Management Reference

## Private Key vs. Seed Phrase

| Aspect | Private Key | Seed Phrase (Mnemonic) |
|--------|-------------|------------------------|
| Format | 64 hexadecimal characters | 12 or 24 English words |
| Purpose | Controls a single account | Recovers all accounts in wallet |
| Exposure risk | Compromises only that account | Compromises entire wallet |
| Backup method | Store offline, hardware wallet | Write down, never digitize |
| Derivation | Direct account control | Generates infinite keys via HD path |

## Critical Security Checklist

- [ ] Never paste private keys into online tools
- [ ] Never screenshot or email seed phrases
- [ ] Store seed phrase physically separate from passwords
- [ ] Verify phishing URLs before entering credentials
- [ ] Use hardware wallet (Ledger, Trezor) for large holdings
- [ ] Test recovery on fresh installation before relying on backups
- [ ] Keep MetaMask extension updated
- [ ] Enable additional security (2FA, biometric lock)

## Emergency Response Checklist (If Compromised)

1. **Immediate:** Move all assets to a new, secure wallet
2. **Revoke:** Cancel token approvals (check revoke.cash)
3. **Monitor:** Watch old address for suspicious activity
4. **Report:** Contact exchange support if funds were there
5. **Analyze:** Review transaction logs to trace breach origin
6. **Replace:** Create new MetaMask wallet with fresh seed phrase

## Export & Import Procedures (Summary)

### Exporting Private Key
- Open MetaMask → Account Details → Export Private Key
- Authenticate with password
- Store in secure, offline location only

### Importing Private Key
- Create new MetaMask instance or select wallet
- Use "Import Account" → paste private key
- Never use for new funds; treat as legacy account only

## Recommended Wallet Security Stack

1. **Daily use:** MetaMask (small amounts)
2. **Medium holdings:** Hardware wallet (Ledger Live, Trezor)
3. **Long-term cold storage:** Paper wallet or air-gapped device
4. **Backup:** Encrypted external drive + physical seed phrase (separate location)

---
*This reference is a curated summary for developers and advanced users. Always consult official MetaMask documentation (metamask.io) before performing critical operations.*

## Reference

[trendkoin](https://trendkoin.com/wallet/metamask-private-key)
