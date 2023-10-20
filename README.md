# Pico Play
Play thousands of songs on your Raspberry Pi Pico with a buzzer

CircuitPython library to play music through a buzzer, automatically replaces chords with fast arpeggios to simulate polyphony. Music can be easily taken from [Online Sequencer](https://onlinesequencer.net/).


Also supports playing music through multiple buzzers, dividing the currently playing notes across them for polyphony

<br>

### Usage with RPi Pico / Other CircuitPython Board 
1. Connect your buzzer to a ground pin and either pin 7 or 26 on your Raspberry Pi Pico.
2. Install CircuitPython on your Pico and copy the files from this repository to it.
3. Find the desired music on [Online Sequencer](https://onlinesequencer.net/), click edit, select all notes with CTRL + A, and copy them with CTRL + C.
4. Connect a wire to the designated pins:
   - For Tetris, use pins 2 and 18.
   - For Sweden, use pins 2 and 19.
   - For "Never Gonna Give You Up," use pins 2 and 20.
   - For Jingle Bells, use pins 2 and 21.
Alternatively, paste the music string in place of one of the songs you can select, and connect it to the corresponding pin. Make sure to remove the "Online Sequencer:120233:" from the start and the ";:" from the end.
<br>

### Board Compatibility
| Board | Compatible? |
|-------|-------------|
| Raspberry Pi Pico | Yes |
| Other boards | Not Tested |
<br>
