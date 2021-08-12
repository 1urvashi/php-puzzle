# PHP-Puzzle
A system supports StrangeID strings, if the string has a "Binary Address Authenticator Bytes", commonly called the "BAAB".  A BAAB is any four-character sequence, which consists of a pair of
two different characters followed by the reverse of that pair, such as "pqqp", "xzzx", "xoox","adda",
etc. However, a supported StrangeID also must NOT have a BAAB within any [square bracket]
sequences. There can be many [square bracket] sequences in one StrangeID.

# Output
The output of your program, that is the total number (integer) of supported StrangeIDs.
