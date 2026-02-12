# AxooPortfel 💰

Zaawansowany system ekonomii i sklepu premium dla serwerów Minecraft, oferujący w pełni konfigurowalne menu GUI, systemy rang oraz rankingi doładowań.

## ✨ Funkcje

- **🛍️ Sklep Premium**: Nowoczesne menu GUI do zakupu rang, kluczy i przedmiotów specjalnych.
- **🏆 Ranking Doładowań**: System `/topka`, który wyświetla graczy z największą sumą wpłat wraz z ich głowami.
- **🎨 Pełna Personalizacja**: Możliwość edycji każdego elementu GUI (sloty, materiały, tytuły, ramki) bezpośrednio w `config.yml`.
- **🛡️ Bezpieczne Zakupy**: System potwierdzeń "Tak/Nie" przed każdą transakcją, chroniący graczy przed pomyłkami.
- **📈 Placeholders**: Integracja z PlaceholderAPI do wyświetlania stanu konta i topki doładowań w dowolnym miejscu.
- **🔗 Integracja z LuckPerms**: Automatyczne nadawanie rang i uprawnień po zakupie w sklepie.

## 🛠️ Komendy

### 👤 Komendy Gracza

| Komenda | Aliasty | Opis |
| :--- | :--- | :--- |
| `/skleppremium` | `/sklep`, `/portfel` | Otwiera główne menu sklepu premium. |
| `/topka` | `/topkadow` | Wyświetla ranking najhojniejszych graczy (doładowań). |

### 🛡️ Komendy Administracyjne

| Komenda | Opis | Uprawnienie |
| :--- | :--- | :--- |
| `/aportfel add <nick> <kwota>` | Dodaje środki do portfela gracza. | `axooportfel.admin` |
| `/aportfel set <nick> <kwota>` | Ustawia stan konta na konkretną wartość. | `axooportfel.admin` |
| `/aportfel sprawdz <nick>` | Pokazuje stan konta i sumę doładowań gracza. | `axooportfel.admin` |

## 📊 Placeholders (PlaceholderAPI)

| Placeholder | Opis |
| :--- | :--- |
| `%axoo_wallet_stan_konta%` | Aktualna kwota w portfelu gracza. |
| `%axoo_wallet_topka_doladowan_[X]%` | Gracz i kwota z miejsca X w rankingu. |

## Galeria
<img width="543" height="349" alt="image" src="https://github.com/user-attachments/assets/88cd93fb-4a17-4271-9f24-f78a1f892eba" />

---

## ✨ Informacje o projekcie

*Stworzone przez AXOO*



