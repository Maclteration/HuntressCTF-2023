<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Where Am I?**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @proslasher

Difficulty: <font color=yellow>Medium</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/osint/%5BMedium%5D%20Where%20Am%20I/PXL_20230922_231845140_2.zip)

# Description

Your friend thought using a JPG was a great way to remember how to login to their private server. Can you find the flag?

<br>

## Flag

`flag{b11a3f0ef4bc170ba9409c077355bba2)`

# Solution

1. Use exiftool to see the metadata
2. Go to image description section
3. Decode the text/string using base64