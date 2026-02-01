# Projekt Smart Kontrakty - Zaliczenie

Repozytorium zawiera wdrożenie dwóch kontraktów na sieć testową **Sepolia**. Kod obu kontraktów został pomyślnie zweryfikowany w eksploratorze.

## 1. Kontrakt ERC-20 (Token)
* **Nazwa**: ProjectToken (PTK)
* **Adres**: `0xdBE4C14a0DD56865b839d8eE4d34300d68f9612a`
* **Eksplorator**: [Zobacz na Etherscan](https://sepolia.etherscan.io/address/0xdBE4C14a0DD56865b839d8eE4d34300d68f9612a)
* **Status**: Zweryfikowany pomyślnie ✅

## 2. Kontrakt ERC-721 (NFT)
* **Nazwa**: MyNFT (MNFT)
* **Adres**: `0x4719c448Db33bB3dE71f211a8dea5402C1eD56e3`
* **Eksplorator**: [Zobacz na Etherscan](https://sepolia.etherscan.io/address/0x4719c448Db33bB3dE71f211a8dea5402C1eD56e3)
* **Status**: Zweryfikowany pomyślnie ✅

---

## 3. Struktura projektu i testy
* **/contracts**: Zawiera pliki źródłowe `.sol` oraz wersje *flattened* użyte do weryfikacji.
* **/tests**: Pliki testowe wygenerowane w Remix IDE. Testy potwierdzają poprawność funkcji `transfer` (ERC-20) oraz `safeMint` (ERC-721).

## 4. Potwierdzenie działania
Tokeny oraz NFT są widoczne w portfelu MetaMask pod adresem `0xf59d1c0cc3d72c208c3fa671ce562c5066d29d6a` na sieci Sepolia. Pierwszy token NFT (ID 0) został pomyślnie wybity funkcją `safeMint`.
