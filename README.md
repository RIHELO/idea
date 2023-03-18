Overview:
 https://en.wikipedia.org/wiki/International_Data_Encryption_Algorithm
According to wikipedia:
"International Data Encryption Algorithm (IDEA)
  The last patents expired in 2012, and IDEA is now patent-free and thus completely free for all uses."
Compile:
  ./compile.sh
Run:
 time ./target/release/idea_rust e key text output.txt
 time ./target/release/idea_rust d key output.txt decrypted
 base64 --decode decrypt

Not for industrial or production use.
This is just a PoC.

