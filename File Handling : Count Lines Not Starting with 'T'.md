# File Handling in Python: Count Words

## 🎯 Aim
To write a Python program that counts the number of words in a text file `story.txt`.

## 🧠 Algorithm
1. Open the file story.txt in read mode.
2. Read the entire content of the file into a variable content.
3. Split the content into individual words using the split() method.
4. Count the total number of words obtained.
5. Return this count as the output.

## 🧾 Program
def create_file(file_path, file_content):
  with open(file_path,'w') as file:
    file.write(file_content)

def count_words_in_file(file_path):
  with open (file_path,'r') as file:
    content = file.read()
    words = content.split()
    return len(words)

## Output
<img width="1378" height="222" alt="image" src="https://github.com/user-attachments/assets/b39136dc-ceda-4bb1-a3c1-227cdac1d9b4" />


## Result
Thus, To write a Python program that counts the number of words in a text file `story.txt` is verified.
