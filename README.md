# OSO_hack

This repository contains the assets and research for the OSO hackathon project.

## Gist of the Project

The project aims to create a system for DJs to receive non-pecuniary "tokens of love" during their live sets. This involves using `.eth` subdomains, QR codes, and a Raspberry Pi with an e-ink display to show the gifts. The team is also exploring the concept of using the HTTP 402 error for non-monetary "payments" and "joyforking" the Liquity V2 protocol to handle these gift-based transactions.

## Command Strings

Here are the 5 command strings for the sub-Minimum-Viable-Robot setup:

1.  `rsync -av --delete Desktop/OSO/ bestape@10.213.5.207:~/OSO/`
2.  `ssh 10.213.5.207`
3.  `screen or screen -r`
4.  `source ~/.virtualenvs/pimoroni/bin/activate`
5.  `(while true; do for img in OSO/*.png; do python3 OSO/image.py --file "$img"; sleep 60; done; done) &`
