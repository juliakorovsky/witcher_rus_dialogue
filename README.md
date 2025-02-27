# witcher_rus_dialogue
Dialogue text from the main Witcher 3 game (Russian)

`witcher_3_dialogue.csv` contains dialogue lines in Russian from the Witcher 3 game.
The w3strings files were extracted from the game and converted to csv with `w3strings.exe`. They were then concatenated to one file.
column `"wav_id"` was also added to match WAV files extracted from the game.

All columns:   
`id` - original w3strings id for a voice line    
`hex` - original w3strings hex key    
`text` - text for a voice line, extracted from w3strings files    
`wav_id` - filename of wav-file containing voice line   

This dataset was created to aid in TTS and ASR tasks.   
You can pair this with Huggingface Witcher 3 dataset: https://huggingface.co/Rootreck/so-vits-svc-4.0-ru-The_Witcher_3_Wild_Hunt
