<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Welcome To The Park**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @Stuart Ashenbrenner

Difficulty: <font color=yellow>Medium</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/miscellaneous/%5BMedium%5D%20Welcome%20to%20The%20Park/welcomeToThePark.zip)

# Description

The creator of Jurassic Park is in hiding... amongst Mach-O files, apparently. Can you find him?

<br>

## Flag

`flag{680b736565c76941a364775f06383466}`

# Solution

1. Go to `welcome` diretory and navigate to `.hidden`
2. Use strings on `welcomeToThePark`
3. Decode from base64
4. Used cyberchef `xml beautify`
5. Find the pattern and navigate to the github link
6. Use strings on `JohnHammond.jpg`