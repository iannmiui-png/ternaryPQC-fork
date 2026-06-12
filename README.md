# ternaryPQC-fork
![ternaryPQC Icon](icon.png)
## Quick Start
```bash
git clone https://github.com/DigiMancer3D/ternaryPQC.git
cd ternaryPQC
chmod +x setup.sh
./setup.sh          # Builds liboqs + all tools
```
**Most useful commands:**
- `./pqc_keygen` → Generate a full keychain
- `./validate_kchain` → Test all keys with real signatures
- `python3 game.py` → Play #HASHBREAKER
- `./pqc_hybrid_signer` → Create multi-algorithm signatures
## Terminology Table

| Term                  | What it really is                              | Plain English                                      |
|-----------------------|------------------------------------------------|----------------------------------------------------|
| **ternaryPQC**        | The whole project                              | Ternary-based Post-Quantum Crypto toolkit          |
| **6000-trit seed**    | Massive expanded master entropy                | The super-secure root everything comes from        |
| **SPX-QEC**           | Custom seed expansion pipeline                 | Turns sny if < input into iff > bigsafe seed       |
| **Keychain**          | JSON file with all master + role keys          | One file containing your entire secure wallet      |
| **Hybrid Signer**     | Signs with Falcon + Dilithium + SPHINCS+       | Defense-in-depth signatures                        |
| **Ring Password**     | SHA3-512 + Ring0 proof (.ssp)                  | Secure password system compatible with ringCT      |
| **#HASHBREAKER**      | Interactive Python game                        | Fun way to test and learn your keys                |
--------------------------------------------------------------------------------------------------------------------------------
