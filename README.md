# HoneyFileGenerator (AI powered)
This project generates honeyfiles (Decoy documents designed to detect intruders when accessed). These documents are automatically created to look enticing and believable, making them useful for deception-based security monitoring.

The generator leverages an AI model to create realistic filenames and document bodies, mixing ordinary-looking files with special JUICY files (containing fake sensitive data such as credentials, API keys, or payroll passwords). The goal is to create a set of files that attackers may target, which can then be monitored for unauthorized access.

# Features
- 🔍 Directory scanning: Extracts topics and keywords from existing files in your Documents folder.
- 📝 AI-powered text generation: Creates technical, how-to style document bodies.
- 📂 Realistic filenames: AI generates filenames with dates, extensions, and internal-style naming conventions.
- 🍯 Juicy files: With a configurable probability, generates decoy files containing fake credentials or secrets.
-📑 Multiple formats: Outputs .txt, .csv, or .docx files.
- 🔐 Fake passwords: Uses secure random password generation for authenticity.

# Results
Rather disapointing.<br>
There is still a LOT of work to make the generated data believable.<br>
The "Juicy" file generator was created without AI.<br>

<img width="657" height="377" alt="image" src="https://github.com/user-attachments/assets/bac21e61-d869-433b-9e8a-7ddd29278218" />
