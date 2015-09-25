# caesar


This is an implementation of the Caesar Shift Cipher. In this algorithm, a rotation is performed on the letters of the Plaintext.
It isn't the strongest of algorithms, and hence isn't exactly trust worthy.
As a result the Cipher can be broken easily by:
1) Brute Force (Given the limation of just 26 keys)
2) Frequency Analysis: The frequency of each letter is noted. The one with the max appearance is mapped to the letter 'e'. This is possible only if the plaintext is in English, and is sufficently long.
