# encrytion-and-decrytion-of-message
This is a simple encryption and decryption script written in Python. It uses a shuffled character mapping to encrypt and decrypt text.

Features

Encrypts plain text into cipher text using a randomized key mapping.

Decrypts the cipher text back into the original plain text.

Uses Python's random.shuffle() to create a unique key for each execution.

How It Works

A character set is created, containing:

Space

Punctuation (string.punctuation)

Digits (string.digits)

Letters (string.ascii_letters)

A shuffled copy of this character set is used as the encryption key.

Each character in the plain text is replaced with the corresponding character from the shuffled key.

The decryption process reverses the mapping to retrieve the original text.
