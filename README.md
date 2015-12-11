# bruteforce_shadow_sha512
####A little python to bruteforce /etc/shadow file from a dictionary

This is a sha512 implementation of a simple crypt() bruteforcer for /etc/shadow file.
This is useful for that kind of password (Debian for istance)):

root:$6$saltsalt$encryptedpassword:16584:0:99999:7:::

It read shadow from "passwords.txt" and dictionary from "dictionary.txt"
