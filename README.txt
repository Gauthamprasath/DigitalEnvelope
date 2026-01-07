A Java Swing–based Digital Envelope system (server + client) that encrypts plaintext using an RSA-style asymmetric key process and transmits ciphertext over TCP sockets with file-backed transfer.
Implemented a simple key-wrapping/confusion mechanism (combining RSA-derived private key with a user-supplied key), robust parsing/validation and end-to-end decryption logic to demonstrate confidential message exchange and basic session/key verification.


Usage:
Open this DigitalEnvelope folder as project.

Then navigate to src-> digitalenvelope

Then run serverDE.java ---------> (Give Inputs)

Then run client.java -----------> (Give Inputs) 

----------------------------------------------------------------------------
Note:

In order for the file handling to work on the respective system, mention the paths in the code of serverDE and clientDE.
