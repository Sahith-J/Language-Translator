# Bharat-Intern-Language-Translator

This is a Python script that utilizes the `googletrans` library to translate text or files to different languages using Google Translate. It provides the following functionality:

- Translating text: You can enter a text and specify the target language to translate it.
- Detecting language: You can enter a text and the script will attempt to detect the language of the input.
- Translating files: You can provide a file path and specify the target language to translate the contents of the file.

## Requirements

To run this script, you need to have the following dependencies installed:

- `googletrans`: You can install it using `pip install googletrans==4.0.0-rc1`.

## Usage

1. Clone this repository or download the script file.
2. Install the required dependencies.
3. Run the script using Python.

The script will display a menu with options for translation and language detection. Follow the prompts to interact with the translator tool.

### Menu Options

- Enter `q` to quit the translator tool.
- Enter `t` to translate text.
- Enter `d` to detect language.
- Enter `f` to translate a file.

When translating text or files, you will be prompted to enter the input and target language.

Note: Make sure to have an internet connection as the script relies on the Google Translate service.

## Examples

1. Translate text:
Enter the text to translate: Hello

Enter the target language: es

Output:

Source Language: en

Translated Text: Hola

2. Detect language:
Enter the text to detect language: Bonjour

Output:

Detected Language: fr

Confidence: 1.0

3. Translate a file:
Enter the file path to translate: /path/to/file.txt

Enter the target language: de

Output:

Source Language: en

Translated Text: (Contents of the file in German)

## Contributions

Contributions to this script are welcome. If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.
