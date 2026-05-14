# Base Builder Kit

Professional starter repository for deploying and interacting with smart contracts on Base.

![Banner](images/banner.png)

---

## Özellikler

- Base Mainnet desteği
- Base Sepolia desteği
- Hardhat altyapısı
- Deploy scriptleri
- Verify scriptleri
- Başlangıç dostu yapı

---

## Gereksinimler

- Node.js
- npm
- MetaMask
- Base RPC

---

## Kurulum

```bash
npm install
```

---

## .env Ayarı

`.env` dosyası oluştur:

```env
PRIVATE_KEY=your_private_key
BASE_RPC=https://mainnet.base.org
BASESCAN_API_KEY=your_api_key
```

---

## Contract Compile

```bash
npx hardhat compile
```

---

## Deploy

```bash
npx hardhat run scripts/deploy.js --network base
```

---

## Verify

```bash
npx hardhat run scripts/verify.js --network base
```

---

## Dokümantasyon

- `docs/deployment-guide.md`
- `docs/base-network.md`
- `docs/troubleshooting.md`
