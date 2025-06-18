# Bilingual-Word-Checker

A flexible, friendly vocabulary quiz web app for any two languages!  
Load your own CSV file, select quiz direction, and boost your language skills with instant feedback and error tracking.

---

## Features

- **Works With Any Two Languages:**  
  Just provide a CSV file with two columns (e.g., `To,From`). You can use English–Arabic, Spanish–French, or any pair you want!

- **Direction Switch:**  
  Instantly flip quiz direction (e.g., quiz from English→Spanish or Spanish→English) with a dropdown.

- **Keyboard-Only Play:**  
  Press Enter to check your answer, and Enter again to move to the next word—no mouse required.

- **Progress & Score:**  
  See your correct, incorrect, and total attempts, plus a visual progress bar.

- **Error Highlighting & History:**  
  Review all words you attempted in a color-coded table—incorrect answers are clearly marked.

- **Encouragement:**  
  Get a random positive message when you get a word right!

---

## How to Use

1. **Prepare your word list**
   - Make a file called `words.csv` (or use your own name, but update the HTML if you do).
   - The FIRST row must be the headers. Example:
     ```
     To,From
     cat,قطة
     dog,كلب
     ```
   - You can use any language for either column—just be consistent!

2. **Open the app**
   - Put `index.html` and your `words.csv` in the same folder.
   - Open `index.html` in your web browser.

3. **Select quiz direction**
   - Use the dropdown at the top to pick which direction you want to be quizzed.

4. **Play!**
   - Type your answer and press Enter.
   - See feedback and your answer history below the quiz.

---

## Customization

- To use a different word file, edit the `fetch('words.csv')` line in the HTML.
- Add as many words as you want. The quiz will shuffle them each time.
- Edit the two column headers to match your languages/labels.

---

## Example

**Spanish to English:**
```
To,From
cat,gato
dog,perro
water,agua
```

**German to French:**
```
To,From
Hund,chien
Katze,chat
Wasser,eau
```

---

## File Structure

```
project-folder/
├── index.html
├── words.csv
├── README.md
```

---

## Credits

Created by [SkibidiRany](https://github.com/SkibidiRany) with help from GitHub Copilot and the open source community.

---

## License

MIT License.  
Free to use, adapt, and share!