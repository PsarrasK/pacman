# Ονοματεπώνυμο φοιτητή: Ψαρράς Κωνσταντίνος

# Αριθμός Μητρώου: Π2014004

### [Η εργασία στο προσωπικό μου αποθετήριο](https://github.com/PsarrasK/pacman)

### [Σύνδεσμος για το εκτελέσιμο](https://psarrask.github.io/pacman/pacman.html)

(Προτείνεται η εκκαθάριση της κρυφής μνήμης πριν την επίσκεψη στη σελίδα του εκτελέσιμου. Δείτε στο τέλος της σελίδας για περισσότερα)

# Pac-Man: Plants vs Zombies edition

## Εισαγωγή

Το συγκεκριμένο project είναι μια παραλλαγή του κλασσικού παιχνιδιού Pac-Man, της εταιρείας Namco, το οποίο κυκλοφόρησε το 1980 και αποτελεί εργασία για το μάθημα "Τεχνολογία Λογισμικού" του ΣΤ' εξαμήνου στο τμήμα Πληροφορικής του Ιονίου Πανεπιστημίου.

Στόχος της εργασίας είναι να διαφοροποιηθεί και να επεκταθεί το παιχνίδι ως προς την αρχική έκδοσή του, όσον αφορά το περιβάλλον αλλά και το gameplay. 
Συγκεκριμένα στο παιχνίδι ενσωματώθηκαν στοιχεία του επίσης γνωστού παιχνιδιού Plants vs Zombies από την PopCap Games, (με έτος κυκλοφορίας του πρώτου παιχνιδιού της σειράς, το 2009) από το οποίο επιλέχθηκε ως πρωταγωνιστής ο χαρακτήρας Chomper λόγω του χαρακτηριστικού του να τρώει τους αντιπάλους του, όπως ακριβώς και ο Pac-Man (όταν αυτοί γίνονται ευάλωτοι). 

## Σύνοψη

Στόχος του παιχνιδιού είναι ο Chomper να καταναλώσει όλες τις σταγόνες νερού στην πίστα, πράγμα που τον βοηθά στο να γίνει ένα δυνατό (σαρκοφάγο) φυτό. Το power-up που θα δώσει στο χαρακτήρα μας τη δυνατότητα να αντιμετωπίσει τα ζόμπι (δηλαδή το Superspeed), εμφανίζεται όταν συλλεχθούν πέντε αντικείμενα-ήλιοι, και μένει στην πίστα για τρία έως οχτώ δευτερόλεπτα, έτσι ώστε να υπάρχει ένας βαθμός δυσκολίας στη δοκιμασία, μιας και επιλέχθηκε τα ζόμπι να μην ξανακάνουν spawn μετά την εξουδετέρωσή τους. Από τη στιγμή που θα ενεργοποιηθεί το Superspeed, ο παίχτης έχει πέντε δευτερόλεπτα για να σκοτώσει όλα τα ζόμπι με τα οποία θα έρθει σε επαφή. Ο Chomper έχει τη δυνατότητα να τηλεμεταφερθεί μεταξύ του δέντρου και του ναού απλά εισερχόμενος σε ένα από αυτά. Για κάθε πενήντα σταγόνες απονέμεται στον παίχτη μια ζωή. Αν υπάρχουν ήδη τρεις ζωές στην κατοχή του τότε οι σταγόνες αυξάνουν το συνολικό σκορ. Τέλος υπάρχει δυνατότητα επιλογής της δυσκολίας του παιχνιδιού μεταξύ Easy, Medium και Hard. 

## Επιλογή εργαλείων

Για την εκπόνηση της εργασίας χρησιμοποιήθηκαν τα εξής εργαλεία:
- XAMPP για την τοπική εκτέλεση του κώδικα,
- Notepad++ για την επεξεργασία του κώδικα,
- GIMP για την επεξεργασία ή και τη δημιουργία των εικόνων που χρησιμοποιήθηκαν,
- Tiled για τη δημιουργία της πίστας και των layers που χρησιμοποιήθηκαν και επηρέασαν τη συμπεριφορά του παιχνιδιού,
- Audacity για την επεξεργασία και προσαρμογή των ηχητικών εφέ που χρησιμοποιήθηκαν.

## Διαδικασία Ανάπτυξης

Αρχικά στο πρώτο παραδοτέο έγινε επιλογή του παιχνιδιού Pacman ως θέμα της εργασίας.

Για το δεύτερο παραδοτέο έγινε αλλαγή του πρωταγωνιστή από τον Pac-Man, στο χαρακτήρα του παιχνιδιού Plants vs Zombies, τον Chomper. Τα sprites για το χαρακτήρα δημιουργήθηκαν από το μηδέν στο πρόγραμμα GIMP χρησιμοποιόντας ως πρότυπο την εικόνα του [link 1](http://orig00.deviantart.net/a41b/f/2013/347/8/4/plants_vs_zombies__chomper_by_thumbzdown-d6xvabc.png), όπως επίσης και τα sprites του χαρακτήρα ζόμπι που κάνει την εμφάνιση του στο τέταρτο παραδοτέο.
Επίσης έγινε αλλάγή των κύριων πόντων που μαζεύει ο πρωταγωνιστής από τελείες σε σταγόνες και προσθήκη δευτερεύοντος αντικειμένου, του ήλιου, το οποίο σε επόμενο παραδοτέο ενεργοποιεί κάποια νέα χαρακτηριστικά στο gameplay. Και αυτά τα αντικείμενα δημιουργήθηκαν από το μηδέν στο GIMP, χωρίς τη χρήση προτύπων.
Επιπλέον δημιουργήθηκε νέα πίστα στο πρόγραμμα Tiled, με sprites που πάρθηκαν από τη σελίδα spriters-resource.com και συγκεκριμένα από την εικόνα του [link 2](https://www.spriters-resource.com/fullview/61816/) (η οποία απεικονίζει μέρη του βασικού χάρτη του παιχνιδιού Pokemon Emerald) και επεξεργάστηκαν για να φτάσουν στο επιθυμητό αποτέλεσμα, αλλά και πολλά tiles (όπως οι τάφοι) που δημιουργήθηκαν επίσης από την αρχή καθώς δε βρέθηκε ικανοποιητική εναλλακτική έτοιμων sprites.
Τέλος έγιναν αλλαγές στον κώδικα της σελίδας όπου κρίθηκε αναγκαίο κάνοντας χρήση του προγράμματος Notepad++.

Σε αυτό το στάδιο, του τρίτου παραδοτέου έγινε προσθήκη Background music αλλά και ηχητικών effects στο παιχνίδι. Επίσης προστέθηκε χρόνος αλλά και μια αντίστροφη
μέτρηση στην αρχή, ώστε να δωθεί χρόνος στον παίκτη να προετοιμαστεί και στον browser να κατεβάσει τα δεδομένα που χρειάζεται για να είναι ομαλή η εμπειρία του gameplay. Η μελωδία βρέθηκε στο [link 3](https://www.youtube.com/watch?v=OEF_26niVp4) και προσαρμόστηκε χρονικά ώστε να συμπίπτει με την αλλαγή των δευτερολέπτων ώστε ο παίχτης να έχει μια αίσθηση παρόδου του χρόνου.
Σε δεύτερη φάση δημιουργήθηκαν περισσότερα sprites του Chomper τα οποία απεικονίζουν σωστά την κάθετη κίνηση χαρακτήρα στην πίστα (δηλαδή το πάνω-κάτω).
Έχει γίνει προθήκη score το οποίο αυξάνεται κατά ένα όταν ο Chomper καταναλώνει μια σταγόνα. Ο ρόλος των ήλιων είναι να εμφανίζει ένα SuperSpeed powerup κάθε φορά που συλλέγονται 5 ήλιοι.
Το Superspeed κάνει spawn (εμφανίζεται δηλαδή) και παραμένει στην πίστα για 3-8 δευτερόλεπτα τυχαία, ενώ εμφανίζεται στο κεντρικό πάνω μέρος της οθόνης και ο χρόνος για τον οποίο θα παραμείνει στην πίστα το powerup. Όταν ο Chomper συλλέξει ένα από τα SuperSpeed που εμφανίζονται, όλα τα SuperSpeed εξαφανίζονται και ο χαρακτήρας κινείται πιο γρήγορα για 5 δευτερόλεπτα.
Επιπλέον προστέθηκαν ζωές, οι οποίες αυξάνονται κατά μια κάθε φορά που επιτυγχάνεται score 50, με τη λογική της εξαργύρωσης της ζωής με το κόστος πόντων. Αν οι ζωές είναι τρείς (μέγιστο) το score συνεχίζει να αυξάνεται και πέρα των 50.
Τα ηχητικά effects που έχουν προστεθεί είναι τα beeps στην αρχική αντίστροφη μέτρηση, ένα γέλιο με τη φωνή του Chomper κάθε φορά που συλλέγεται ένας ήλιος, ένας ήχος κατάποσης κάθε φορά που καταναλώνονται πέντε σταγόνες, ένας ήχος μαρσαρίσματος από μηχανάκι όταν συλλέγεται SuperSpeed και τέλος ένας πανηγυρισμός με τη φωνή του Chomper όταν επιτευχθεί η συλλογή όλων των σταγόνων στην πίστα.

Τέλος για το τέταρτο παραδοτέο προστέθηκαν εχθροί, τα ζόμπι τα οποία δημιουργήθηκαν από το μηδέν όπως προαναφέρθηκε στο παραδοτέο δύο. Ο αριθμός και η ταχύτητα κίνησής τους ποικίλει ανάλογα με τη δυσκολία παιχνιδιού του επιλέγεται κάθε φορά. Τα ζόμπι κινούνται με μια ψευδοτυχαιότητα σε προκαθορισμένες περιοχές της πίστας και αλλάζουν κατεύθυνση κάθε φορά που συγκρούονται με κάποιο από τα ορισμένα tiles. 
Σε αυτό το σημείο, έχοντας πια εχθρούς το Superspeed δίνει επίσης στο χαρακτήρα μας τη δυνατότητα να τους σκοτώνει, για τη μικρή διάρκεια των πέντε δευτερολέπτων.
Προστέθηκε επίσης η δυνατότητα τηλεμεταφοράς του χαρακτήρα μεταξύ της τρύπας του δένδρου και της εισόδου στο ναό, κάθε φορά που ο Chomper εισέρχεται σε ένα από τα δύο.
Προστέθηκε εισαγωγική οθόνη για την επεξήγηση του τρόπου λειτουργίας του παιχνιδιού και κουμπί για την παύση και συνέχιση του από το χρήστη.
Τέλος έγινε προσθήκη επιπέδων δυσκολίας, μόνο και μόνο για το hype και τη μικρότερη δυσκολία για άτομα στο περιβάλλον μου που δε θα χαρακτήριζα gamers αλλά η συμμετοχή τους στη δοκιμή και αξιολόγηση του παρόντος παιχνιδιού ήταν για μένα σημαντική. 

## Screenshots
Κάντε hover με το ποντίκι για να εμφανιστεί η περιγραφή των εικόνων

![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr1.png "Αρχική οθόνη - Πληροφορίες")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr2.png "Επιλογή δυσκολίας")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr3.png "Στιγμιότυπο Gameplay")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr4.png "Όταν συλλεχθούν 5 ήλιοι")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr5.png "Όταν συλλεχθεί Superspeed")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr6.png "Στιγμιότυπο Gameplay PAUSED")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr7.png "Στιγμιότυπο Gameplay YOU WIN!")
![alt text](https://github.com/PsarrasK/pacman/blob/master/screenshots/scr8.png "Στιγμιότυπο Gameplay GAME OVER")

## Συμπεράσματα

- Η Phaser είναι μια ενδιαφέρουσα βιβλιοθήκη με υλικό και αρκετές δυνατότητες για mini games.
- Τα προγράμματα που χρησιμοποιήθηκαν είναι αρκετά εύχρηστα και δε χρειάζονται πολλές γνώσεις για να εγκλιματιστεί κανείς πολύ γρήγορα.
- Δεν υπάρχουν αρκετά παραδείγματα χρήσης της Phaser για όλα όσα πραγματοποιήθηκαν στην παρούσα εργασία.
- Η διασύνδεση και προσαρμογή των χαρακτηριστικών που έχουν προστεθεί στο παιχνίδι είναι αρκετά απαιτητική και οι αλλαγές που πρέπει να πραγματοποιηθούν κάθε φορά από τη σκοπιά του κώδικα, αυξάνονται σχεδόν εκθετικά.
- Παρατηρήθηκε πρόβλημα με την τηλεμεταφορά σε κάποιες περιπτώσεις, χωρίς αναφορά τύπου error από τον περιηγητή. Επιλύθηκε με εκκαθάριση της κρυφής μνήμης ή αλλαγή περιηγητή (αφού πρώτα σπαταλήθηκε χρόνος στην εύρεση της πιθανής αιτίας του bug). (Ο κώδικας και η αξιοπιστία του εκτελέσιμου έχει ελεγχθεί σε Chrome και Firefox και δεν παρουσίασε κανένα πρόβλημα εφόσον η κρυφή μνήμη έχει καθαριστεί.)
