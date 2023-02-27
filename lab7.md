# Lab Report 4

CSE15L_WI23 | Joy Lee (A17608409) | 27 February 2023<br />

---

###### This page explains step 4 to step 9 on Challenge Tasks.
###### Each step includes screenshots with brief explanation.

---

### Step 4: Log into ieng6
![Image](step4.png)
* Type `ssh cs15lwi23atu@ieng6.ucsd.edu` to log into ieng6. Press `<enter>`
* As I generated SSH keys for ieng6, I do not need to type the password.<br />

### Step 5: Clone your fork of the repository from your Github account
![Image](step5.png)
* Type `git clone` and then copy paste my fork of the repository `git@github.com:joy1ee/lab7.git`
* Press `<enter>`
  
### Step 6: Run the tests, demonstrating that they fail
![Image](step6.png)
* Using `<ctrl>+r` to search __javac__ in history, I do not need to type long compiler command.
* As above, use `<ctrl>+r` to search __java__ in history to run the file.
* Key pressed: `<ctrl>+r and then <enter>`
  
### Step 7: Edit the code file to fix the failing test
* To fix the failing test, type `nano ListExamples.java` in terminal.
* As you type `nano filename.java`, you can edit java file using nano in terminal.

![Image](step7.png)

* Use the "Down" key 42 times, the "Right" key 12 times and then "Backspace" 1 time
* Key pressed: `<down> 42 times, <right> 12times, and <backspace>`
* Now we are in Line 43.
* Here is the part of the code; Line 41 to Line 44.
>```ruby
> while(index2 < list2.size()) {
>     result.add(list2.get(index2));
>     index1 += 1;
>   }
> ```
* In Line 43, put `index2 += 1;` instead of `index1 += 1;`
* To save, use `<ctrl>+o` and then press `<enter>`
* Key pressed: `<ctrl>+o and <enter>`
* To exit nano, use `<ctrl>+x`
* Key pressed: `<ctrl>+x`
 
  
### Step 8: Run the tests, demonstrating that they now succeed
![Image](step8.png)
* To compile and run the file, use the "up" arrows 3 times to go through the history of commands I have executed.
* Key pressed: `<up><up><up><enter>`

### Step 9: Commit and push the resulting change to your Github account
![Image](step9.png)
* Type `git add *` to add my changes
* Type `git commit -m "Updated"` to commit the changes
  
![Image](step10.png)
* Type `git push` to push my changes to my Github repository.
  
![Image](step11.png)
* They all successfully updated in the Github repository.
