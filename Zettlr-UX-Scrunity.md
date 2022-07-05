---
disqus: exanrauzer
---

# ZETTLR - UX SCRUNITY

System: Windows 10
Architecture: Intel 64bit
🏳 Issue on GitHub
🏁 Issue o GitHub by another User



___

# Batch 2.3.0

<!--


Dodac Pinned tabs to left - jako enchancement i exclude from scroll. -  od nowej wersji


-->

## BUGS
- AutoCorrect doesn't work when italic, bold, or other MD characters follow the string to autocorrect (conflict)
- Font size changes after soft break and typed hypen (vid)
- Selected text pop-up menu overlaps selected text 🏳
- Inability to use arrows keys to manouver teh cousor while file editing 🏁
- Inability to use diacritics in snippets

## FRICTION REDUCTION
- Removing the need to hold the `shift` while scrolling tabs.

## UI CLEANUP
- Mouse scrolling over ther editor area on the left from left margin isn't smooth, but jumping (discontinuous

## FEATRURES
- Profiles - switching between profiles to have different workspaces and settings (snippetsty, and all) as well as solo file loaded otside the Wospace.
- Anchor to paragraph

## ENHACEMENT
- Menu option to export a file with soft line breakes in seperate lines.
___

# Batch 2.2.5 / 2.2.6

<!--

BUGS
Niestety kurwa zjebane sa snippetsy. Chodzi o to, że podaje podpowiedź na podstawie zaweartości snippetsa. Np mam snippets yaml gdzie w zawartości mam author, które zawiera "ho" i podrzuca mi podpowiedź gdy wpisuję snippets :ho który miał być skrótem do :hour a też nie mogę mieć snippetsa :hour, bo w snippetsie :day jest równiez variable current_hour.

Plik Wolna wola pokazuje mi w panelu prawym zbieżność z plikami na pdstawie tagu a żadnych tagów nie mam w pliku.






FEAT
Musi być eksport z nowymi linijkami pojedynczymi - taka opcja.
Oraz menu kontekstowe: dodaj znaki pojedynczych linii (/) do zaznaczonego tekstu.

Przyklikaniu na kartę - przy przechodzeniu z pliku na plik drzewo się rozwija do tego elementu, oraz przy zamykaniu - bo przeskakuje fokus. To kiepskie, tym bardziej, że nie zwija sie automatycznwie, gdy plik jest już zamknięty. Kilkanie na taby kart nie powinno powodować rozwijania drzewa. Mogłoby być w prawym kliku w menu rozwijanym dla taba - pokaż lokalizację w drzewie. Dodatkowo można by przypisać jakiś skrót do shift+MouseLeft przy kliku na tab. Dodatkowow opcja - przypnij tab - jak w googlu.

Jeśli jakiś plik staje się zbyt obwity - klikasz na niego prawym i wybierasz opcję: stwórz Projekt (albo: przenieś do nowego katalogu o tej samej nazwie). Wtedy plik jest przenoszony do nowego katalogu, który być może jest już projektem. Być może - ale to już byłoby mega extra ale też skomplikowane - bo jak ogarnąć yamla - niech utworzą się nowe pliki z nazwami i treściami z pierwszych nagłówków.

Znak dzielenia strony. jak w końcu dac nową stronę?


Jeśli jest api HackMD, to czy możnaby zrobić w Zettlu połączenie z HackMD aby niektóre pliki były z Zettla udostępniane i na aktualizowane? Byłoby to bardzo spoko - niektóre elementy można by publikować z poziou Zettla. Bardzo by to byo spoko.

Połączyć search #arcihtektura-informacji z keyword: architektura informacji, czyli jeśli szuka architektura-informacji to pokazuje mie też architektura informacji i na odwrót. DOdatkowo łącznie z underlinem: architektura_informacji. jest jakaś chyba nieścisłość między kewywords i tagami.


dwa rodzaje tagów - funkcyjne i tematyczne/contentowe/contextowe



Kurwa, czy trzeba sie tak jebać z nazwami katalogów? Dlaeczego struktura katalogów jest tak sztywna i nie do ustawienia przez USera, że trzeba kombinować z nazwami Katalogów, żeby ustawić odpowiednią kolejność. Jest to strasznie sztywne i skostniałe. Nie pozwala na dynamiczne operowanie katalogami.



ENAHCNE
dlaczego nie zrobić takiego triku, by:
[[20220331095756]] [[{pobierz nazwę z pliku: 20220331095756}]] wtedy zawsze byłyby aktualne nazwy plików.

Napisać o grafie (tagu) w temacie o grafie: Graf Zettla pokazuje nie połączenia między plikami, ale linki. Jeśli link jest sztuczny, tzn prowadzi do pliku, którego nie ma to i tak go w grafie wyświetli. Mógłby pokazywać Graf martwe linki.Linki do plikó, które nie istnieją.

Nazwy tygodnia do predefiniowanych snippetsów!!!!!! Shortowa również.


Nie ma szybkiego renderowania plików. Jest sekunda, pół przerwy zanim sie zrenderuje nagłówek, gdy przechodzi się od pliku do pliku - to wkurwiające. Zrobić prerenderowanie wszystkich plików w tle.


FRICTION REDUCTION
aranżacja headlinów - dodaj poziom -1 (coś takiego), że chcesz przeorganizować dokument tak, że wszystkie headliny poziomu Igo chcesz by były poziomu drugiego etc, czyli przesunąć chcesz wszystkie jeden poziom głębiej.

Uwaga bardzo dobra uwaga: Kółko musi dopasowywac zoom i uwagaa: z shiftem cały UI a bez shifta, czyli z ctr - sama czcionka

Dodawanie katalogów wielu Workspaceów jednoczenie.




UI CLENUP
Wygasić headingi jak na Stackedicie - jako opcja

Zrobic tak jak w Transno, że można przeskrocllowac przestrzeń pdd tekstem na samą górę mimo, że nie ma tam pustych liniii ? Może..

I nie powinien się podświetlać katalog, gdy wybrany jest plik solo. Bo to myli w huj.

Musi, musi być shortcut do colapsu katalogów, bez tego lipa. Również podkatalogów (z shiftem).

sortowanie katalogów i plików powinno być od razu a ie po restarcie Zettla.



TABELE TABELE TABELE
zrobić je tak jak w Gitbooku! Najlepsze tabele ever.
Ctrl:enter ani shift enter nie działa w Tabeli.




?????????????
Snippetsy a głównie predefiniowane naj CLOIPBOARD czy CURRENT_MINUTE nie są wyjaśnieone, jak ich używać dla laika

Czy jest info o dwóch spacjacvh w YAML w instrukcji?

- Let file be saving in background (with active option: save after a while) to prevent opening another tab with another file when that file is opening during saving.



-->
## BUGS

- Redo and undo doesn't work from dropdown menu.
- Rendering of ~~strikethrough~~ doesn't dissapear after undo.
- When bold rendered text ended with backslach is clicked then one star after text is visible.
- 
## FRICTION REDUCTION

- Remeber collapsed Headings.


## UI CLEANUP

- Drop down menu hints of keyboard shortcuts: replace 'shift' with '⇑' - that's rather misleading if this is a 'shift' designation.
- Render `monospace`





___

# Batch: 2.2.4

## BUGS


- Coursor isn't placed properly inline after zoom in/out
- Coursor isn't placed properly inline after # and space
- Coursor isn't placed precisely after click between letters in rendered text (f.e. bold) - it is placed where clicked but text moved right due to showing hidden md marks (for bold: two stars).

.
- Something is broken and crashes when moving files and folders in File Manager. After close the app to reset folders are sometimes gone and bringing back is impossible (root error). Need to clean up folders and subfolders with .directory files to be able to load folders back to Zettlr.
- Some folders sometimes do not open at app start.
- General messy bugs with folders: moving, name changing prohibition, etc.
- Sometimes unable to rename a folder (some system restriction). App reopen doesnt help.

.

- When moving folder from lev4 folder to lev2 folder it moves that folder to lev1 folder often.
- You cannot change a small letter to big letter in the name of the file in File Manager.
- When selecting a rendered bold text: the selection disappears when it leaves rendering.
- Switching between tabs to large (?) file (50k of signs) takes too long, but only when coursor is on the bottom of this document.
- Backspace lags at big paragraphs.
- Shortcut keys should be without alt(!), because when i switch to Dark Mode it types a 'ł' sign in my language.


## FRICTION REDUCTION


- To group Settings with Resources Manager and Tags Manager (group settings together).
- Ability to deselect a folder by second click.
- Remember coursor position when switching between files in one tab mode.
**- There is unability to create a workspace that is not 1st level (it is always nested inside active folder since all the time one folder is selected).**
**- There is no ability to create a file that would be outside a Workspace (loaded above). Prototype rezolution: right click on Files... bar to create a file and popup system window where to place that file.**
- When a file is clicked in the File Manager the active folder should change to the one that contains selected file (combined view)
- After ctrl+click a tag, focus in search panel should be placed on _restrict search to directory_, not a tag (and default folder shouldn't be suggested).
- After ctrl+click a tag, when a tag field was previously backspaced and search window was closed, after ctrl+click an another tag , the tag name isn't filled int the search field.
- Option: Set saving delay time.
- Search folder/files: when files found: make it possible to use keyboard only to go to that file (f.e. arrows up and down between files that match (not folders), and press enter to open file and ctr+enter to open in another tab).
- Tags dynamic suggestions do not highlight a tag that is exactly as typed tag (but prefere to highlight tags that contain that typed tag f.e. prefere #inprog**re**s instead of #**re**) - by that you can't press enter to confirm a tag, that you've already typed.
- Shortcut to snippets/icon



## UI CLEANUP

- Render '#Heading' to Heading.
- Render line.
- Option: Highlights font size: Normal, Small (i feel like Heading font is to large).
- In distraction mode hide menu bar and Windows taskabar.
- Files Manager width should be fixed, its bad when it changes when window width is manipulated.
- Text selection which starts from a middle of a text that is rendered is different.
- Display of single files (outside a workspace) in text search is different and multiplicates file info.
- To remember collapsed headings after file close and file switch in one tab mode.
- The tab bar of active tab looks now like faded and inactive and bar of inactive looks like active. This is rather counter intuitive. The active bar should have lesser difference beetwen font color and tab color then not active bar.
- Bold in dark mode is not to visible, font of the bold in dark mode should have be a little brighter.
- Ability to collapse YAML Frontmatter section like a heading
- When @ is added before a written word and when you undo (ctrl z) - then the @ mark do not disappear, but technically it is undone: it isn't there already.
- Remove global search panel and instead add additional search bar above floders/files search bar. Behavior: When full text search bar is used - the content of the File Manager is replaced with search results content.
- HOW TO SOLVE RENDERED TEXT CLICKS: Markdown sings should become visible only when mouse click (coursor placement) takes before rendered text or after rendered text. When clicked ON rendered text, the Markdown signs shouldn't be visible.
- Default fonts in templates should have special signs in most leanguages. Bordeaux font doesn't have signs for polish language. (anyway the font and dark mode deep sea color is so cool that I use it anyway).
- Width of File Manager isn't saved


## ENHANCEMENTS

- Selected text bouble menu option: ==highight==
- Selected text bouble menu option: ~~Strikethrough~~
- Both words and signs counting (remove the option to choose one)
- Fortunately there is a nice glitch that expands a folder that has the same name as a file outside the workspaces when that file is clicked. Please do not fix it. Instead add an option to collapse that folder after doublle-click.
- Ctrl f search: number of findings, and mark on the mousebar.


## FEATURES

- Workspaces sorting by User.
- Option: After file opening focus coursor at the position where it was when file was closed or at the end of a text.
- User color pickup for: highlights background and dark mode background.
- Collapse all folders and subfolders button/shortcut.
- Option: Star a file and starred files section in File Manager.


## DOCS

- Lack of md 'functions' f.e.: highlight, line, strikethrough.
- Creating a snippet isn't clearly described

___


# FIXED ISSUES

## 2.3.0

### BUGS

- Tick mark of Distraction Free mode in drop down menu isn't toggled by opening a File Manager (and by thus leaving Distraction Free mode).
- There is a lag when backspace is pressed and hold - there is no fluent deletion

### ENHANCEMET
- Ability to close search window with escape button.
