# Appointment Tracker

[English](#english) | [Polski](#polski)

---

## English

Keep track of medical and other appointments for the whole family. Appointments are always sorted by what's coming up next, show the weekday and how many days are left, and you can get a heads-up before each one.

It works offline, and all your data stays on your own phone. No account, no ads, no tracking.

### What it does

- **Sorted by what's next.** Every appointment is sorted from the nearest to the furthest away, with its weekday (Mon, Tue, Wed…) and how many days are left ("today", "tomorrow", "in 9 days").
- **People without setting anything up.** Just type whose appointment it is. Names you have used are suggested next time, and you can filter by person or group the list by **person**, **type** or **date**. Appointments with no name go under "General".
- **Location with a map.** Type the clinic name or address, then open it directly in Google Maps to see where it is or get directions. There is no built-in map search with autocomplete (that needs a paid Google API key this app doesn't have) — typing the address and opening it in Maps is the reliable alternative.
- **Reminders before the appointment.** Choose one or more: 1, 2, 3, 5, 7, 14 or 30 days before, or your own custom number of days. Set your usual choice as the default in Settings.
- **How to prepare.** A note field shown clearly on the appointment and in its reminder, for things like "fast for 8 hours" or "bring your referral letter", so it doesn't get missed.
- **Quick add** for common appointment types (GP, dentist, eye test, vaccination, blood test and more).
- **Phone number** with a direct **Call** link, and **notes** for anything else.
- **Cancel** an appointment (it's kept, struck through, and can be restored) or **delete** it for good.
- **Past appointments** move out of the way automatically and stay available to look back on.
- **Search** by name, person, location or notes.
- **Calendar export.** Add every appointment to your phone's calendar in one tap, with its reminders attached.
- **Undo** for every change. Polish and English (the app defaults to English), light and dark mode, backup to a file.

### Reminders: how they work, and what they can't do

Inside the app, you always see what's coming up when you open it: the summary at the top, "Today" and "Tomorrow" highlighted, and a dot next to the people who have something soon.

**Please read this.** This is a web app, and Android does not let web apps ring or notify at a set time while they are closed. So there are three layers, from most to least dependable:

1. **Your phone's calendar (most dependable).** Tap the **calendar button** at the top (or **Add to calendar** on a single appointment). The app creates a file with an event for each appointment — at its exact time if you set one — with your chosen reminders attached. Open that file with your calendar app (for example Google Calendar or Samsung Calendar) and add the events. Your calendar then reminds you even when this app is closed.
2. **Background check (best effort, Chrome only).** In **Settings**, turn on **Check in the background** and allow notifications. Chrome then occasionally wakes the app, and it can show a notification when a reminder date has been reached. Chrome decides when, and it is not guaranteed, especially if the app has not been used recently.
3. **When you open the app.** The summary and each appointment's status are always up to date.

For an appointment you cannot afford to miss, please use the calendar.

### Install on your Android phone

1. On your phone, open **https://ewa-schoen.github.io/REPOSITORY-NAME/** in **Chrome**.
2. Tap the **⋮** menu (top right) and choose **Install app**. On some versions this is **Add to home screen**, then **Install**.
3. Open Appointment Tracker from the icon on your home screen.
4. Optional: in **Settings**, allow notifications and turn on the background check.

After the first visit it also works without internet.

### Your data

Everything you enter is stored only on your phone. Nothing is uploaded, and the app does not use any outside map or address service — the Maps link simply opens a search in whatever maps app or website you already use.

Uninstalling the app or clearing Chrome's site data deletes your appointments. Use **Settings → Save backup file** now and then, and **Restore from backup file** to bring your data back, for example on a new phone.

### If the install option doesn't show

- Open the address in **Chrome** and make sure Chrome is up to date. Other browsers, such as Brave, Firefox, Samsung Internet and Edge, only add a shortcut with their own small badge on the icon, so use Chrome to install.
- If the app is already installed, the menu shows **Open** instead of **Install app**.
- If the page shows an error, the site may not be published yet. Try again in a few minutes.
- If you see a small browser icon on the app icon, it was added as a shortcut. Save a backup first, remove the icon, install again from Chrome and restore your backup. Data is kept separately for each browser.

---

## Polski

Pilnuj wizyt lekarskich i innych spotkań dla całej rodziny. Wizyty są zawsze posortowane od najbliższej, pokazują dzień tygodnia i ile dni zostało, a przed każdą można dostać przypomnienie.

Działa bez internetu, a wszystkie dane są tylko na Twoim telefonie. Bez konta, bez reklam, bez śledzenia.

### Co robi

- **Sortowanie od najbliższej.** Każda wizyta jest ułożona od najbliższej do najdalszej, z dniem tygodnia (pon, wt, śr…) i liczbą dni, które zostały („dziś”, „jutro”, „za 9 dni”).
- **Osoby bez żadnej konfiguracji.** Wystarczy wpisać, czyja to wizyta. Użyte wcześniej imiona są podpowiadane, a listę możesz filtrować po osobie albo grupować według **osoby**, **rodzaju** lub **daty**. Wizyty bez imienia trafiają do „Ogólne”.
- **Lokalizacja z mapą.** Wpisujesz nazwę przychodni lub adres, a potem otwierasz go wprost w Google Maps, żeby zobaczyć, gdzie to jest, albo wyznaczyć trasę. Nie ma wbudowanej wyszukiwarki miejsc z podpowiedziami (wymagałoby to płatnego klucza API Google, którego ta aplikacja nie ma) — wpisanie adresu i otwarcie go na Mapach to niezawodna alternatywa.
- **Przypomnienia przed wizytą.** Wybierz jedno lub więcej: 1, 2, 3, 5, 7, 14 lub 30 dni przed, albo własną liczbę dni. Swój zwykły wybór ustawisz jako domyślny w Ustawieniach.
- **Jak się przygotować.** Pole notatki pokazane wyraźnie przy wizycie i w przypomnieniu, na rzeczy typu „na czczo 8 godzin” albo „zabrać skierowanie”, żeby nie umknęło.
- **Szybkie dodawanie** typowych wizyt (lekarz rodzinny, dentysta, badanie wzroku, szczepienie, badanie krwi i inne).
- **Numer telefonu** z bezpośrednim linkiem do **zadzwonienia** i **notatki** na wszystko inne.
- **Odwołanie** wizyty (zostaje na liście, przekreślona, można ją przywrócić) albo **usunięcie** na stałe.
- **Minione wizyty** same schodzą z głównej listy i są dostępne do przejrzenia.
- **Wyszukiwanie** po nazwie, osobie, lokalizacji lub notatkach.
- **Eksport do kalendarza.** Wszystkie wizyty dodasz do kalendarza w telefonie jednym stuknięciem, razem z przypomnieniami.
- **Cofnij** dla każdej zmiany. Polski i angielski (domyślnie aplikacja jest po angielsku), jasny i ciemny motyw, kopia zapasowa do pliku.

### Przypomnienia: jak działają i czego nie potrafią

W samej aplikacji po otwarciu zawsze widać, co nadchodzi: podsumowanie na górze, wyróżnione „Dziś” i „Jutro” oraz kropkę przy osobach, które mają coś wkrótce.

**Proszę to przeczytać.** To aplikacja internetowa, a Android nie pozwala takim aplikacjom dzwonić ani wysyłać powiadomień o umówionej porze, gdy są zamknięte. Dlatego są trzy poziomy, od najpewniejszego do najmniej pewnego:

1. **Kalendarz w telefonie (najpewniejszy).** Stuknij **przycisk kalendarza** na górze (albo **Dodaj do kalendarza** przy pojedynczej wizycie). Aplikacja tworzy plik z wydarzeniem dla każdej wizyty — o dokładnej godzinie, jeśli ją ustawiłaś/eś — razem z wybranymi przypomnieniami. Otwórz ten plik w aplikacji kalendarza (np. Kalendarz Google lub Samsung) i dodaj wydarzenia. Kalendarz przypomni Ci wtedy nawet przy zamkniętej aplikacji.
2. **Sprawdzanie w tle (bez gwarancji, tylko Chrome).** W **Ustawieniach** włącz **Sprawdzaj w tle** i zezwól na powiadomienia. Chrome od czasu do czasu budzi wtedy aplikację, a ona może pokazać powiadomienie, gdy nadejdzie data przypomnienia. To Chrome decyduje kiedy, nie ma gwarancji, zwłaszcza gdy aplikacja dawno nie była używana.
3. **Po otwarciu aplikacji.** Podsumowanie i status każdej wizyty są zawsze aktualne.

Przy wizycie, której przegapienie byłoby poważne, użyj kalendarza.

### Instalacja na telefonie z Androidem

1. Na telefonie otwórz w **Chrome** adres **https://ewa-schoen.github.io/REPOSITORY-NAME/**.
2. Stuknij menu **⋮** (prawy górny róg) i wybierz **Zainstaluj aplikację**. W niektórych wersjach to **Dodaj do ekranu głównego**, a potem **Zainstaluj**.
3. Otwieraj Appointment Tracker z ikony na ekranie głównym.
4. Opcjonalnie: w **Ustawieniach** zezwól na powiadomienia i włącz sprawdzanie w tle.

Po pierwszym otwarciu działa także bez internetu.

### Twoje dane

Wszystko, co wpiszesz, zapisuje się tylko na Twoim telefonie. Nic nie jest wysyłane, a aplikacja nie korzysta z żadnej zewnętrznej usługi map czy adresów — link do Map po prostu otwiera wyszukiwanie w aplikacji lub stronie map, której już używasz.

Odinstalowanie aplikacji albo wyczyszczenie danych Chrome usuwa wizyty. Co jakiś czas użyj **Ustawienia → Zapisz plik kopii**, a w razie potrzeby **Przywróć z pliku kopii** (np. na nowym telefonie).

### Gdy nie widać opcji instalacji

- Otwórz adres w **Chrome** i sprawdź, czy Chrome jest aktualny. Inne przeglądarki, jak Brave, Firefox, Samsung Internet czy Edge, dodają tylko skrót z własną małą odznaką na ikonie, więc do instalacji używaj Chrome.
- Jeśli aplikacja jest już zainstalowana, w menu zobaczysz **Otwórz** zamiast **Zainstaluj aplikację**.
- Jeśli strona pokazuje błąd, witryna może jeszcze nie być opublikowana. Spróbuj ponownie za kilka minut.
- Jeśli na ikonie aplikacji widać małą ikonę przeglądarki, została dodana jako skrót. Najpierw zapisz kopię, usuń ikonę, zainstaluj aplikację ponownie z Chrome i przywróć kopię. Dane są przechowywane osobno dla każdej przeglądarki.
