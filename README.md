Advanced Encryption Standard is implemented as a group project of the Information Security course.

Contributors: [Sevde Sarıkaya](https://github.com/schroscatt), [Gozde Unver](https://github.com/GozdeUnver), [Ahmet Necip Gorgulu](https://github.com/ahmetnecipg)

See the [documentation](https://github.com/schroscatt/Advanced-Encryption-Standard-Implementation/blob/master/cmpe%20494%20report.pdf) for detailed information.

# How to run the code
You should have an inptu and a key file. An example input file is present here with the name "inputFile" and key file is "keyFile". 
In the project directory, type these commands on the terminal:<br>
make<br>
java AES e \<keyFile\> \<inputFile\> // For encryption<br>
java AES d \<keyFile\> \<inputFile\> // For decryption
