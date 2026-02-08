# 🏰 east-dzialki - Zaawansowany System Działek

**east-dzialki** to nowoczesny i estetyczny plugin na serwery Minecraft (Paper 1.20.1+), który umożliwia graczom tworzenie i zarządzanie własnymi terenami o wymiarach 50x50 kratek. Plugin stawia na immersję, wykorzystując niestandardowe receptury craftingu, hologramy, bossbary oraz eleganckie menu GUI.

## ✨ Główne Funkcje

### 🛠️ Unikalny System Tworzenia
- **Custom Crafting**: Aby stworzyć działkę, gracz musi wytworzyć specjalny **Blok Działki** (Ognisko Dusz) z rzadkich materiałów (sztabki złota, żelaza).
- **Inteligentne Ograniczenia**: System sprawdza odległość od innych działek (minimum 100 kratek) oraz limity gracza przed postawieniem bloku.
- **Zapobieganie Abuse**: Zwykłe ogniska dusz nie tworzą działek - wymagany jest przedmiot ze specjalnym tagiem NBT.

### 🛡️ Pełna Ochrona i Zarządzanie
- **Ochrona Terenu**: Blokada niszczenia i stawiania bloków dla osób nieuprawnionych.
- **Niezniszczalne Serce**: Centrum działki (ognisko) jest całkowicie odporne na wybuchy (TNT, Creeper), tłoki oraz niszczenie przez graczy.
- **System Uprawnień**: Właściciel może dodawać **Członków** (budowanie) oraz **Wspólników**.
- **PVP**: Walka na terenie działek jest dozwolona.

### 💎 Ekonomia i Czas
- **Ważność Działki**: Każda działka startuje z 7-dniowym okresem ważności.
- **Przedłużanie**: Gracze mogą przedłużać ważność działki w GUI. Koszt to **1 Blok Diamentu** za 24 godziny.
- **Limity Rangowe**: Konfigurowalne limity posiadanych działek dla rang VIP, SVIP, MVIP.

### 🎨 Estetyka i UI
- **Nowoczesne GUI**: Wszystkie menu (Panel, Lista Członków, Usuwanie) posiadają spójny styl z czarnym i szarym szkłem oraz wyśrodkowanymi tytułami (np. `    ᴘᴀɴᴇʟ ᴅᴢɪᴀʟᴋɪ`).
- **Hologramy**: Nad sercem działki unosi się lewitujący tekst z informacją o właścicielu i ID działki.
- **BossBar**: Po wejściu na teren działki gracz widzi pasek z nazwą właściciela.
- **Efekty Teleportacji**: Teleportacja do domu (`/dzialka dom`) zawiera odliczanie na ekranie (Title) oraz efekt ślepoty dla immersji.

## 📜 Komendy

| Komenda | Opis |
|---------|------|

| `/dzialka` | Wyświetla menu pomocy. |
| `/dzialka stworz` | Alternatywna metoda tworzenia (głównie admin). |
| `/dzialka dom [id]` | Teleportuje do działki. Otwiera GUI wyboru, jeśli gracz ma ich więcej. |
| `/dzialka dodaj <nick>` | Dodaje gracza do działki. |
| `/dzialka wspolnik <nick>` | Dodaje wspólnika do działki. |
| `/dzialka wyrzuc <nick>` | Usuwa gracza z działki. |
| `/dzialka panel` | Otwiera główne GUI zarządzania. |
| `/dzialka usun` | Rozpoczyna procedurę usuwania działki (z GUI potwierdzenia). |

## 🔐 Uprawnienia

- `dzialka.use` - Dostęp do podstawowych komend.
- `dzialka.admin` - Obejście zabezpieczeń, budowanie wszędzie.
- `dzialka.limit.2` - Zwiększa limit działek do 2 (VIP).
- `dzialka.limit.3` - Zwiększa limit działek do 3 (SVIP).
- `dzialka.limit.4` - Zwiększa limit działek do 4 (MVIP).
## ScreenShoty
<img width="857" height="699" alt="Zrzut ekranu 2026-02-08 184452" src="https://github.com/user-attachments/assets/8c985a8d-98a4-466c-b7cb-ca588616da1b" />
<img width="681" height="502" alt="Zrzut ekranu 2026-02-08 184526" src="https://github.com/user-attachments/assets/dbbae5b5-2a78-49d3-83dd-32720b93d097" />
<img width="701" height="294" alt="Zrzut ekranu 2026-02-08 184521" src="https://github.com/user-attachments/assets/b3c7b413-9f34-49d1-ab0a-7b5975eb89ae" />



## 🚀 Instalacja

1. Pobierz plik `.jar`.
2. Wrzuć go do folderu `/plugins/` na swoim serwerze.
3. Zrestartuj serwer.
4. Gotowe! Config wygeneruje się automatycznie.

---
*Autor: **AXOO***
