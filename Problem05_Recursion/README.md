## Its Confidential

### [Problem Statement](https://www.hackerearth.com/practice/basic-programming/recursion/recursion-and-backtracking/practice-problems/algorithm/its-confidential-f006e2c4/)

Abhi is a spy. Its quite natural for him to go on a secret mission. Once You and Abhi were in the same secret mission, when Abhi felt an urgent need to communicate with Dr. Sabitabatra, who appointed both of you for this mission. The only way to communicate with him was by sending letters. As both of you were on a secret mission, Abhi will write the letter with some encrypted words which Dr. Sabitabatra was well aware of . As per the encryption is concerned, the encrypted word will start with the middle character of the string and will be formed henceforth with the middle characters of the left and right substrings (of the middle character of the word) and so on. Take a look at the explanation of the sample test case for better comprehension. As the letter was going to be quite long, Abhi wants your help to encrypt some critical words for him so that he can quickly finish the letter and sent it to Dr. Sabitabatra.

### Input

The first line contains an integer T denoting the number of TEST CASES. Each TEST CASE consists of 2 lines. The first line contains an integer N denoting the length of the word that needs to be encrypted. The second line contains the word that needs to be encrypted.

### Output

N lines where each line will contain the encrypted words 

### Constraints

1 <= T <= 10

1 <= Length of the string <= 10000

### Sample

#### Input

2

3

abc

4

abcd

#### Sample Output

bac

bacd

#### Explanation

In Test Case 2: The word was "abcd"

Middle character of this word is 'b'

Left Substring of 'b' is "a"

Right Substring of 'b' is "cd"

Middle Character of Left Substring of 'b' is 'a'

Middle Character of Right Substring of 'b' is 'c'

There are no other Left Substring for the 'c' in the right substring of 'b'

Right Substring of 'c' is "d"

Middle Character of Right Substring of 'c' is 'd'

There is no other Left or Right Substring of 'd', so we stop here and arrange the middle characters as we have obtained :

"bacd"

### Misc constraints

- **Time Limit**:	1.0 sec(s) for each input file.
- **Memory Limit**:	256 MB
- **Source Limit**:	1024 KB
