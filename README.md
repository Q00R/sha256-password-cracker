# sha256-password-cracker

This is a simple password cracker that uses a dictionary attack to crack a password that has been hashed using the SHA256 algorithm. The program takes in a password hash as input and outputs the password if it is found in the infamous *rockyou.txt password wordlist. The program is written in Rust.

## Usage

To run the program, you must have Rust installed. You can install Rust [here](https://www.rust-lang.org/tools/install).

get your password hash.The password hash must be a SHA256 hash and lowercase. You can get a SHA256 hash of a password [here](https://passwordsgenerator.net/sha256-hash-generator/).

Once you have your password hash and [rockyou.txt](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt), put rockyou.txt in src folder. then run the following command in the terminal:

```bash
cargo run <password hash>
```

