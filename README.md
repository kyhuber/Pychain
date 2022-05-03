# Pychain

A blockchain-based ledger system accessible through a user-friendly web interface.

Initially, the PyChain app creates a class for Records, whose attributes include Sender, Receiver, and Amount. The user inputs values for each of these attributes through the Streamlit UI. 

![Enter Transaction Details](https://user-images.githubusercontent.com/69730757/166508926-72da8504-2457-426d-a6b6-44d557031587.png)

The PyChain app uses a proof of work consensus protocol to validate blocks on the chain. Next, the app creates a Block class with attributes for Creator ID, Previous Hash, Timestamp, and Nonce. Each entry in the blockchain ledger will include information for all of these attributes.

![PyChain Ledger](https://user-images.githubusercontent.com/69730757/166509806-b2c65c47-18bd-4935-999c-3677fc7b54a4.png)

As part of the proof of work protocol, the app allows the user to select their desired level of block difficulty. The scale ranges from 1 to 5, representing the number of zeroes required at the beginning of each hash to validate the block. When the difficulty increases, PyChain takes longer to validate the block and returns larger nonce values.

![Block Difficulty](https://user-images.githubusercontent.com/69730757/166511165-cc07560c-24fc-4752-ab88-454b916692d8.png)

The PyChain app also features a Block Inspector in the web interface. This drop down menu allows the user to select a specific block and view associated attributes. Just below the ledger, the user can click a button to Validate Chain. This process analyzes all of the blocks on the chain to ensure all of them are linked to the previous block's hash.


---

## Technologies

The PyChain app is written in Python 3.10.1 using Microsoft Visual Studio. It is compatible with Mac and PC OS.
The tool uses the Pandas libraries to manage data.
The web interface is rendered using Streamlit.
Hashing and encryption in the ledger come from the Python hashlib module.

---

## Installation Guide

This app can be run in any browser using Streamlit.

---

## Contributors

The PyChain app was written by Kyle Huber in May 2022.

---

# PyChain
