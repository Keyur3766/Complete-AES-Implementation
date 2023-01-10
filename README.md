# Complete-AES-Implementation


This project aims to implement well known AES - 128-bit encryption technique. Using this project, the user can
encrypt audio, video, and text files with the help of a key provided by the user. The person can only decrypt the file or
message if he knows the encryption key. After encryption, Nobody can open or decrypt it in between. This project uses the
concept of Linear algebra concepts in a very efficient way. The message will be transformed into a matrix of 128 bits and
encrypted using matrix transformation.

<br>


Advanced Encryption Standard (AES) algorithm is one of the most sophisticated block ciphers used worldwide. The report explains crucial steps of encryption and decryption of plaintext and any other file format such as .txt, .pdf, .docx, .pptx, .xlsx, .mp4, .flv,.mp3, with example in each process along with some of the changes in the methods.

<br>

# Instruction to run the project:

**Note**:  Ensure that you will never forget the password which you set for the login. Because without it you can’t decrypt your files in the future.


•	First set the command line location as per your python project and then type the following command:


<img width="410" alt="image" src="https://user-images.githubusercontent.com/75409140/211362083-b400d2f3-43c4-41d1-9e77-6c6df0e78d6b.png">


<h2>For  Encryption process:</h2>

 •	As mentioned above you have to type the following command: 
      **“python main.py encrypt”**

<img width="401" alt="image" src="https://user-images.githubusercontent.com/75409140/211362949-2228eb43-d06a-4662-a900-e0306d227b72.png">

•	Then you have to provide your login credentials for encrypting your text or image. The sample image of the login screen is below:

<img width="237" alt="image" src="https://user-images.githubusercontent.com/75409140/211363045-8171e0e6-b643-42bb-99f2-a9c1179ca0b5.png">

•	Then you are able to see the main menu screen. Select your choice from the menu.  

<img width="181" alt="image" src="https://user-images.githubusercontent.com/75409140/211363212-1a0155d4-5439-4e24-a899-7dd85e287c06.png">

•	If you choose the first option(Encrypt text) and once the string is encrypted you have to provide the filename to store your encryption string.

<img width="451" alt="image" src="https://user-images.githubusercontent.com/75409140/211363281-0526148e-1982-4a9e-9c8b-96a177e65c82.png">


•	If you choose the second option(Encrypt image) and once the image is encrypted you don’t have to provide the filename to store your encrypted image the code will automatically generate an encrypted image file as Filename_enc.


<h2>For Decryption process: </h2>


•	As mentioned in the menu you have to type the following command: 
      **“python main.py decrypt”** 
      
 <img width="425" alt="image" src="https://user-images.githubusercontent.com/75409140/211363945-44181694-cf67-4291-9ec4-accd7f8733e6.png">

      
•	then you must the same login credentials as encryption. Otherwise, you are not able to decrypt the image.

•	Then you are able to see the main menu screen. Select your choice from the menu.

<img width="172" alt="image" src="https://user-images.githubusercontent.com/75409140/211364019-27a9e1bf-a248-4091-9f65-0d927b83e893.png">


•	If you choose the first option(Decrypt text) and then you have to provide the Filename which you want to decrypt as below.

<img width="451" alt="image" src="https://user-images.githubusercontent.com/75409140/211364092-b9c42f12-2e1f-4848-9055-314709bc423b.png">

•	If you choose the second option(Decrypt image) and then you have to provide encrypted Filename (Filename_enc).

<img width="451" alt="image" src="https://user-images.githubusercontent.com/75409140/211364220-3679f221-8e1c-4688-8952-0a7caaae8afa.png">









