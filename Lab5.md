# Lab Report 5
## Part 1- Debugging Scenario
1. Debugging Post
- The enviroment that I am using is VSCode in my Windows laptop
- When I was running the code in the terminal, I saw that all three tests ran, but two out of the three failed. The first test that failed noted that the index was out of bounds, while the other test expected another number instead of the number that I expected. To be honest, I expected all of my tests to pass, since I double checked all my codes to make sure that there's no typo or what I wrote is what the method is supposed to do.
![Image](Failmethod3.png)
- Well for starters, here is what I was running from the terminal which is only the file of the code, the test cases, and that bash script. The three images that I am going to show are ordered based on what I said from the previous sentence.
![Image](Codefile.png)
Before I go on to the next image, note that I did not run the whole code from `LectureExamples.java`, since my test only cared about the `EvensExample` meaning that the test cases only compiled from that class.
![Image](Testcases.png)
![Image](Script.png)
I decided to show all the images just in case if they're important, but I know that the error or bug has to come from the code I wrote in `class EvensExample`. However, I don't know what's wrong with it since I know that's how you are supposed to go through the iteration and add up those elements together. I don't beleive that I did the count wrong, since I checked the iterator number for each element just by hovering my mouse. I know have done something like this in 8B, but I swear that I don't see anything wrong with the code, unless I must've forgotten to add an extra line of code or change some of the words from that class.
2. TA response
Hi Karim, based on what you said and also looking at those images, my best suggestions are:
- Get a piece of paper to rewrite your test cases. In then, count each element starting at 0 till you reach the end. In then really reread what you wrote for your code, since I believe that you have a misunderstanding with that concept or you might have just miscounted.
- Just remember that you already start off at index 0 bsed on what was written in that for loop condition. Also, check what exactly is going on in the condition and how it affects your method.
- If you want as a last resort, you can try to find something simialr to what you did in 8B and just compare that code with what you
3.Screeshot and explanation of working terminal:
![Image](Work.png)
I figured that bug occured in line 23 since there was no need to add anything, since this method is only asking for the even indexes.

## Part 2- Reflection
One of the best things that I learned from this course was vim.
