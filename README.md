[![Twitter Follow](https://img.shields.io/twitter/follow/alxfazio?style=social)](https://twitter.com/alxfazio) [![Open Main Version In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alexfazio/srt-GPT-translator/blob/main/srt_gpt_translator_claude.ipynb)

# `.srt` GPT Translator (Google Colab)

This tool is designed to help users translate srt file into a different language using the Antrhopic (Claude 3) API . Does not support bilingual subtitles output.

## Description
Translate `.srt` files from any language to any language using Anthropic (Claude). This Google Colab notebook provides a seamless way to translate `.srt` subtitle files between any supported languages using state-of-the-art language models from Anthropic (Claude). With just a few simple steps, you can quickly and accurately translate your subtitles, making your content accessible to a wider audience.

Feel free to contribute to the project by submitting pull requests or reporting issues on the GitHub repository. Your feedback and contributions are greatly appreciated!

## Features
- Translate `.srt` files between any supported languages using Anthropic (Claude) or OpenAI APIs.
- Easy-to-use Google Colab notebook interface.

## Instructions
To translate an `.srt` file:
1. Open the Google Colab notebook.
2. Insert your API key in the designated cell.
3. Upload your `.srt` file to the notebook.
4. Run the notebook cells to execute the translation process.
5. Download the translated `.srt` file(s) from the notebook.

## Upcoming Enhancements
- Implement an API selector to choose between OpenAI and Anthropic APIs.
- (Optional and Low Priority) Implement a string cleaner for improved output (Reference: https://x.com/mattshumer_/status/1777541303288340613).
- Make the API key either an environment variable or provide a custom form space for the end user to input their key.
- Implement context length selector, a toggle or slider that decides how many context words are given to the text. This is the number of segments used to flank the target segments and pass to the LLM for richer context reference during translation. The higher the context segments, the slower the process and more expensive in terms of API call usage, but more precise.
- Support for bilingual subtitle output.

## API Documentation
For more information on using the Anthropic API, refer to the official documentation: https://docs.anthropic.com/claude/page/polyglot-superpowers

## License
This tool is released under the MIT License.

## Disclaimer
The SRT Translator tool is provided for educational and informational purposes only. The accuracy, reliability, and completeness of the translations generated by the Anthropic Claude API model used in this tool cannot be guaranteed. Users of the SRT Translator tool are solely responsible for verifying the accuracy and usefulness of the translations obtained and should not rely solely on them without further verification. The use of the SRT Translator tool is at the user's own risk, and the tool's developers and contributors shall not be liable for any damages or losses arising from its use. By using the SRT Translator tool, you agree to these terms and conditions.

If you have any concerns or suggestions about the use of this project, please contact us through the issues section.
