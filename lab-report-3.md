> # Part 1

1. The failure-inducing input for the buggy program
   ```
   @Test
   public void testReversed2(){
     int[] input2 = {1,3,5};
     assertArrayEquals(new int[]{5,3,1}, ArrayExamples.reversed(input2));
   }
   ```
3. The input that doesn't induce a failure
   ```
   @Test 
	public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
   }
   ```
4. The symptom
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/3039d099-c581-4b81-ae6f-d4cb8d51ffb0)
5. ```
   


> # Part 2

## `grep`
1. To search for a pattern recursively in a directory and its subdirectories

```
$ grep -r "base pair" technical/plos
```
Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/608f1475-e79a-4a94-bc8a-1525b1fcc37c)

The `grep -r` command is searching through the directory of `technical/plos` to look for the pattern "base pair" to see which files contain it. This command is useful because it can help someone easily find all the files that have the pattern the person is looking for, instead of having to take extensive measures.

```
$ grep -r "conventional medicine" technical/biomed
```
Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/636ef59f-0632-4734-8d44-8fc6f447f358)

The `grep -r` command is searching through the directory of `technical/biomed` to look for the pattern "conventional medicine" to see which files contain it. This command is useful because it can locate the files that have the specific pattern the individual is looking for fast.

---

2. To search for lines in a file that do not contain the pattern

```
$ grep -v "and" technical/plos/pmed.0020191.txt
```
Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/19a4d98b-c8ad-44f3-b3ac-13c892569153)

The `grep -v` command is searching a file for lines that do not contain the pattern the user is searching for, in this case it is the word "and". This is useful for when you want to filter out a certain word.

```
$ grep -v "a" technical/biomed/1471-2490-3-2.txt
```
Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/cd2ff86f-04a6-4b9d-b35e-7bb354c1cd21)

The `grep -v` command is searching through the file `technical/biomed/1471-2490-3-2.txt` for lines that contain the letter "a". This is useful because it could help people focus on the lines in the text that are more suitable for their conduct.

---

3. To search for a specific pattern in the lines of a file

```
$ grep "E. coli" technical/biomed/1471-2334-3-13.txt
```
Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/d5d10af9-0689-4587-8181-ebd90edb8e60)

The command `grep` searches for a specific pattern in the lines of a certain file, in this case "E. coli" in `technical/biomed/1471-2334-3-13.txt`. This command is extremely useful when trying to find information with that specific pattern to help specify only necessary details.

```
$ grep "disorder" technical/plos/pmed.0010061.txt
```

Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/6a64f7c7-ae30-4033-a87c-37411c034b64)

In this case, `grep` is searching for the word "disorder" in `technical/plos/pmed.0010061.txt`. This command is useful because it allows the individual to gather all the information they need regarding the pattern they are searching for. 

---

4. To search for the amount of times a pattern occurs in the lines of a file

```
$ grep -c "trial" technical/plos/pmed.0010046.txt
```
Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/9df555f3-2635-454d-a4e6-80643d2b1fd5)

In the image, `grep -c` is allowing the idividual to see how many times the word "trial" appears in the file. This command is useful for when you want to see the amount of times a specific pattern appears, without having to write difficult code.

```
$ grep -c "the" technical/biomed/1475-2875-1-5.txt
```

Output:

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/ebb9b8e8-0ebb-4e90-8574-eecfe3f7e259)

The command `grep -c` is searching for the amount of times the word "the" is in the file `technical/biomed/1475-2875-1-5.txt`. This command is useful when you want to know the amount of times a certain string appears in a file. 

---

## Works Cited
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/c0cb6435-66e5-4322-81ac-93c29bcf6f66)
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/051152d3-f82d-45aa-8a79-354feda73283)
