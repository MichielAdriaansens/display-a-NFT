# !!DISPLAY A NFT!!
the goal is to showcase one single NFT on a webpage, with just the bare bones requirements.
For this exersice i kept the usage of libaries minimal.
No react, no server side stuff. This should serve as a quick reminder or a tutorial for people just starting out perhaps.

Can you get the page to show another NFT? Display some attributes perhaps?
This is a nice starting point. :3

# Summary
The page connects to a node wich allows interaction with a blockchain and NFT smartcontract.
From the smartcontract a link (URI) gets retrieved where the NFT's metadata (image/attributes/name etc) is stored.
And finally the retrieved metadata gets used to be displayed on the page. 

# Steps
1. set up the HTML page
2. choose a cool NFT
3. connect to the network where the NFT is deployed at.
4. getconnect with the the NFT contract (Get ABI if necassary)
5. retrieve the Metadata (image, nft info etc)
6. display the data on the web page


