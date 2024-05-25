# Dictionary-using-BST-FH
Introducing a "GUI" based "Dictionary Project" entirely coded in C++ using BST and file handling.

Features:
1) Load Dictionary: Upon execution, the program loads a .txt file and inserts its contents into a BST based on the ASCII weight of each alphabet present in the word.

Duplication resolution: To address duplication, the program calculates the weight of each word by summing up the squares of each alphabet's ASCII value.

2) Case Sensitive: All words are stored in lowercase form in the Dictionary.txt file. Whether the user enters a word in uppercase, lowercase, or a mix of both, the program processes it as a lowercase word during insertion and search operations.

3) Search: The search function operates within the BST and handles three cases: 
   - If the word is found
   - If the word is not found, it suggests words with a high hitrate (if 50% of the alphabets of the words match)
   - If the word is not found and no suggestions are available

4) Add to Dictionary: After suggesting a word, the program prompts the user to confirm if it should be added to the dictionary. Upon confirmation, the word is added to the Dictionary and BST simultaneously.
