# ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ, ΤΜΗΜΑ ΠΛΗΡΟΦΟΡΙΚΗΣ

## ΜΑΘΗΜΑ
## Επικοινωνία Ανθρώπου-Υπολογιστή
#### Επιβλέπων καθηγητής: Χωριανόπουλος Κωνσταντίνος

## Στοιχεία φοιτητή
### Γιώργος Σιανός
### ΑΜ: Π2013140

### Άσκηση 1. Set-up the main dependencies and demonstrate your base system - Change your command prompt with your student ID, list your dot files, display your shell configuration file and display system information (hardware+software)
#### asciinema: https://asciinema.org/a/xcewjj3h9W8XBDfm8WNn93UtN
Άλλαξα το command prompt απο το αρχείο .bashrc. Το configuration του αρχείου φαίνεται στο recorded session. Για να τροποποιήσω το αρχείο χρησιμοποίησα τον nano editor

```
sudo nano .bashrc
```

Εμφάνισα όλα τα dot files στο home directory.

```
ls -a
```

Eγκατέστησα το neofech για να δείξω το σύστημά μου hardware και software.
```
sudo apt install neofetch
neofech
```

### Άσκηση 2. Βrowse and view files on your system.
#### asciinema: https://asciinema.org/a/4x32iogQLLddAoK1VVt2abiBq
Εγκατέστησα το ranger και το vim.

```
sudo apt-get install ranger
sudo aot-get install vim
```

Χρησιμοποίησα το ranger για να περιηγηθώ στο filesystem μου.

```
ranger
```

Χρησιμοποίησα τον vim editor για να δημιουργήσω ένα νέο αρχείο στο οποίο πρόσθεσα κείμενο και το έσωσα.
Τα maual του ranger και του vim είναι αναλυτικότατα.

```
man ranger
man vim
```

### Άσκηση 3. Edit the vim or the shell configuration file.
#### asciinema: https://asciinema.org/a/xaIsS9BGrrAMSOBXeAnz0k9d9

Στην συγκεκριμένη έκδοση του vim 8.1.1401. To code highlighting ειναι ενεργοποιημένο by default. Για να γίνει οποιαδήποτε αλλαγή στο configuration του vim χρησιμοποιούμε το αρχείο .vimrc το οποίο αν δεν υπάρχει το δημιουργούμε στο home directory.

```
nano .vimrc
```

Για να ενεργοποιήσουμε και να απενεργοποιήσουμε το code highlighting ανάλογα προσθέτουμε τα παρακάτω στο αρχείο .vimrc

```
:syntax on

:syntax off
```

Για να ενεργοποιήσω το auto completion χρησιμοποίησα το omni completion, το οποίο δεν είναι ενεργοποιημένο by default στον vim editor.
Το omni completion υποστηρίζει αρκετές γλώσσες τις οποίες καταλαβαίνει απο την επέκταση του αρχείου. Για να ενεργοποιήσω το omni completion προσθεσα τα παρακάτω στο αρχείο .vimrc.

```
filetype plugin on
set omnifunc=syntaxcomplete#Complete
```

Για να δοκιμάσω τις νέες αυτές δυνατότητες δημιούργησα ένα αρχείο .html.

#### Πληροφορίες σχετικά με την υλοποίηση της άσκησης βρήκα:
https://www.cyberciti.biz/faq/turn-on-or-off-color-syntax-highlighting-in-vi-or-vim/
https://vim.fandom.com/wiki/Omni_completion



