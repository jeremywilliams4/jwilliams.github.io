# JEREMY WILLIAMS, SOFTWARE DEVELOPER
![copper_pattern](https://user-images.githubusercontent.com/75949144/205489662-106c1ff5-81a7-4fc8-9f36-51a82d5f0984.jpeg)

## NARRATIVE

My artifact for the: 1) Software Design and Engineering, 2) Algorithms and Data Structures, and 3) Databases, categories is a program titled, “ClientList”. This is a project from my CS410 class, Software Reverse Engineering. This is a simple program that prompts the user to select from a menu of options and then reacts according to that input. The program will display a current list of clients, and then allow the user to select a specific client to view their investment option, or exit the program. I chose this program because it seemed like a great example of a real-world scenario and could allow for expandability. I imagined this type of program to be much like one that a business such as a bank, for example, may use to keep track of client information. The program is quite simple but is still able to showcase my ability to transform a real-world business need and convert it into a software solution.

  For this artifact I performed the following enhancements to align with the three different categories mentioned above:
### 1)	Software Design and Engineering
-For this category enhancement, I converted my original C++ program into Java. Being able to translate a program from one language to another was a great way for me to showcase my computer science skills for this category.
### 2) Algorithms and Data Structures
-For this category enhancement, I expanded the complexity of the original program by converting the list of clients from individual variables to members of an ArrayList. This showcased skills and knowledge of data structures as well as made the program more efficient and easier to expand in the future. For this category I also implemented some improvements regarding the security of the program by adding input validation and exception handling. Now the program will verify that the user input is within the range of the menu options. If not, the user is prompted with a message to make a valid entry. The user input required for the program to run has to be an integer. In order to provide further input validation, I used try/catch blocks to handle any exceptions thrown from a letter being entered instead of an integer. 
### 3) Databases
-For this category enhancement, I chose to use the ArrayList built by the program, to            populate a MySQL database. This was a great way to solve a real-world business problem and allow me to demonstrate my ability to work with databases in a way that incorporates useful business tools and software solutions. Now, everytime the program is exited, a connection to a MySQL database is established that loads the contents of the clientList ArrayList into a database. 
  I learned quite a bit from revisiting my original program and then performing the above enhancements. I was reminded of the similarities of C++ and Java. Not suprising since Java was built on a C++ foundation. However, there were some syntax differences like method naming for instance that I had to correct. I also had to go about input validation a little differently than I would have had to in C++. These challenges, however, only strengthened my programming skills and led to a higher level of confidence and better performing program. Feedback was tremendously helpful as I navigated my way through the enhancements. I learned from that feedback that my original plan for the Databases category was not strong enough to showcase my proficiency in this area. I wanted to simply create a user log-in database for the program. However, the program now is much more sophisticated in the Databases category after building upon professor feedback. Instead, the program will load a MySQL database upon closing the program with the contents of the ArrayList of client names. 
	The program described above allowed me to demonstrate my profiency in a range of computer science disciplines. It was also a great learning opportunity to revisit an old program and make necessary enhancements to it. Along with these advantages, this program and the work that I performed throughout all three categories of enhancements, clearly lay out my successful completion of the Five Course Outcomes outlined below:

### 1)	Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
i.	I was able to achieve this in my portfolio with my artifact, ClientList, by taking a program originally written in the C++ language and translating it into Java, while maintaining its efficiency and honoring its original design features. This process is proof of my ability to operate in a collaborative way and be able to adapt to different audiences, diverse programming environments, and make decisions necessary while adhering to design techniques and user requirements. 
ii.	I also successfully showcased my proficiency in this course outcome by my enhancement in the Databases category with this artifact. This enhancement meets that criterion by its utilization of trusted database software, MySQL, and taking advantage of its cohesiveness with Java and the Eclipse development environment. By using these combined tools, I have shown that I am able to use well-founded and innovative techniques to solve a computing problem. The solution offered in this program is an industry-specific one that will meet many relevant business needs: collecting client information, verifying that information, protecting that information, and allowing for expansion in an easy to maintain and simple software solution.
### 2)	Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
i.	I was able to meet this course outcome in my portfolio by performing a code review of my original version of my artifact, ClientList. For this code review, I created a screencast where I was able to walk through an evaluation of the program and highlight areas for improvement. This code review is an example of the skills I have obtained in analyzing a program, identifying its structure, and finding room for improvement. Code reviews are a regular part of a software developer’s duties. The code review included in my portfolio showcases my knowledge of programming basics and best practices. It also shows my ability to create visuals and presentations that are easy to operate, easy to follow, and professional. 
ii.	I was also able to meet this course outcome by including descriptive, informative, and useful in-line comments to the code in my artifact, ClientList. The comments included in this program describe its functionality and purpose in a way that will make it easy for any developer to follow. This skill is one that is vital for a programmer to have. Most projects are done in a collaborative way and it is very important that the work that one developer does to a program can be easily deciphered by another developer. Having people who are proficient in this area of the software development world is the only way we can have the sophisticated software solutions available to us today.
### 3)	Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
i.	
### 4)	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
5)	Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources


