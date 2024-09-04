# Language Translator

Language Translator is a web-based application that allows users to translate text between various languages. The application supports over 50 languages, enabling users to input text in one language and receive the translated text in another.

 # Features
- Multi-language Support: Translate between more than 50 languages.
- Auto Language Detection: Automatically detects the input language.
- File Upload: Upload text documents (PDF, DOC, TXT) to translate.
- Download Translations: Save translated text as a document.
- Dark Mode: Toggle between light and dark modes for better readability.

# Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/language-translator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd language-translator
   ```
3. Add Google Translate API URL:
   - In the `script.js` file, locate the `translate` function.
   - Replace `your api url` with your actual Google Translate API URL.
   Example:
   ```javascript
   const url = `https://translation.googleapis.com/language/translate/v2?key=YOUR_API_KEY&q=${encodeURI(
     inputText
   )}&source=${inputLanguageValue}&target=${outputLanguageValue}`;
   ```

4. Run the Project:
   Open the `index.html` file in a web browser to see the language translator in action.


# File Structure
- `index.html`: The main HTML file that contains the structure of the web application.
- `style.css`: Contains all the styles used in the application, including light and dark modes.
- `languages.js`: Holds the list of supported languages with their corresponding codes.
- `script.js`: Contains the logic for handling language selection, text translation, and file operations.

# Customization
- Adding New Languages: Update the `languages.js` file with new language options.
- Styling: Modify `style.css` to change the look and feel of the application.
- API Integration: Replace the placeholder API URL in `script.js` with a real translation API.


