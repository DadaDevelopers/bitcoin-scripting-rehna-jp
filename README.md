# assignment-4
Bitcoin Scripting


Assignment A

Given this script:

OP_DUP OP_HASH160 <PubKeyHash> OP_EQUALVERIFY OP_CHECKSIG

Tasks:

Break down each opcode's purpose

Create a diagram showing data flow

Identify what happens if signature verification fails

Explain the security benefits of hash verification



Assignment B

Implement a Hashed Time-Lock Contract for atomic swap between Alice and Bob:

Alice can claim with secret preimage within 21 minutes

Bob gets refund after 21 minutes

Tasks:

Complete the HTLC script

Create claiming transaction script

Create refund transaction script

Test with sample hash and timeout
