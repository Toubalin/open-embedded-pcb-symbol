# Παγκόσμιο Οπτικό Σύμβολο Προειδοποίησης Ενσωματωμένων Εξαρτημάτων PCB (Open-EPS)

### Σκοπός & Χρηστικότητα (Abstract)
Λόγω της ραγδαίας εξέλιξης της τεχνολογίας **Embedded Components (ενσωματωμένα εξαρτήματα)**, οι σύγχρονες πολυστρωματικές πλακέτες (multi-layer PCBs) φιλοξενούν πλέον αντιστάσεις, πυκνωτές ή ολοκληρωμένα κυκλώματα **μέσα** στα εσωτερικά τους στρώματα (internal layers) και όχι μόνο στην εξωτερική τους επιφάνεια. 

Όταν μια τέτοια πλακέτα παρουσιάζει βλάβη, η επιφάνειά της (silkscreen) φαίνεται απατηλά «άδεια», με αποτέλεσμα οι τεχνικοί να επιχειρούν αδύνατες χειρουργικές επεμβάσεις, καταστρέφοντας το PCB και χάνοντας πολύτιμο χρόνο. 

Το παρόν **ανοιχτό σύμβολο (Open-Source Icon)** σχεδιάστηκε για να τυπώνεται απευθείας στην επιφάνεια (silkscreen) της πλακέτας. Λειτουργεί ως μια **διεθνής, άμεση οπτική προειδοποίηση** προς τους τεχνικούς: **«Μην επιχειρήσετε επισκευή - Μη επισκευάσιμο υλικό (Board Replacement Only)».**

---

### Ανάλυση των δύο Σχεδιαστικών Παραλλαγών

Το project προσφέρει δύο εναλλακτικές οπτικές προσεγγίσεις για να επιλέξει ο σχεδιαστής:

#### 1. Εκδοχή Α (Μινιμαλιστική Απαγόρευση - Κυκλικό Σχήμα)
*   **Στοιχεία:** Οριζόντιες γραμμές (layers), εσωτερικά σύμβολα αντίστασης και πυκνωτή, και το γερμανικό κλειδί (service).
*   **Μήνυμα:** Μια καθαρή, μακριά λευκή διαγώνια γραμμή τέμνει το σύμβολο του service, επικοινωνώντας ακαριαία την απαγόρευση επισκευής, αφήνοντας τα εξαρτήματα πεντακάθαρα.

#### 2. Εκδοχή Β (Κλειδωμένη Δομή - Τετράγωνο Σχήμα)
*   **Στοιχεία:** Οριζόντιες γραμμές (layers), εσωτερικά σύμβολα αντίστασης και πυκνωτή, και ένα κλασικό λουκέτο στην κορυφή.
*   **Μήνυμα:** Εστιάζει στην έννοια της «κλειδωμένης» και απροσπέλαστες αρχιτεκτονικής. Το λουκέτο προειδοποιεί ότι τα εσωτερικά στρώματα είναι σφραγισμένα και μη προσβάσιμα για συντήρηση.

---

### Δήλωση Χρήσης Τεχνητής Νοημοσύνης (AI Disclaimer)
**Σημείωση Σχεδίασης:** Η σύλληψη της ιδέας, η λειτουργικότητα, η επιλογή των ηλεκτρονικών συμβόλων και η δομή των παραλλαγών ανήκουν αποκλειστικά στον δημιουργό. Η οπτική υλοποίηση, η ψηφιοποίηση και η παραγωγή των τελικών γραφικών αρχείων (icons) πραγματοποιήθηκαν με τη συνδρομή εργαλείων **Τεχνητής Νοημοσύνης (AI-Generated Graphics)**, ακολουθώντας ακριβείς και διαδοχικές σχεδιαστικές οδηγίες (prompt engineering) για την επίτευξη του τελικού βιομηχανικού αποτελέσματος.

---

### Άδεια Χρήσης (License)
Και οι δύο εκδοχές του συμβόλου διατίθενται υπό την παγκόσμια άδεια **Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)**. 
*   **Επιτρέπεται:** Η ελεύθερη χρήση, ενσωμάτωση και εκτύπωση του συμβόλου σε οποιοδήποτε εμπορικό ή open-source hardware project παγκοσμίως, χωρίς κανένα κόστος ή παράβολο.
*   **Απαιτείται:** Η αναφορά στο όνομα του δημιουργού.
*   **Απαγορεύεται:** Η τροποποίηση ή αλλαγή των σχεδιαστικών στοιχείων, προκειμένου να διατηρηθεί η ομοιομορφία του συμβόλου ως παγκόσμιο σταθερό πρότυπο (standard).



# Global Visual Warning Standard for Embedded PCB Components (Open-EPS)

### 📋 Abstract & Purpose
With the rapid advancement of **Embedded Components** technology, modern multi-layer PCBs now host resistors, capacitors, or integrated circuits **inside** their internal layers, rather than exclusively on the external surfaces (top/bottom layers). 

When such a board fails, its surface (silkscreen) appears deceptively "empty" and safe for rework. This often leads technicians to attempt impossible surgical troubleshooting or soldering, destroying the PCB structure and wasting valuable time and resources.

This **Open-Source Icon** was designed to be printed directly on the board's surface (silkscreen). It serves as a **global, instantaneous visual warning** for hardware engineers, repair technicians, and support personnel: **"Do Not Attempt Repair - Non-Serviceable Material (Board Replacement Only)".**

---

### Visual Design Variants

The project offers two alternative visual approaches for designers to choose from based on their PCB aesthetic constraints:

#### 1. Version A (Minimalist Prohibition - Circular Frame)
*   **Elements:** Horizontal lines (representing multi-layers), internal schematic symbols for a resistor and a capacitor, and a service wrench.
*   **Message:** A clean, extended white diagonal line cuts across the service wrench. This communicates an immediate repair prohibition while leaving the underlying embedded electronic symbols fully visible and unobstructed.

#### 2. Version B (Locked Architecture - Square Frame)
*   **Elements:** Horizontal lines (representing multi-layers), internal schematic symbols for a resistor and a capacitor, topped with a distinct padlock icon.
*   **Message:** Focuses heavily on the concept of a "locked" and impenetrable hardware architecture. The padlock warns the technician that the inner layers are sealed, proprietary, or physically impossible to access for maintenance.

---

### AI-Generated Graphics Disclaimer
**Design Note:** The core conceptualization, structural functionality, choice of electronic symbols, and the creation of design variants belong entirely to the author. The visual implementation, digitization, and production of the final high-definition graphics files (icons) were executed with the assistance of **Artificial Intelligence (AI-Generated Graphics)** tools, following precise, sequential, and iterative prompt engineering guidelines to achieve the final industrial-grade output.

---

### Open-Source License
Both versions of the symbol are distributed under the global **Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)**.
*   **Permitted:** Anyone (including commercial industries, independent makers, or open-source hardware projects) is free to download, embed, and print this symbol on their PCBs globally, at no cost and without any fees.
*   **Required:** Appropriate attribution must be given to the original creator.
*   **Prohibited:** Modifying, altering, or creating derivative works from the design elements is strictly forbidden, ensuring the symbol remains an unmodified, uniform, and easily recognizable global standard.
