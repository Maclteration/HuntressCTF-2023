<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Rock, Paper, Psychic**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @HuskyHacks

Difficulty: <font color=yellow>Medium</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/miscellaneous/%5BMedium%5D%20Rock,%20Paper,%20Psychic/rock_paper_psychic.7z)

# Description

Wanna play a game of rock, paper, scissors against a computer that can read your mind? Sounds fun, right?

**NOTE:** this challenge binary is not malicious, but Windows Defender will likely flag it as malicious anyway. Please don't open it anywhere that you don't want a Defender alert triggering.

## Flag

`flag{35bed450ed9ac9fcb3f5f8d547873be9}`

# Solution

1. Open cutter and input the executable file

2. Run and understand what the code does

3. Replace computerWins to playerWins by changing the instructions

    a. replace `call 0x4169f0` to `call 0x4169d0`

4. Save and rerun the executable to get the flag

