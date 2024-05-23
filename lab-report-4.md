## Step 4:

`ssh<space>jnolasco@ieng6.ucsd.edu<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/b40e50c0-a425-4e78-8d9c-192137d79a1f)

This command allowed me to log-in to my ieng6 account in order to complete steps 5-9.

---

## Step 5:

`git<space>clone<space>https://github.com/jjmnol/lab7.git<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/e44513ac-0828-474d-b39a-7ba79aadcd6a)

Cloning the fork from my repository allowed me to access the code needed in order to perform the next steps.

---

## Step 6:
`bash test.sh`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/49c328f8-40f3-4109-ad6e-e05a3b396052)


Running the test made it so that I can see which test fails and what needs to be fixed.

---

## Step 7:

- `vim<space>ListExamplesTest.java<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/c354bf61-e054-45d6-b639-93a29c386e69)

I used the command `vim` to access the testers and ensure that the error was not located in that file.

- `:q!<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/89df5bea-00ad-4679-b528-6c9d367526cc)

The command `:q!` was utilized in order to exit the file.

- `vim<space>ListExamples.java<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/d6a60a0c-6c62-4d41-83d2-9d2c9f6fa8bb)

The command `vim` was used again to access `ListExamples.java` to locate the error in it, since it was not in the testers.

- `:44<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/d97d080e-2a30-4fa8-998f-c6353e795609)

As I was scanning for the error, I realized it was on line 44, so I used `:44` access the line.

- `i<right><right><right><right><right><right><backspace> 2 <esc>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/f29795e5-2563-4e0b-8212-4de31cc539a4)

Using `i`, I was able to insert the right code in order to fix the error, which was replacing the `1` in `index1` with `2`. I used `<esc>` to exit the insert mode and type in the next command.

- `:wq<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/ed5cb0bd-56b2-4249-a474-68f68c4d2be4)

The command `:wq` was used to save the changes made in the file, so when the tests are run again, it does not show an error.

- `<up><enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/12e213f0-fe61-416c-abe5-8279dcd1dbe1)

`<up><enter>` was used to access the first command we used which was `vim<space>ListExamplesTest.java<enter>`to access the file again to ensure that vorrect code was saved.

- `:q<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/6cdc2ea9-a8ef-4ce4-8906-8c5e439e3775)

I used `:q` to exit the file again.

---

## Step 8:
`bash test.sh`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/1a242f29-64ed-4fc2-a8c1-54970bebee6a)

I ran the tests again through `bash test.sh` to ensure that the code runs with no failure.

---

## Step 9:
- `git<space>add<space>.<enter>`
- `git<space>commit<space>-m<space>"Fixes commited"<enter>`
- `git<space>push<enter>`

![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/eecbcc23-6fd3-4d75-952a-79876837c7ed)
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/42e5c6ab-8060-41c7-bbff-fc22ac8cb6ac)


I used `git commit` and `git push` to commit and push the fixes made to the `ListExamples.java` file into my forked repository in my github account.
