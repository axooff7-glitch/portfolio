# axoo-czeki 📜

Zaawansowany system fizycznych czeków bankowych dla serwerów Minecraft, pozwalający na bezpieczny handel oraz przekazywanie gotówki między graczami w formie fizycznych przedmiotów.

## ✨ Funkcje

- **📂 Fizyczne Czeki**: Gracze mogą tworzyć czeki, które są fizycznymi przedmiotami (papier), co ułatwia handel i ekonomię.
- **💸 Automatyczny Podatek**: System automatycznie pobiera **5% podatku** przy wypłacie czeku (konfigurowalne), co wspiera gospodarkę serwera.
- **🛡️ Bezpieczeństwo (PersistentData)**: Dane o wartości i autorze czeku są zapisywane bezpośrednio w przedmiocie za pomocą `PersistentDataContainer`, co wyklucza możliwość podrabiania czeków (np. przez kowadło).
- **🎨 Pełna Personalizacja**: Konfiguracja pozwala na zmianę materiału, nazwy, lore (opisów) oraz wszystkich wiadomości.
- **🔗 Integracja Ekonomii**: Pełne wsparcie dla **Vault** oraz **AxooCore** (wykrywa dostępnego dostawcę automatycznie).

## 🛠️ Komendy

| Komenda | Opis | Uprawnienie |
| :--- | :--- | :--- |
| `/czek <kwota>` | Tworzy czek o podanej wartości i pobiera kwotę z Twojego konta. | - |
| `/adminczek <kwota>` | Tworzy czek administracyjny (darmowy i bez autora). | `axooczeki.admin` |
| `/czeki-reload` | Przeładowuje plik konfiguracyjny pluginu. | `axooczeki.admin` |

## ⚙️ Przykład Konfiguracji Itemu

```yaml
check-item:
  material: PAPER
  name: "&6&lᴄᴢᴇᴋ"
  lore:
    - "&fWartość: &e{VALUE}$"
    - "&fAutor: &7{AUTHOR}"
    - "&fPodatek przy wypłacie: &c5%"
    - "&eKliknij PPM, aby wypłacić!"
  admin-author: "&cCONSOLE"
  enchanted: true
```

## Galeria 
<img width="543" height="349" alt="Zrzut ekranu 2026-02-12 131002" src="https://github.com/user-attachments/assets/f9b9f378-c632-46cb-9c73-9f4ebc420ff4" />

---

## ✨ Informacje o projekcie

*Stworzone przez AXOO*
