# Lyric Generator
Lyric Generator
This is a web-based application designed to help users generate lyrics based on keywords or ideas they provide.

Features:

Keyword Input: Users can enter keywords or ideas, separated by commas, pauses, or spaces.
Language Selection: The generator supports three languages:
Chinese (中文)
English (English)
Japanese (日本語)
Lyric Length Selection: Users can choose the desired length of the generated lyrics:
Short (短)
Medium (中)
Long (长)
Lyric Generation: Clicking the "生成歌词" (Generate Lyrics) button processes the input and selections to produce lyrics in the "生成的歌词" (Generated Lyrics) text area.
Clear Lyrics: The "清空歌词" (Clear Lyrics) button clears the output text area.
Copy Lyrics: The "复制歌词" (Copy Lyrics) button copies the generated lyrics to the user's clipboard.
How it Works:

The application uses predefined lyric template snippets for each supported language. When a user inputs keywords and selects a language and length, the tool splits the keywords and then randomly selects lines from the appropriate language template lists (verse, chorus, bridge, outro) based on the chosen length. For the Chinese language, the generated lyrics may incorporate the user's keywords into the templates where specified. The selected lines are then joined together to form the complete generated lyric.

The user interface is built using Tailwind CSS for styling. The core logic for generating, clearing, and copying lyrics is implemented in JavaScript.

This tool appears to be a simple yet interactive way for users to get creative inspiration or generate quick lyric drafts based on their initial ideas.
