Overview:
 https://en.wikipedia.org/wiki/International_Data_Encryption_Algorithm
  International Data Encryption Algorithm (IDEA)
  The last patents expired in 2012, and IDEA is now patent-free and thus completely free for all uses. 
Compile:
  rustc idea.rs
Run:
 ./idea e key text output.txt 
 ./idea d key output.txt decrypt
 base64 --decode decrypt
