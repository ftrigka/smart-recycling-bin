# smart-recycling-bin
Implementation of smart recycling bins

Το σύστημα τοποθετείται σε σημεία με κάδους ανακύκλωσης και υπάρχει και σε εφαρμογή στο κινητό.
Στα σημεία ανακύκλωσης:
Όποτε δεν ξέρουμε ένα αντικείμενο από τι υλικό είναι κατασκευασμένο και το αν και που πρέπει να ανακυκλωθεί μπορούμε να χρησιμοποιήσουμε το vision training. Δείχνω στην οθόνη τι θέλω να ανακυκλώσω( χαρτί, αλουμίνιο, φαγητό). Το σύστημα, αναγνωρίζοντας το αντικείμενο, μας δίνει πληροφορίες σχετικά με το υλικό κατασκευής, το χρόνο που χρειάζεται να αποσυντεθεί, τον κάδο στον οποίο οφείλει να πεταχτεί. Επιπλέον, ανοίγει αυτόματα ο αντίστοιχος κάδος. Τα παιδιά θα δημιουργήσουν κάδους ανακύκλωσης από χαρτόνια που ανοίγουν με σερβοκινητήρα για να βάλουμε το ανακυκλώσιμο υλικό.
Στο κινητό:
Το σύστημα, αναγνωρίζοντας το αντικείμενο, μας ενημερώνει για τον κάδο στον οποίο οφείλει να πεταχτεί, αλλά και το που βρίσκεται ο κοντινότερος κάδος. Το σύστημα γνωρίζει τη θέση των κάδων αλλά και την δική μας μέσω GPS.
Επιπλέον, το σύστημα μας δίνει πληροφορίες σχετικά με το υλικό κατασκευής, το χρόνο που χρειάζεται να αποσυντεθεί, και τα αντικείμενα τα οποία μπορούν να κατασκευαστούν με το ανακυκλωμένο υλικό.
Εάν κατά την αναγνώριση το ποσοστό βεβαιότητας είναι κάτω από μια τιμή, θα πρέπει είτε να μας δείχνει τα 2-3 πιθανά αντικείμενα και να αποφασίζουμε εμείς, είτε να μας ωθεί να μαζέψουμε πληροφορίες για το αντικείμενο και να το εκπαιδεύσουμε.
