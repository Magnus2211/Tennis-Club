# DA Tennis Club Ομαδα 12

Στο συγκεκριμενο repo εχει γινει το ομαδικο project της ομαδας 12,όπου αφορά την ανάπτυξη εφαρμογής ενός tennis club για το μάθημα:
```
Προγραμματισμός Διαδικτύου (ECE_ΓΚ802)
```
Απο τους φοιτητές:
```
Δημήτριο Φεφέ
Ανδρέα Γαλανη
```
# Περιγραφη

Σε αυτή την εφαρμογή,μπορεί να κάνει εγγραφή ένας νέος χρήστης και με την σύνδεση του στην εφαρμογή να κλείσει ώρα/ώρες σε όποια μέρα θα ήθελε να παίξει tennis.Επίσης οποιοσδήποτε (είτε είναι εγγεγραμμένος χρήστης ή οχι) μπορεί να επικοινωνήσει σε μια φόρμα επικοινωνίας.Ο διαχειριστής της εφαρμογής(admin) μπορεί να δει τα μηνύματα επικοινωνίας που έχουν σταλεί μέσω της φόρμας επικοινωνίας.Επιπλέον,ο admin μπορεί να δει όλα τα bookings που έχουν γίνει,καθώς και να "κλείσει" συγκεκριμένα time slot,ώστε να μην μπορεί κάποιος να κάνει κράτηση(πχ για λόγους συντήρησης κάποιου γηπέδου).

Τα modules που χρησιμοποιήθηκαν είναι:
```
bcrypt
better-sqlite3
dotenv
express
express-handlebars
express-session
randomcolor
node-fetch
```

Αν κατεβασετε το repository,ενδεχομενως να ειναι προτιμοτερο να διαγραψετε τον φακελο
```
node_modules
```
και να τρεξετε στο terminal την εντολη:
```
npm i
```

Θα πρεπει να εκτελεσετε πρωτα στο terminal την εντολη
```
node adminSetup.js
```
για να δημιουργηθει ο admin.Τα credentials του είναι:
```
username=admin
password=1234
```
Για την εκτέλεση της εφαρμογής απλά τρέχετε την εντολή(δεδομένου ότι είστε στο σωστό path):
```
npm start
```


