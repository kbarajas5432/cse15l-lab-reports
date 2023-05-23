# Lab 3- Command Research

There were so many commands for bash that I learned in this course and discovered what they do in lab. The one command that I am researching for this report is the `less` command.
Since I found this command interesting, I decided to go on [Link](https://phoenixnap.com/kb/less-command-in-linux) to look at four interesting comman line options or another way of writing `less`.
When looking up ways on writing the less command, I saw that one of the ways was `N`
- When using that code in files, I wrote it as, `less -N Server.java`. Writing the code this way, gave me this output: `
`1 // A simple web server using Java's built-in HttpServer`
      `2`
      `3 // Examples from https://dzone.com/articles/simple-http-server-in-java were useful references`
      `4`
      `5 import java.io.IOException;`
      `6 import java.io.OutputStream;`
      `7 import java.net.InetSocketAddress;`
      `8 import java.net.InetAddress;`
      `9 import java.net.URI;`
     `10`
     `11 import com.sun.net.httpserver.HttpExchange;`
     `12 import com.sun.net.httpserver.HttpHandler;`
     `13 import com.sun.net.httpserver.HttpServer;`
     `14`
     `15 interface URLHandler {`
     `16     String handleRequest(URI url) throws IOException;`
     `17 }`
     `18`
     `19 class ServerHttpHandler implements HttpHandler {`
     `20     URLHandler handler;`
     `21     ServerHttpHandler(URLHandler handler) {`
     `22       this.handler = handler;`
     `23     }`
     
- For directories from `./technical`, I wrote the code as, `less -N technical/911report/chapter-1.txt` which I got this output:
`      `1`
      `2`
      `3`
      `4 "WE HAVE SOME PLANES"`
      `5`
      `6     Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions of men and women readied thems      6 elves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York City. Others       6 went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session. At the other end of       6 Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. Bush went for an early mornin`
      `6 g run.`
      `7`
      `8     For those heading to an airport, weather conditions could not have been better for a safe and pleasant journey. Among the travelers were`
      `8  Mohamed Atta and Abdul Aziz al Omari, who arrived at the airport in Portland, Maine.`
      `9`
     `10 INSIDE THE FOUR FLIGHTS`
     `11`
     `12 Boarding the Flights`
     `13`
     `14     Boston: American 11 and United 175. Atta and Omari boarded a 6:00 A.M. flight from Portland to Boston's Logan International Airport.`    
     `15`
     `16     When he checked in for his flight to Boston, Atta was selected by a computerized prescreening system known as CAPPS (Computer Assisted P`
     `16 assenger Prescreening System), created to identify passengers who should be subject to special security measures. Under security rules in pl     16 ace at the time, the only consequence of Atta's selection by CAPPS was that his checked bags were held off the plane until it was confirmed`
     `16 that he had boarded the aircraft. This did not hinder Atta's plans.`
     `17`
     `18     Atta and Omari arrived in Boston at 6:45. Seven minutes later, Atta apparently took a call from Marwan al Shehhi, a longtime colleague w`
     `18 ho was at another terminal at Logan Airport. They spoke for three minutes.`
     `19`
     `20     It would be their final conversation.`
     `21`
     `22     Between 6:45 and 7:40, Atta and Omari, along with Satam al Suqami, Wail al Shehri, and Waleed al Shehri, checked in and boarded American`
     `22  Airlines Flight 11, bound for Los Angeles. The flight was scheduled to depart at 7:45.`
     `23`
     `24     In another Logan terminal, Shehhi, joined by Fayez Banihammad, Mohand al Shehri, Ahmed al Ghamdi, and Hamza al Ghamdi, checked in for Un     24 ited Airlines Flight 175, also bound for Los Angeles. A couple of Shehhi's colleagues were obviously unused to travel; according to the Unit     24 ed ticket agent, they had trouble understanding the standard security questions, and she had to go over them slowly until they gave the rout`
     `24 ine, reassuring answers.`
     `25`
     `26     Their flight was scheduled to depart at 8:00.`
     `27`
     `28     The security checkpoints through which passengers, including Atta and his colleagues, gained access to the American 11 gate were operate     28 d by Globe Security under a contract with American Airlines. In a different terminal, the single checkpoint through which passengers for Uni`
     `28 ted 175 passed was controlled by United Airlines, which had contracted with Huntleigh USA to perform the screening.`

- The `N` command for less, basically "shows the line numbers at the beginning of each new line" as mentioned from the website [Link](https://phoenixnap.com/kb/less-command-in-linux). I think the importance for the command is to make the count easier when reading from the bash terminal. What I mean easier is that if you were to write less without that command, you will see the lines with the text but there will be no numbers shown at the begining.
- Just note that for files, there are actually 55 lines, while directory has 731 lines. I decided to not include the whole output for both because I didn't want to write too much for the output in my report.
- Also, you will see that there are some numbers that repeat and it's because the text was too big to fit in one line of a terminal, so they just indent for a new line but with the same number. That number will just show that the test belongs with that line number.



Delete this: Files example: `less Server.java`   Directories: `less technical/911report/chapter-1.txt`
