<img src="https://i.imgur.com/SPDalOx.png" style="margin-left: 20px; zoom: 80%;" align=left />        <font size="10">**Dialtone**</font>

November 1<sup>st</sup> 2023

Prepared By: Capyhax

Challenge Author(s): @JohnHammond

Difficulty: <font color=yellow>Warmup</font>

Download: [Challenge](https://github.com/Maclteration/Huntress-CTF-2023/raw/main/huntress-ctf-2023/warmup/%5BWarmup%5D%20Dialtone/dialtone.zip)

# Description

Well would you listen to those notes, that must be some long phone number or something!

<br>

## Flag

`flag{6c733ef09bc4f2a4313ff63087e25d67}`

# Solution

1. Input wav file in dtmf decoder

- https://dtmf.netlify.app/

        Decoded String: 13040004482820197714705083053746380382743933853520408575731743622366387462228661894777288573

2. long to bytes converter

## Solver
```python
from Crypto.Util.number import long_to_bytes

data = int(input("Input long integer: "))

bytes_data = long_to_bytes(data)

print(bytes_data)
```