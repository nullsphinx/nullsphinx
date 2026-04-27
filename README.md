# nullsphinx

Security Analyst | Cyber Threat Intel

## Projects

* **ctx** – Threat intelligence platform
* **balconythoughts** – Personal website
* **chronovos** – Geographic historical timeline app
* **book-dependency-tree** – Recursively view a book’s sources
* **future-finances** – Personal finance calculator

## Contact

- **Email:** hermyx@proton.me 
- **Encrypted email (PGP)**. Requires [GnuPG](https://gnupg.org/) installed.
  
  - **Install GnuPG on macOS:**
    ```bash
    brew install gnupg
    ```
  - **Fingerprint:**  
    ```
    5325 D31F C34D CFC7 8BAD  E9FA 353F 84B3 905D A9F1
    ```  
  - **Import my public key:**
    ```bash
    curl -L -o nullsphinx-pubkey.asc \
      https://gist.githubusercontent.com/nullsphinx/ad0ddba3969bf7f6b41bc9b48a843e01/raw/pubkey.asc

    gpg --import nullsphinx-pubkey.asc
    gpg --fingerprint hermyx@proton.me
    ```
    Confirm the fingerprint shown by `gpg --fingerprint` matches the fingerprint above.

  - **Encrypt a message for me:**
    ```bash
    gpg --armor --encrypt --trust-model always \
      --recipient hermyx@proton.me \
      --output message.txt.asc message.txt
    ```
    Replace `message.txt` with the file you want to encrypt. Send me `message.txt.asc`.
