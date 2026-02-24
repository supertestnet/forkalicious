# Forkalicious
Visualize possible outcomes of a contentious BIP110 soft fork

# What is this?
This is a "fork visualizer." It helps you see what the possible outcomes might be if BIP110 continues on its path as a contentious soft fork.

# How can I try it?
Just click here: https://supertestnet.github.io/forkalicious/

# How does it work?
The website creates three characters, Alice, Bob, and Carol. Alice runs a "standard" bitcoin node that **ignores** the BIP110 soft fork. Bob runs a node that **enforces** the BIP110 soft fork. Carol runs a node that **rejects** the BIP110 soft fork. (These nodes are all simulated, not real.) Then it lets you pick how many miners enforce the rules of BIP110, from 0% to 100%. Then you can start generating blocks based on that assumption, and see how the blockchain looks on Alice's node, Bob's node, and Carol's node.

# Why did you make it?
I want to use this visualizer during [an upcoming Bitdevs in San Juan](https://www.sanjuanbitdevs.org/) to illustrate possible outcomes of the BIP110 debate.
