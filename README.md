# transcriber

This project is a command-line tool that takes in a audio or video and transcribe it into text. 

## Implementation

Videos will firstly be extracted to be audios.

[Whisper AI](https://github.com/openai/whisper) is required for the transciption extraction.

## Usage

Currently, I meant to support csv, txt as output format. 
csv should keep the (timestamp, text) entry.
text is pure text, with each sentence as a separate line. 

```bash
transcriber --input <file-name.mp3>
    --output <file-name.txt>
    --format 
```
