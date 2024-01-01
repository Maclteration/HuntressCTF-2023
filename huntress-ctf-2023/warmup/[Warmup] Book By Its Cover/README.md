<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Book By Its Cover**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @JohnHammond

Difficulty: <font color=yellow>Warmup</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/warmup/%5BWarmup%5D%20Book%20By%20Its%20Cover/book.zip)

# Description

They say you aren't supposed to judge a book by its cover, but this is one of my favorites!

<br>

## Flag

`flag{f8d32a346745a6c4bf4e9504ba5308f0}`

# Solution

1. Using `file` command on book.rar will output

    ``` shell
    book.rar: PNG image data, 800 x 200, 8-bit/color RGB, non-interlaced
    ```

2. Change book.rar to book.png
3. Open book.png