<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Babel**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @JohnHammond

Difficulty: <font color=yellow>Medium</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/miscellaneous/%5BMedium%5D%20Babel/babel.zip)

# Description

It's babel! Just a bunch of gibberish, right?

<br>

## Flag

`flag{b6cfb6656ea0ac92849a06ead582456c}`

# Solution

1. Deobfuscate and try to make a sense of the strings

2. Add the value of `string pTIxJTjYJE` as input

3. Use cyberchef `Substitute` operation

    * Plaintext: lQwSYRxgfBHqNucMsVonkpaTiteDhbXzLPyEWImKAdjZFCOvJGrU
    * Ciphertext: abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ

4. Add `From Base64` operation

5. Search "flag"

**NOTE:** You can also add `Strings` operation after `Base64` to have a more clean view