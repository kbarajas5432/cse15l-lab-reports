# Lab 3- Command Research

There were so many commands for bash that I learned in this course and discovered what they do in lab. The one command that I am researching for this report is the `less` command.
Since I found this command interesting, I decided to go on [Link](https://phoenixnap.com/kb/less-command-in-linux) to look at four interesting comman line options or another way of writing `less`.
## When looking up ways on writing the less command, I saw that one of the ways was `-N`
- When using that code in files, I wrote it as, `less -N Server.java`. Writing the code this way, gave me this output: `
1. `1 // A simple web server using Java's built-in HttpServer`
2.      `2`
3.      `3 // Examples from https://dzone.com/articles/simple-http-server-in-java were useful references`
4.      `4`
5.      `5 import java.io.IOException;`
6.      `6 import java.io.OutputStream;`
7.      `7 import java.net.InetSocketAddress;`
8.      `8 import java.net.InetAddress;`
9.      `9 import java.net.URI;`
10.     `10`
11.     `11 import com.sun.net.httpserver.HttpExchange;`
12.     `12 import com.sun.net.httpserver.HttpHandler;`
13.     `13 import com.sun.net.httpserver.HttpServer;`
14.     `14`
15.     `15 interface URLHandler {`
16.     `16     String handleRequest(URI url) throws IOException;`
17.     `17 }`
18.     `18`
19.     `19 class ServerHttpHandler implements HttpHandler {`
20.     `20     URLHandler handler;`
21.     `21     ServerHttpHandler(URLHandler handler) {`
22.     `22       this.handler = handler;`
23.     `23     }`
     
- For directories from `./technical`, I wrote the code as, `less -N technical/911report/chapter-1.txt` which I got this output:
1.      `1`
2.      `2`
3.      `3`
4.      `4 "WE HAVE SOME PLANES"`
5.      `5`
6.      `6     Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions of men and women readied thems      6 elves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York City. Others       6 went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session. At the other end of       6 Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. Bush went for an early mornin`
7.      `6 g run.`
8.      `7`
9.      `8     For those heading to an airport, weather conditions could not have been better for a safe and pleasant journey. Among the travelers were`
10.      `8  Mohamed Atta and Abdul Aziz al Omari, who arrived at the airport in Portland, Maine.`
11.      `9`
12.     `10 INSIDE THE FOUR FLIGHTS`
13.     `11`
14.     `12 Boarding the Flights`
15.     `13`
16.     `14     Boston: American 11 and United 175. Atta and Omari boarded a 6:00 A.M. flight from Portland to Boston's Logan International Airport.`    
17.     `15`
18.     `16     When he checked in for his flight to Boston, Atta was selected by a computerized prescreening system known as CAPPS (Computer Assisted P`
19.     `16 assenger Prescreening System), created to identify passengers who should be subject to special security measures. Under security rules in pl     16 ace at the time, the only consequence of Atta's selection by CAPPS was that his checked bags were held off the plane until it was confirmed`
20.     `16 that he had boarded the aircraft. This did not hinder Atta's plans.`
21.     `17`
22.     `18     Atta and Omari arrived in Boston at 6:45. Seven minutes later, Atta apparently took a call from Marwan al Shehhi, a longtime colleague w`
23.     `18 ho was at another terminal at Logan Airport. They spoke for three minutes.`
24.     `19`
25.     `20     It would be their final conversation.`
26.     `21`
27.     `22     Between 6:45 and 7:40, Atta and Omari, along with Satam al Suqami, Wail al Shehri, and Waleed al Shehri, checked in and boarded American`
28.     `22  Airlines Flight 11, bound for Los Angeles. The flight was scheduled to depart at 7:45.`
29.     `23`
30.     `24     In another Logan terminal, Shehhi, joined by Fayez Banihammad, Mohand al Shehri, Ahmed al Ghamdi, and Hamza al Ghamdi, checked in for Un     24 ited Airlines Flight 175, also bound for Los Angeles. A couple of Shehhi's colleagues were obviously unused to travel; according to the Unit     24 ed ticket agent, they had trouble understanding the standard security questions, and she had to go over them slowly until they gave the rout`
31.     `24 ine, reassuring answers.`
32.     `25`
33.     `26     Their flight was scheduled to depart at 8:00.`
34.     `27`
35.     `28     The security checkpoints through which passengers, including Atta and his colleagues, gained access to the American 11 gate were operate     28 d by Globe Security under a contract with American Airlines. In a different terminal, the single checkpoint through which passengers for Uni`
36.     `28 ted 175 passed was controlled by United Airlines, which had contracted with Huntleigh USA to perform the screening.`

- The `-N` option for less, basically "shows the line numbers at the beginning of each new line" as mentioned from the website [Link](https://phoenixnap.com/kb/less-command-in-linux). I think the importance for the command is to make the count easier when reading from the bash terminal. What I mean easier is that if you were to write less without that command, you will see the lines with the text but there will be no numbers shown at the begining.
- Just note that for files, there are actually 55 lines, while directory has 731 lines. I decided to not include the whole output for both because I didn't want to write too much for the output in my report.
- Also, you will see that there are some numbers that repeat and it's because the text was too big to fit in one line of a terminal, so they just indent for a new line but with the same number. That number will just show that the test belongs with that line number. Not only that, but you will some numbers have blank spaces and this is more likely that it's going to happen for my other outputs. You may also see that some of the code isn't line up porperly, which it was lined up how the output is supposed to look in bash. These two problems that I just pointed happened because I copied the output from my terminal.

## After doing the `-N`, I used that website to look for more options which that is when I discovered an option named `-E`. 
- For the files part, I wrote it as `less -E Server.java` which I got this output:

1. `// A simple web server using Java's built-in HttpServer`
2.
3. `// Examples from https://dzone.com/articles/simple-http-server-in-java were useful references`
4.
5. `import java.io.IOException;`
6. `import java.io.OutputStream;`
7. `import java.net.InetSocketAddress;`
8. `import java.net.InetAddress;`
9. `import java.net.URI;`
10.
11. `import com.sun.net.httpserver.HttpExchange;`
12. `import com.sun.net.httpserver.HttpHandler;`
13. `import com.sun.net.httpserver.HttpServer;`
14.
15. `interface URLHandler {`
16.    `String handleRequest(URI url) throws IOException;`
17. `}`
18.
19. `class ServerHttpHandler implements HttpHandler {`
20.    `URLHandler handler;`
21.    `ServerHttpHandler(URLHandler handler) {`
22.      `this.handler = handler;`
23.   `}`

- For the directories part, I just wrote `less -E technical/911report/chapter-1.txt` which I got this output:
1. `"WE HAVE SOME PLANES"`
2.
3.    `Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions of men and women readied themselves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York City. Others went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session. At the other end of Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. Bush went for an early morning run.`
4.
5.    `For those heading to an airport, weather conditions could not have been better for a safe and pleasant journey. Among the travelers were Mohamed Atta and Abdul Aziz al Omari, who arrived at the airport in Portland, Maine.`
6.
7. `INSIDE THE FOUR FLIGHTS`
8.
9. `Boarding the Flights`
10.
11.    `Boston: American 11 and United 175. Atta and Omari boarded a 6:00 A.M. flight from Portland to Boston's Logan International Airport.`
12.
13.    `When he checked in for his flight to Boston, Atta was selected by a computerized prescreening system known as CAPPS (Computer Assisted Passenger Prescreening System), created to identify passengers who should be subject to special security measures. Under security rules in place at the time, the only consequence of Atta's selection by CAPPS was that his checked bags were held off the plane until it was confirmed that he had boarded the aircraft. This did not hinder Atta's plans.`

- At first, the two different outputs may look like nothing happened, but something did happened. By pressing the space bar, clicking enter, or using the down arrow to scroll through the whole output you will notice that once you reached the end of the output, the file immdeatly ends and you are back to your bash terminal. From there, you see that you did't type `q` to exit the file when you reached the end. What I mean is that if you ran the less command without the `-E` option, you will see the `(End)` message at the end of your file. Even though it says end, you can't exit the file without typing `q`. Unlike `-E`, there's no need to type `q` and also there was no `(End)` at the end of the file. The `(End)` is replaced with `:`.
- Based on what I said earlier and according to that same website [Link](https://phoenixnap.com/kb/less-command-in-linux), the `-E` option just "automatically exits upon reaching the end of file." I believe the importence of this option is to save the hassle and time for a coder to just quickly end the file when he or she reaches to the end without typing `q`.

## The third option that I just learned from the same website is `-p[pattern]`. 
- For files, I worte this option as `less -p[pattern] TestDocSearch.java` and here is the output:

1. `import static org.junit.Assert.*;`
2. `import org.junit.*;`
3. `import java.net.URI;`
4. `import java.net.URISyntaxException;`
5. `import java.io.IOException;`
6.
7. `public class TestDocSearch {`
8.        @Test`
9.        `public void testIndex() throws URISyntaxException, IOException {`
10.    `Handler h = new Handler("./technical/");`
11.    `URI rootPath = new URI("http://localhost/");`
12.    `assertEquals("There are 1391 total files to search.", h.handleRequest(rootPath));`
13.        `}`
14.        `@Test`
15.        `public void testSearch() throws URISyntaxException, IOException {`
16.    `Handler h = new Handler("./technical/");`
17.    `URI rootPath = new URI("http://localhost/search?q=Resonance");`
18.    `String expect = "Found 2 paths:\n./technical/biomed/ar615.txt\n./technical/plos/journal.pbio.0020150.txt";`
19.    `assertEquals(expect, h.handleRequest(rootPath));`
20.        `}`
21. `}`

For directories, `-p[pattern]` is written as `less -p[pattern] technical/biomed/1468-6708-3-7.txt` and got this as my output:

1. `Background`
2.        `With the publication of the Antihypertensive and`
3.        `Lipid-Lowering Treatment to prevent Heart Attack Trial`
4.        `(ALLHAT), the role of peripheral alpha-1 antagonists in the`
5.        `treatment of hypertension has become controversial. The`
6.        `doxazosin arm of ALLHAT was stopped early, due to a`
7.        `doubling of the incidence of congestive heart failure in`
8.        `this group, as compared to the low-dose chlorthalidone arm`
9.        `[ 1 ] . Prior to this publication, there had been no`
10.        `obvious suggestion of a mechanism by which peripheral`
11.        `alpha-1 antagonists in general or doxazosin in particular`
12.        `would be inferior to chlorthalidone or would specifically`
13.        `cause CHF. Because ALLHAT is an active-control trial, no`
14.        `inferences can be made on whether this increased incidence`
15.        `of CHF results from a harmful effect of doxazosin, a`
16.        `beneficial effect of chlorthalidone, or both. Nonetheless,`
17.        `there has been a large body of literature dedicated to the`
18.        `positive effects of peripheral alpha-1 antagonists on`
19.        `surrogate endpoints such as cholesterol levels and`
20.        `tolerability. In light of the results of ALLHAT, we`
21.        `performed a review of the literature on doxazosin,`
22.        `terazosin, and prazosin.`
    
- Before I explain what happened, I did use a different file for the files part and a different file and `/technical` for directories and it's because I wanted to do something for the output and not show the same output for each output I ran for this report. They all do run on how they are supposed to in the bash terminal.
- Anyways, the two outputs shown look like nothing happend when I pasted them here. If you run the command with that option in the terminal, you will see there are some words highlighted. They are highlighted because a certain letter matched with whatever you wrote inside of that bracket that is after the `p`. I say whatever you wrote because I did try writing other words like `hi` in the bracket and the same thing happened. But when I ran `hi`, only the letters `h` and `i` were highlighted throughout the output.
- Just note that only the exact letters that are in the bracket can be highlighted meaning that if you did not capatlize any words, it doesn't matter if that same letter was found in the terminal. The command with that option will not highlight it like let's just in the bracket you had `a` and in the terminal there's an `A`. They are the same letters but that `A` will not be highlighted because you did not type it as a capital in the bracket unless you did have that capital somewhere in the bracket. This rule still applies to the lowercase letters if you decided to include capital in the bracket.
- Based on what I wrote and according to the website that I have been using for this report [Link](https://phoenixnap.com/kb/less-command-in-linux), `-p[pattern]` "Instruct less to start at the first occurrence of the specified pattern in the input file." This is useful if you want to find similar letters in the file by just simply typing someing inside of the bracket. It could be useful if you are doing some sort of assignment to find similar lettering in the file of a word you chose or assigned to inside of that bracket.

## The final option that I selected from the website is, '-X'. 
- In files, this option was written as `less -X DocSearchServer.java` and this is the output I got from running that command with that option:
1. `import java.io.File;`
2. `import java.io.IOException;`
3. `import java.net.URI;`
4. `import java.net.URISyntaxException;`
5. `import java.net.InetAddress;`
6. `import java.nio.file.Files;`
7. `import java.nio.file.Path;`
8. `import java.nio.file.Paths;`
9. `import java.util.ArrayList;`
10. `import java.util.List;`
11. `import java.util.Collections;`
12. 
13. `class FileHelpers {`
14.    `static List<File> getFiles(Path start) throws IOException {`
15.        `File f = start.toFile();`
16.        `List<File> result = new ArrayList<>();`
17.        `if(f.isDirectory()) {`
18.            `File[] paths = f.listFiles();`
19.            `for(File subFile: paths) {`
20.                `result.addAll(getFiles(subFile.toPath()));`
21.            }
22.        }
23.        else {
24.            result.add(start.toFile());
25.        }
26.        return result;
27.    }
28.    static String readFile(File f) throws IOException {
29.        return new String(Files.readAllBytes(f.toPath()));
30.    }
31. }

- In directories, the option is written as `less -X technical/government/media/Barnes_Volunteers.txt` and this is the output from the terminal:
1. `Barnes Volunteers as Lawyer to Poor`
2. `Wednesday, December 18, 2002`
3. `Defeated last month for re-election, Gov. Roy Barnes announced`
4. `Tuesday that he will spend his first six months out of office as an`
5. `unpaid attorney for the Atlanta Legal Aid Society, where he will`
6. `represent poor people.`
7. `"One day I'll probably do some legal work that I will charge a`
8. `handsome fee for - at least I hope there are those that are still`
9. `willing to pay," he told reporters.`
10. `"But for now, I think it is important to fulfill my duty as a`
11. `lawyer to help those who need it the most, to speak for those who`
12. `cannot speak for themselves and to defend those whose life and`
13. `livelihoods depend on it," he said.`
14. `Previous governors have gone to prestigious law firms, joined`
15. `corporate boards or returned to thriving businesses.`
16. `"I don't think I've ever heard of anybody doing this before,"`
17. `Emory University political science professor Merle Black said.`
18. `"If he's actually going to represent individuals for that`
19. `organization, they're going to get great representation. You're`
20. `going to get some powerful legal muscle there," Mr. Black said.`
21. `Mr. Barnes said he already has his first case, but he wouldn't`
22. `say what it is.`
23. `Atlanta Legal Aid providThes civil services to poor people in five`
24. `metro Atlanta counties.`
25. `Mr. Barnes said he was hoping to send a message to other`
26. `lawyers.`

- Yes, I decided to use a different file and directory again for the last option of the less command.
- When I ran the command with that new option, I did noticed that the output for both does look like nothing happened since I posted them here on github. But as usual as my other outputs, there is actually something happening in the terminal. When you reached to end of the file forn both, you do get the `(End)` message meaning that you have to type `q` in order to exit from that file. As soon as you type q, you do get back to your original bash terminal but you will see that the output from that code you were on is still there. Usually when you exit a file from bash terminal, you no longer see the context of that file and you only see the terminal.
- You can also type `q` before reaching to the end of the file, but just note that wherever you exit from the file, only the part you left off will be visible meaning that you can not see what the whole output actually is. If you want to see the whole output, then you just going to have to write that command and option again. In then, you have to keep scrolling until you reach the `(End)` message.
- So, based on waht I said and according to the website [Link](https://phoenixnap.com/kb/less-command-in-linux), the `-X` option only "disables clearing the screen after quitting less.". I believe the importance of this option is to make it easier for the coder to reference back file, due to the fact that he or she can see what is the context without having to write another code to see. 
