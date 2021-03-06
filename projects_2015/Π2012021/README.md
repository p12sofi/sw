#Δημιουργία map tour application με το app inventor

Γραμμένος Πασχάλης
AM: Π2012021

## Τελική Αναφορά


### Alexandroupolis tour

#### Σύνοψη

Η εφαρμογή που δημιούργησα ονομάζεται Alexandroupolis tour. Αναπτύχθηκε με την βοήθεια του εργαλείου MIT app inventor 2. Έχει συνδυασμούς απο διάφορα tutorial στο internet τα οποία δείχνουν πώς να φτιάξεις μια εφαρμογή για map tour. Το ένα είναι το tutorial της εφαρμογής Paris map tour και το αντίστοιχο London map tour απο βίντεο στο διαδίκτυο. Όπως επίσης χρησιμοποιήθηκε ένα tutorial το οποίο έδειχνε πώς μπορεί κάποιος να προσθέσει την λειτουργία της αποθήκευσης ενός προορισμού και την δυνατότητα να μπορεί να βρίσκει την τοποθεσία του στον χάρτη. Το τελευταίο tutorial είναι το «Map It:Displaying Locations on a Google Map».


#### Εισαγωγή

Ο κύριος σκοπός της εφαρμογής είναι η περιήγηση του χρήστη στην πόλη της Αλεξανδρούπολης. Αυτό μπορεί να επιτευχθεί με την δυνατότητα να επιλέξει μέσα απο 7 προορισμούς οι οποίοι είναι είδη αποθηκευμένοι στην εφαρμογή, αλλα επίσης και με την δυνατότητα του χρήστη να προσθέσει σε μια λίστα τον προορισμό που επιθυμεί και έπειτα να τον αναζητήσει στον χάρτη. Επίσης δίνει την δυνατότητα στον χρήστη να μπορέσει να δει την τοποθεσία του στον χάρτη, για ευκολία αλλα και για να μπορέσει να δει ποιοι προορισμοί είναι κοντά του και να τους επισκεφτεί. Η εφαρμογή ξεκινώντας σου δείχνει την κυρίως οθόνη η οποία έχει σαν backround το κυρίως αξιοθέατο της Αλεξανδρούπολης, τον φάρο. Υπάρχουν 3 κουμπάκια για αρχή. Το ένα είναι η «Επιλογή προορισμού» το οποίο πατώντας το εμφανίζει τους υπάρχοντες 7 προορισμούς όπως είπα και πριν. Το δεύτερο κουμπάκι είναι η «Προσθήκη» το οποίο πατώντας το εμφανίζει στο κάτω μέρος της εφαρμογής ένα textbox για να γράψει ο χρήστης τον προορισμό του αλλα και δυο κουμπάκια, το «Υποβολή» και το «Ακύρωση». Πατώντας την υποβολή αποθηκεύεται ο προορισμός και εμφανίζεται ένα κουμπάκι το οποίο λέγεται «Αναζήτηση αποθηκευμένων προορισμών». Πατώντας το ανοίγει η λίστα με τους προορισμούς που έχει προσθέσει ο χρήστης. Το τελευταίο κουμπάκι ονομάζεται «Η τοποθεσία μου στον χάρτη» το οποίο πατώντας το ανοίγουν οι χάρτες και δείχνει στον χρήστη που βρίσκεται εκείνη την στιγμή.


####Επιλογή εργαλείων

Για την διαδικασία ανάπτυξης της εφαρμογής χρησιμοποιήθηκε το εργαλείο MIT app inventor 2. Ο λόγος που επιλέχθηκε το συγκεκριμένο εργαλείο είναι επειδή ήταν το προτεινόμενο και σε γενικές γραμμές είναι πολύ απλό στην χρήση του. Απλό κατανοητό και κατάλληλο για αρχάριους μιας και χρησιμοποιείς blocks για να αναπτύξεις την εφαρμογή που επιθυμείς. Η μόνη δυσκολία που συνάντησα ήταν για την διαμόρφωση της εμφάνισης της αρχικής οθόνης της εφαρμογής, την θέση των κουμπιών δηλαδή αλλα το αποτέλεσμα ήταν αρκετά καλό μπορώ να πω. Το app inventor σου δίνει διάφορα εργαλεία στην διάθεση σου για να υλοποιήσεις ό,τι επιθυμείς. Επίσης σου παρέχει την δυνατότητα να χρησιμοποιήσεις διάφορους αισθητήρες ενός android κινητού αλλα και την δυνατότητα να βάλεις κάποια μικρή βάση δεδομένων στην εφαρμογή για να αποθηκεύονται κάποια δεδομένα, όπως στην συγκεκριμένη εφαρμογή έχει χρησιμοποιηθεί το Tiny DB για την αποθήκευση των προορισμών του χρήστη. Ένα μειονέκτημα του εργαλείου που χρησιμοποίησα είναι οτι δεν σου δίνει την δυνατότητα να επιλέξεις διαφορετικό screen για starting screen της εφαρμογής απο αυτό που σου δίνει στην αρχή. Δηλαδή άμα εγώ προσθέσω ένα Screen2 δεν μπορώ να το κάνω να είναι αυτό το home screen για την εφαρμογή μου. Παρ'όλα αυτά το app inventor είναι εύκολο στο να μάθει κανείς να το χρησιμοποιεί μιας και υπάρχουν πολλά βίντεο στο internet και αρκετά tutorial που μπορεί να συμβουλευτεί κανείς.


####Διαδικασία Ανάπτυξης

Ξεκινώντας την ανάπτυξη της εφαρμογής έφτιαξα την αρχική οθόνη με μια εικόνα η οποία είναι χαρακτηριστική της πόλης και ένα κουμπάκι το οποίο πατώντας το άνοιγε η λίστα με τους προορισμούς για την Αλεξανδρούπολη. Στην συνέχεια κάνοντας κάποιες αλλαγές στην λίστα με τους προορισμούς και βάζωντας αυτούς που πιστεύω πως πρέπει να επισκεφθεί κανείς είχε ολοκληρωθεί η πρώτη version της εφαρμογής μου. Στην συνέχεια και μετά την παρότρυνση του διδάσκοντα να τοποθετήσω και κάποια άλλη λειτουργία στην εφαρμογή ξενίνησα να δουλεύω πάνω στην τοποθέτηση ενος Tiny DB και την δυνατότητα του χρήστη να προσθέτει σε μια ξεχωριστή λίστα τους προορισμούς που θέλει να αναζητήσει στον χάρτη ο ίδιος. Μία επιπλέον λειτουργία που προστέθηκε στο τέλος ήταν η δυνατότητα του χρήστη να μπορεί να αναζητήσει την τοποθεσία του στον χάρτη, το οποίο μπορεί να βοηθήσει αρκετά, ειδικά κάποιους τουρίστες οι οποίοι επισκέπτονται πρώτη φορά την πόλη και έχουν χαθεί ή θέλουν να δουν ποια αξιοθέατα είναι κοντά στην τοποθεσία τους. Έτσι η εμφάνιση της εφαρμογής άλλαξε αρκετα μετά την τελική παρουσίαση. Σε γενικές γραμμές η λειτουργία της εφαρμογής επιτυγχάνεται ως εξής: ο χρήστης επιλέγωντας τον προορισμό που επιθυμεί απο τους ήδη αποθηκευμένους ανοίγει η εφαρμογή Google Maps και αναζητεί για την τοποθεσία που επιλέχθηκε βάση του ονόματός της. Για την λειτουργία να μπορεί να βλέπει ο χρήστης την τοποθεσία του στον χάρτη χρησιμοποιούνται τα Google Maps με την βοήθεια του Location Sensor. 


####Διάγραμμα Λειτουργίας

![alt tag](https://github.com/gpasxalis/gpasxalisRepository/blob/master/%CE%94%CE%B9%CE%AC%CE%B3%CF%81%CE%B1%CE%BC%CE%BC%CE%B1%20%CE%BB%CE%B5%CE%B9%CF%84%CE%BF%CF%85%CF%81%CE%B3%CE%AF%CE%B1%CF%82/%CE%94%CE%B9%CE%AC%CE%B3%CF%81%CE%B1%CE%BC%CE%BC%CE%B1%20%CE%BB%CE%B5%CE%B9%CF%84%CE%BF%CF%85%CF%81%CE%B3%CE%AF%CE%B1%CF%82.jpg)


####Ενδεικτικές οθόνες

Η αρχική οθόνη της εφαρμογής και οι λειτουργίες που περιέχει.

![alt tag](https://github.com/gpasxalis/gpasxalisRepository/blob/master/screenshot/%CE%BF%CE%B8%CF%8C%CE%BD%CE%B7%20%CE%B5%CF%86%CE%B1%CF%81%CE%BC%CE%BF%CE%B3%CE%AE%CF%82.jpg)

Τα blocks της εφαρμογής.

![alt tag](https://github.com/gpasxalis/gpasxalisRepository/blob/master/screenshot/appblocks1.jpg)
![alt tag](https://github.com/gpasxalis/gpasxalisRepository/blob/master/screenshot/appblocks2.jpg)
![alt tag](https://github.com/gpasxalis/gpasxalisRepository/blob/master/screenshot/appblocks3.jpg)



####Συμπεράσματα

Μετά την ολοκλήρωση της υλοποίησης της εφαρμογής κατανοήθηκε η λειτουργία του εργαλείου MIT app inventor 2 και των λειτουργιών που παρέχει. Σε γενικές γραμμές με την παρακολούθηση κάποιων ενδεικτικών βίντεο στο youtube και την αναζήτηση tutorials στο internet μπορείς να δημιουργήσεις πολύ καλά πράγματα στο app inventor χωρίς να έχεις γνώσεις προγραμματισμού μιας και το εργαλείο το συγκεκριμένο χρησιμοποιεί blocks για να φτιάξεις μια λειτουργία κτλ. Επίσης πιστεύω οτι άμα δεν υπήρχαν κάποια μειονεκτήματα που ανέφερα πιο πάνω θα ήταν σχεδόν τέλειο για την δημιουργία μιας εφαρμογής για ένα smartphone.



--------------------

Το αρχείο apk για την εγκατάσταση της εφαρμογής στο κινητό αλλα και ολόκληρο το project σε aia αρχείο έτσι ώστε να γίνει import στο app inventor και να δείτε τα blocks αλλα και την οθόνη της εφαρμογής και τα περιεχόμενά της βρίσκονται [εδώ](https://github.com/gpasxalis/gpasxalisRepository)


