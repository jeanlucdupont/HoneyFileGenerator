# HoneyFileGenerator (AI powered and Markov variant) (PoC)
This project generates honeyfiles (Decoy documents designed to detect intruders when accessed). These documents are automatically created to look enticing and believable, making them useful for deception-based security monitoring.


## AI powered ##
The generator leverages an AI model to create realistic filenames and document bodies, mixing ordinary-looking files with special JUICY files (containing fake sensitive data such as credentials, API keys, or payroll passwords). The goal is to create a set of files that attackers may target, which can then be monitored for unauthorized access.

<img width="247" height="222" alt="image" src="https://github.com/user-attachments/assets/4c8afa25-a46b-475d-af69-534fdc735399" />


### Features ###
- 🔍 Directory scanning: Extracts topics and keywords from existing files in your Documents folder.
- 📝 AI-powered text generation: Creates technical, how-to style document bodies.
- 📂 Realistic filenames: AI generates filenames with dates, extensions, and internal-style naming conventions.
- 🍯 Juicy files: With a configurable probability, generates decoy files containing fake credentials or secrets.
-📑 Multiple formats: Outputs .txt, .csv, or .docx files.
- 🔐 Fake passwords: Uses secure random password generation for authenticity.

### Results ###
Rather **disapointing**.<br>
There is still a LOT of work to make the generated data believable.<br>
The "Juicy" file generator was created without AI.<br>
If you’ve experimented with deception tech or have ideas for making decoys more credible, I’d love to hear them.<br>

<img width="656" height="378" alt="image" src="https://github.com/user-attachments/assets/bac21e61-d869-433b-9e8a-7ddd29278218" />

<hr>
<img width="616" height="429" alt="image" src="https://github.com/user-attachments/assets/e567ac96-e6ce-491d-b50e-b69da38619a3" />

<hr>

<img width="610" height="331" alt="image" src="https://github.com/user-attachments/assets/89eb4ab4-bd9d-434e-9043-e91bc2e1f047" />


### How-to ###

1. Get LLAMA.CPP: https://github.com/ggml-org/llama.cpp/releases/
2. Get LLAMA chhat GGUF: https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGUF/blob/main/llama-2-7b-chat.Q5_K_S.gguf
3. Run llama server
```
llama-server.exe -m ..\llama-2-7b-chat.Q5_K_S.gguf --host 127.0.0.1 --port 8080 --ctx-size 4096
```
4. Run python script
5. What your PC suffer at 100% CPU/GPU/RAM for a long time
6. See results in */decoy*

## Markov variant ##
This is even worse. There's no way any human would consider this as a human input. Maybe some better programming or model would help.
Also, if you could tell AI to change PII with ficticious information, you can't do that with Markov's.

<img width="232" height="164" alt="image" src="https://github.com/user-attachments/assets/72f312e6-ec78-4e07-a479-0280a2471c39" />
<hr>
Silverlining. 

1. It is extremely fast.
2. It could be used for file name generation but not for content generation.


<hr>
<img width="593" height="347" alt="image" src="https://github.com/user-attachments/assets/4d07e8dd-0c60-4586-b457-fc113b86e2d1" />

<hr>
<img width="615" height="369" alt="image" src="https://github.com/user-attachments/assets/244411f5-fda4-4592-a4f6-70d8d22aa95e" />
<hr>
<img width="603" height="329" alt="image" src="https://github.com/user-attachments/assets/daf72725-e97f-40b2-b236-24eacda1cd6d" />


