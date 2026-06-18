
## How it works
The chatbot uses a simple loop to read user input, normalizes it (lowercase + strip), and matches it against a small set of predefined phrases (`hello`, `how are you`, `what is your name`, `thank you`, `bye`). If the input doesn't match any rule, it replies with a default "I don't understand" message.

## Extending the bot
- Add more `elif` branches in `task1.py` for new phrases.
- Replace rule-based logic with pattern matching (regular expressions) for more flexible input handling.
- Move responses into a dictionary or separate data file for easier maintenance.
- Integrate an NLP library (e.g., NLTK, spaCy) if you want fuzzy matching or intent classification.

## Contributing
Contributions, suggestions, and improvements are welcome. Please open an issue or submit a pull request.

## License
You can add a license of your choice (e.g., MIT). If you want, I can add a LICENSE file.

## Contact
For questions or help, open an issue on the repository.


I've generated the README content above. If you'd like, I can add this README.md file to the repository for you—tell me to proceed and I'll commit it.
