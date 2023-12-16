# Caesar Cipher Game

## Description
This is a simple Caesar Cipher game written in Python. It allows you to encode and decode messages using the Caesar Cipher method.

## How to Play
1. Run the game.
2. You will be prompted to choose between 'encode' to encrypt a message or 'decode' to decrypt a message.
3. Next, you will be asked to type your message.
4. Finally, you will need to type the shift number which will be used to shift the letters in your message.

## Code
The game uses a list of alphabets to shift the letters in your message. The `caesar` function takes in your message and the shift amount as parameters. It then iterates over each letter in your message, finds its position in the alphabet list, and shifts it by the shift amount to encode or decode the message.

## Example
Here's an example of how to play the game:

```python
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
3
```
The encoded text is `khoor`.
