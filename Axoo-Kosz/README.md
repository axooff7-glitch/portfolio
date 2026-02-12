# axoo-kosz 🗑️

Lekki i funkcjonalny plugin na wirtualny kosz na śmieci, który pozwala graczom na szybkie i wygodne pozbywanie się niepotrzebnych przedmiotów poprzez dedykowany interfejs GUI.

## ✨ Funkcje

- **🗑️ Wirtualny Kosz**: Otwiera menu o rozmiarze 54 slotów, gdzie gracze mogą wrzucić przedmioty.
- **🎨 Estetyczne GUI**: W pełni konfigurowalne tło i obramowanie kosza (szklane panele).
- **🛡️ Bezpieczeństwo**: Przedmioty są usuwane bezpowrotnie dopiero po zamknięciu ekwipunku.
- **⚙️ Pełna Konfiguracja**: Możliwość zmiany tytułu, rozmiaru GUI oraz wszystkich wiadomości w `config.yml`.

## 🛠️ Komendy

| Komenda | Aliasty | Opis | Uprawnienie |
| :--- | :--- | :--- | :--- |
| `/kosz` | `/trash`, `/garbage` | Otwiera menu kosza na śmieci. | `axookosz.use` (opcjonalnie) |

## ⚙️ Konfiguracja

W pliku `config.yml` możesz dostosować wygląd i działanie pluginu:

```yaml
gui:
  title: "&8&l                 ᴋᴏsᴢ"
  size: 54
  decorations:
    frame:
      material: BLACK_STAINED_GLASS_PANE
      name: " "
    background:
      material: GRAY_STAINED_GLASS_PANE
      name: " "

messages:
  prefix: "&8[&6Kosz&8] &7"
  opened: "&aOtwarto kosz. Po zamknięciu zawartość zostanie usunięta!"
  no-permission: "&cNie masz uprawnień!"
```

## Galeria
<img width="687" height="501" alt="Zrzut ekranu 2026-02-12 125721" src="https://github.com/user-attachments/assets/920afcff-c84a-4fce-b735-e1948a9b766c" />


## ✨ Informacje o projekcie

*Stworzone przez AXOO*

