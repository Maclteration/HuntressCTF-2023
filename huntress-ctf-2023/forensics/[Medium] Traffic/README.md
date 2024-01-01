<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Traffic**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @JohnHammond

Difficulty: <font color=yellow>Medium</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/forensics/%5BMedium%5D%20Traffic/traffic.7z)

# Description

We saw some communication to a sketchy site... here's an export of the network traffic. Can you track it down?

Some tools like `rita` or `zeek` might help dig through all of this data!

## Flag

`flag{8626fe7dcd8d412a80d0b3f0e36afd4a}`

# Solution

1. Unzip the challenge and move all log files into a new folder

2. Use `gzip -d *` to unzip all log files

3. As per the description, there's a `sketchy` site

4. Use `cat * | grep sketchy` to find the site

5. Browse the website or use `curl -L` to follow all website redirects

