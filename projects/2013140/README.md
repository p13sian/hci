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
