# [Intro to password hashing](https://auth0.com/blog/hashing-passwords-one-way-road-to-security/)

1. Define the term “hashing”.

- By dictionary definition, hashing refers to "chopping something into small pieces" to make it look like a "confused mess". That definition closely applies to what hashing represents in computing.

2. Explain to a non-technical friend what a hash function does to a password.

- Hashing a password is like interpreting the password in a language only the computer knows.

[bcrypt overview](https://medium.com/@danboterhoven/why-you-should-use-bcrypt-to-hash-passwords-af330100b861)

1. What does it mean to ‘salt’ a password?

- It adds a very long string of bytes to the password. So even though a hacker might gain access to one-way hashed passwords, they should not be able to guess the ‘salt’ string. 

2. What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

- Your source code


[jBCrypt (the paragraphs and code example at the top of the page)](https://www.mindrot.org/projects/jBCrypt/)

1. How does the Blowfish block cipher handle the increased computation speed of new computers?

- The computation cost of the algorithm is parametised, so it can be increased as computers get faster. The intent is to make a compromise of a password database less likely to result in an attacker gaining knowledge of the plaintext passwords (e.g. using John the Ripper).

2. What are the issue with the two most common password hashes for Java (“Java password hash” and “Java password encryption”)?

- There seems to be a lack of good password hashes for Java - the top two hits in Google (as of 2006/05/24) for "Java password hash" and "Java password encryption" both offer terrible advice: one uses an unsalted hash which allows reverse dictionary lookup of passwords and the other recommends reversible encryption, which is rarely needed and should only be used as a last resort.

