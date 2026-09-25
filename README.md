# Firefox-Themes-CSS
<a href="https://addons.mozilla.org/en-US/firefox/user/19760903/" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Firefox_Browser_Add-ons_logo.svg" alt="Firefox Add-ons">
</a><br><br>

<b>Custom CSS files for Firefox Themes</b>

<b>You can find all Firefox themes here: [https://addons.mozilla.org/en-US/firefox/user/19760903/](https://addons.mozilla.org/en-US/firefox/user/19760903/) </b>

<b>Προσαρμοσμένα αρχεία CSS για Θέματα Firefox </b>

<b>Μπορείτε να βρείτε ολα τα θέματα Firefox εδω: [https://addons.mozilla.org/el/firefox/user/19760903/](https://addons.mozilla.org/el/firefox/user/19760903/) </b>
<br><br>

---

### 🎨 About the versions
* **Classic**: The traditional design with standard square edges.
* **Nova**: A modern redesign featuring rounded corners, smooth hover effects, and dynamic spacing that adapts to Firefox's UI density settings.

## Customizing Firefox Menu Backgrounds (history, right-click, etc.)

1. Type `about:config` in the Firefox address bar and press Enter
2. If a warning message appears, click on "Accept the Risk and Continue"
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
4. Change its value from `false` to `true` by double-clicking on it
5. **For macOS users ONLY:** Search for `widget.macos.native-context-menus` and change its value to `false`
6. Type `about:support` in the Firefox address bar and press Enter
7. Under the "Application Basics" section, locate the "Profile Directory" or "Profile Folder" row
8. Click the "Open Directory" or "Open Folder" button
9. Inside the downloaded ZIP, you will find two versions: **Classic** and **Nova**. Choose your preferred version, copy its `chrome` folder, and paste it into the profile folder that just opened <br>
	Please check if a chrome folder already exists from a previous customization:<br>
	a) If the folder exists but there is no `userChrome.css` file inside it, simply paste the new `userChrome.css` file into that chrome folder<br>
	b) If a `userChrome.css` file already exists, open it, check its current code, and carefully append/merge your new code into it
10. Restart Firefox
11. Done!

---

### 🎨 Σχετικά με τις εκδόσεις
* **Classic**: Ο παραδοσιακός σχεδιασμός με τις κλασικές τετράγωνες γωνίες.
* **Nova**: Μοντέρνος σχεδιασμός με στρογγυλεμένες γωνίες, ομαλά εφέ και δυναμικές αποστάσεις που προσαρμόζονται στην πυκνότητα του Firefox.

## Προσαρμογή φόντου μενού (ιστορικό, δεξί κλικ κλπ) σε κατάλληλο χρώμα στο Firefox

1. Πληκτρολογήστε στην γραμμή διεύθυνσης του Firefox `about:config` και πατήστε Enter
2. Σε περίπτωση που εμφανιστεί προειδοποιητικό μήνυμα επιλέξτε "Αποδοχή Ρίσκου και Συνέχεια"
3. Αναζητήστε `toolkit.legacyUserProfileCustomizations.stylesheets`
4. Αλλάζετε κατάσταση από `false` σε `true`, κάνοντας διπλό κλικ
5. **ΜΟΝΟ για χρήστες macOS:** Αναζητήστε `widget.macos.native-context-menus` και αλλάξτε την κατάσταση σε `false`
6. Πληκτρολογήστε στην γραμμή διεύθυνσης του Firefox `about:support` και πατήστε Enter
7. Στον πίνακα "Βασικά εφαρμογής" εντοπίστε την γραμμή "Κατάλογος προφίλ" ή "Φάκελος προφίλ"
8. Κλικ στο "Άνοιγμα καταλόγου" ή "Άνοιγμα φακέλου"
9. Μέσα στο ZIP που κατεβάσατε, θα βρείτε δύο εκδόσεις: **Classic** (παλιά) και **Nova** (νέα). Επιλέξτε την έκδοση που προτιμάτε, αντιγράψτε τον φάκελο `chrome` που περιέχει, και κάντε τον επικόλληση στο φάκελο προφίλ που άνοιξε <br>
	Προσοχή μήπως ο φάκελος υπάρχει ήδη από προηγούμενη ενέργεια <br>
	α) Εάν ο φάκελος υπάρχει αλλά δεν υπάρχει αρχείο `userChrome.css` μέσα σε αυτόν, απλώς επικολλήστε το νέο αρχείο `userChrome.css` σε αυτόν τον φάκελο chrome<br>
	β) Εάν υπάρχει ήδη ένα αρχείο `userChrome.css`, ανοίξτε το, ελέγξτε τον τρέχοντα κώδικά του και προσθέστε/συγχωνεύστε προσεκτικά τον νέο κώδικα
10. Επανεκκίνηση του firefox
11. Έτοιμο!
