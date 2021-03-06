# Μάθημα: Επικοινωνία Ανθρώπου-Υπολογιστή
**Ονοματεπώνυμο:** Βασιλική Πολυχρόνη  
**ΑΜ:** Π2015084

[Προσωπικό αποθετήριο μαθήματος](https://github.com/p15poly/hci)  
## Εργασία Ανάπτυξης: Οπτικοποίηση δεδομένων εκπαιδευτικού συστήματος (USA)
Links:
* [Σελίδα εφαρμογής](https://p15poly.github.io/D3js-US-educational-attainment/)
* [Προσωπικό αποθετήριο κώδικα εργασίας](https://github.com/p15poly/D3js-US-educational-attainment)
* [Τελική αναφορά σε GitHub Pages](https://p15poly.github.io/hci-anafora/)
### Παραδοτέο 1
Links για το πρώτο παραδοτέο:
* [Αλλαγές στον κώδικα](https://github.com/p15poly/D3js-US-educational-attainment/commits/paradoteo1)

**Ζητούμενα και αλλαγές:**

* - [x] Αλλάξτε τα χρώματα στα 3 γραφήματα.

Άλλαξα τα χρώματα στα τρία γραφήματα της σελίδας με δικές μου επιλογές, με τροποποιήσεις στα αρχεία .js:

*Πρώτο γράφημα:*  
![Διάγραμμα 1](images/graph1.jpg)  

*Δεύτερο γράφημα:*  
![Διάγραμμα 2-1](images/graph2-1.jpg)  
![Διάγραμμα 2-2](images/graph2-2.jpg)  
![Διάγραμμα 2-3](images/graph2-3.jpg)  
![Διάγραμμα 2-4](images/graph2-4.jpg)  

*Τρίτο γράφημα:*  
![Διάγραμμα 3](images/graph3.jpg)  

* - [x]  Αντικαταστήστε τις διεπαφές στα "κουμπιά" του 2ου και 3ου γραφήματος με άλλες της επιλογής σας.

Αντικατέστησα τις διεπαφές στα κουμπιά του 2ου και 3ου γραφήματος, με αλλαγές στα αρχεία .html και .css:  

![Κουμπιά](images/buttons.jpg)  

* - [x] Όταν το ποντίκι διέρχεται επάνω από κάθε επιλογή του menu στην κορυφή της σελίδας, να ακούγεται κάποιος ήχος της επιλογής σας.

Πρόσθεσα έναν ήχο στα κουμπιά του μενού (header) μέσω script, ο οποίος ακούγεται όταν ο χρήστης κάνει κλικ σε μια από τις επιλογές.

* - [x] Όταν το ποντίκι διέρχεται πάνω από κάποια πρόταση/κείμενο της σελίδας ή περιοχή που περιλαμβάνει γραπτή πληροφορία (π.χ. κάποιο τμήμα γραφήματος), να ακούγεται αυτόματα η αφήγηση του κειμένου (text-to-speech).

Πρόσθεσα αφήγηση κειμένου text-to-speech με χρήση της βιβλιοθήκης [ResponsiveVoiceJS](https://responsivevoice.org/) (μπορεί να χρειαστεί να κάνετε πρώτα κλίκ πάνω στη σελίδα για να δουλέψει).

* - [ ] Εφαρμόστε responsive design στη σελίδα και κυρίως στο αρχικό menu έτσι ώστε να προσαρμόζεται σε οθόνες διαφορετικών διαστάσεων (π.χ. Bootstrap).

Δεν υλοποιήθηκε.


*Όλες οι αλλαγές έχουν δοκιμαστεί σε browser Google Chrome.*

### Παραδοτέο 2 (Άλλαγές)
Links για το δεύτερο παραδοτέο:
* [Αλλαγές στον κώδικα](https://github.com/p15poly/D3js-US-educational-attainment/commits/paradoteo2)

Πηγές κώδικα:
* [Simple D3.js Bar Chart](http://bl.ocks.org/d3noob/8952219)
* [Reusable Bubble Chart](https://github.com/dmesquita/reusable_bubble_chart)
* [D3.js - Graphs](https://www.tutorialspoint.com/d3js/d3js_graphs.htm)

Πηγές νέων Στατιστικών:
* [Γάμοι - Απόλυτοι αριθμοί και ποσοστά (1932 - 2017)](http://www.statistics.gr/el/statistics/-/publication/SPO06/2017)
* [Υιοθεσίες που πραγματοποιήθηκαν κατά γεωγραφικό διαμέρισμα και φύλο](http://www.statistics.gr/el/statistics/-/publication/SHE33/-)
* [Θάνατοι - Απόλυτοι αριθμοί και ποσοστά (1932 - 2017)](http://www.statistics.gr/el/statistics/-/publication/SPO09/2017)

**Ζητούμενα και αλλαγές:**

* - [x] Τροποποιήστε τον κώδικα και το μενού της εφαρμογής έτσι ώστε κάθε στιγμή να είναι εμφανές μόνο ένα από τα 3 γραφήματα, παραμένοντας πάντα στη σελίδα index.html.

Άλλαξα τον κώδικα έτσι ώστε όταν ο χρήστης φέρει τον δείκτη του ποντικιού πάνω από ένα απ' τα κουμπιά στη κορυφή της σελίδας (National, Regional, State-Level), να φαίνεται το ανάλογο γράφημα.

* - [ ] Αντικαταστήστε το κάθε ένα από τα 3 γραφήματα με κάποιο άλλο διαδραστικό γράφημα της D3js.

Δεν υλοποιήθηκε.

* - [x] Σε μια καινούργια σελίδα, να τοποθετήσετε αντίστοιχα 3 νέα διαδραστικά γραφήματα D3js της επιλογής σας, τα οποία θα οπτικοποιούν καινούργια στατιστικά δεδομένα που θα βρείτε από κάποια επίσημη στατιστική αρχή (π.χ. ΕΛΣΤΑΤ, Eurostat κ.λπ.).

Πρόσθεσα τρία κουμπιά στη κορυφή της σελίδας, τα οποία οδηγούν σε τρία νέα γραφήματα. Χρησιμοποίησα στατιστικά από την ΕΛΣΤΑΤ, τα οποία απλοποίησα πρίν χρησιμοποιήσω.

*Όλες οι αλλαγές έχουν δοκιμαστεί σε browser Google Chrome.*

Τέλος, έφτιαξα ξεχωριστό αποθετήριο για την [τελική αναφορά](https://p15poly.github.io/hci-anafora/) μου.

## Εργασία Περιεχομένου:
* [Αποθετήριο Εργασίας Περιεχομένου](https://github.com/p15poly/gr)
### Παραδοτέο Β, "Δύο νέα διαδραστικά παραδείγματα":
Night mode switch:
* [Σελίδα στο fork του βιβλίου](https://p15poly.github.io/gr/remix/night-mode-switch/) (GitHub Pages)
* [Κώδικας στο CodePen](https://codepen.io/vapoly/pen/EOLapj)

Scroll animation:
* [Σελίδα στο fork του βιβλίου](https://p15poly.github.io/gr/remix/scroll-animation/) (GitHub Pages)
* [Κώδικας στο CodePen](https://codepen.io/vapoly/pen/rQKadb)

### Παραδοτέο Γ, "Μία νέα βιογραφία":
Πρόσθεσα μια σύντομη βιογραφία του Myron Krueger.  
* [Αλλαγές στο αποθετήριο](https://github.com/p15poly/gr/commits/gh-pages)
* [Η βιβλιογραφία στο fork του βιβλίου](https://p15poly.github.io/gr/biography/myron-krueger/) (GitHub Pages)
