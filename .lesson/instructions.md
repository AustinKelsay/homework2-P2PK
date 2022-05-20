# Instructions  

Make a P2PK transaction on testnet that locks to your pubkey, then spend back out of that P2PK script to yourself.

  ## Steps
  1. You have to build this TX by hand, bitcoin-cli won't build out P2PKs for you. This is NOT a P2SH of a P2PK, you are creating a P2PK. You can go look at the first transaction Satoshi ever did on Bitcoin sending coins to Hal Finney for an example.
  2. Start with the legacy tx_skeleton.txt file and fill in the fields as required
  3. Send some coins locking to the above script.

## Fill in the following questions about your P2PK Transaction

1. PARSED Raw Unsigned Transaction in Hex 
(Separate the fields like Nifty does in class. e.g. )

Version: 01000000

Input Count: ...

etc.

2. BLOB Raw Unsigned Transaction in Hex
(Don't separate the fields, just post the whole TX hex string)

3. PARSED Raw SIGNED Transaction in Hex 
(Separate the fields like Nifty does in class. e.g. )

Version: 01000000
Input Count: ...
etc.

4. BLOB Raw SIGNED Transaction in Hex
(Don't separate the fields, just post the whole TX hex string)

5. TXID of transaction spending to the P2PK Script above: