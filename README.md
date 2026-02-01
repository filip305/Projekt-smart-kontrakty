# Projekt na programowanie smart kontraktów

## Opis projektu
Celem projektu było przygotowanie i wdrożenie dwóch smart kontraktów w standardach ERC-20 oraz ERC-721 przy użyciu bibliotek OpenZeppelin. Repozytorium zawiera pełny kod źródłowy, testy jednostkowe oraz dokumentację wdrożenia na sieć testową **Sepolia**. Kod obu kontraktów został pomyślnie zweryfikowany w eksploratorze Etherscan.

## 1. Kontrakt ERC-20 (Token)
* **Nazwa**: ProjectToken (PTK)
* **Adres**: `0xdBE4C14a0DD56865b839d8eE4d34300d68f9612a`
* **Eksplorator**: <https://sepolia.etherscan.io/address/0xdBE4C14a0DD56865b839d8eE4d34300d68f9612a>
* **Status**: Zweryfikowany pomyślnie

## 2. Kontrakt ERC-721 (NFT)
* **Nazwa**: MyNFT (MNFT)
* **Adres**: `0x4719c448Db33bB3dE71f211a8dea5402C1eD56e3`
* **Eksplorator**: <https://sepolia.etherscan.io/address/0x4719c448Db33bB3dE71f211a8dea5402C1eD56e3>
* **Status**: Zweryfikowany pomyślnie

## 3. Struktura projektu i testy
* **/contracts**: Zawiera pliki źródłowe `.sol` oraz wersje *flattened* użyte do weryfikacji na Etherscan.
* **/tests**: Pliki testowe wygenerowane w Remix IDE. Testy potwierdzają poprawność funkcji `transfer` (ERC-20) oraz `safeMint` (ERC-721).

## 4. Weryfikacja i historia projektu
* **Adres portfela**: Wszystkie operacje (deployment, minting) zostały wykonane z adresu 0xf59d1c0cc3d72c208c3fa671ce562c5066d29d6a.
* **MetaMask**: Tokeny PTK oraz MNFT są poprawnie zaimportowane i widoczne w portfelu na sieci Sepolia. Pierwszy token NFT (ID 0) został pomyślnie wybity funkcją safeMint.
* **Historia zmian**: Pełna historia prac nad projektem, od wstępnych testów po finalną dokumentację, jest dostępna w zakładce Commits (git log) niniejszego repozytorium.

## 5. Galeria - potwierdzenie w MetaMask
Poniżej znajdują się zrzuty ekranu potwierdzające widoczność zasobów w portfelu oraz poprawność wykonanych transakcji:

| Tokeny ERC-20 | Kolekcja NFT | Drugi portfel (Odbiorca transakcji) |
| :---: | :---: | :---: |
| ![Tokeny](images/wallet_token.png) | ![NFT](images/wallet_nft.png) | ![Odbiorca](images/wallet_second.png) |
