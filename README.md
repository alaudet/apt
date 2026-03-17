## Signing Keys

Packages in this repository are signed with the Linuxnorth Archive key.

**Linuxnorth Archive key**
Fingerprint: `BA6D FDD5 12D4 4F9B E585  365B 5EF7 174D 662D FAF8`

This key is cross-signed by Al Audet's personal GPG key:

**Al Audet personal key**
Fingerprint: `0607 0380 D7FB BFEE 391B  4592 32FE FA08 C643 840B`

To verify:
```bash
gpg --recv-keys 5EF7174D662DFAF8
gpg --check-sigs "Linuxnorth Archive"
```
