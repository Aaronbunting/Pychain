# Pychain

# PyChain Ledger Overview
PyChain Ledger delivers a streamlined version of blockchain functionality, developed primarily using Python. This project integrates a proof-of-work technique, and employs the Streamlit framework to craft an interactive user-facing platform for blockchain-related tasks.

## Notable Features

* Transaction Documentation: PyChain offers the capability to log monetary exchanges, detailing sender, recipient, and transaction values.
* Mining Capability: PyChain's blocks are forged via an elementary proof-of-work method. The algorithm's difficulty setting can be tweaked within the user dashboard.
* Blockchain Assurance: To guarantee the soundness of its blockchain, PyChain embeds a verification system.
* Interactive Dashboard: With Streamlit at its core, PyChain presents a dynamic dashboard allowing users to view the blockchain's state and initiate transactions.

## Getting Started

Ensure your machine runs Python 3.6 or a newer version.

To get the project:

C1lone the repository:
bash
Copy code

```
git clone "git@github.com:aaronbunting/Pychain.git"
```

Set up the necessary Python modules:
Copy code
pip install streamlit pandas
How to Use

Transition to the project's directory via the command line:
bash
Copy code
cd pychain
Initiate the Streamlit tool:
arduino
Copy code
streamlit run pychain.py
Upon launch in your browser, input transaction details such as sender, recipient, and transaction value, then hit "Add Block."

You can analyze the blockchain by picking a block using the "Block Inspector" menu. The details of the chosen block will be showcased.

For a thorough blockchain check, press the "Validate Chain" option.

Visual Aids

Below are some visual previews of the Streamlit interface:

![Block Inspector](https://github.com/Aaronbunting/Pychain/assets/128101698/9f923369-3e44-4742-82e3-7a33f06d7ad2)


![Pychain Block Transaction](https://github.com/Aaronbunting/Pychain/assets/128101698/8ba7b886-8176-4c05-a7fe-8481a5e8260f)



![Pychain Ledger Screenshot](https://github.com/Aaronbunting/Pychain/assets/128101698/5e4a550e-53b3-4590-9882-ba36f6514f7f)
