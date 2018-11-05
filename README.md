# Project Euler solutions

Encrypted with gpg 

1) for practice with gpg 
2) so I'm not breaking the Euler TOS on my public github

Happy to chat euler!

## gpg instructions so I remember

1. Setup: add my gpg key to the keyring
2. `git pull` 
3. Decrypt: `gpg -d py/18.py.gpg > py/18.py`
4. Encrypt: `gpg -r [recipient email] -e py/18.py`
5. `git commit -Am "added encrypted solutions" && git push`

`.py` files are safely ignored from the watchful eyes of git, so no need to worry about commiting them accidentally

