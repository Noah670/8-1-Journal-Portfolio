# 8-1-Journal-Portfolio Noah Pohl CS210 

### Summarize the project and what problem it was solving.
This project involved creating a visual representation of a 12 hour and 24 hour clock. These two clocks were then displayed to the user where they could view and interact with them by manually adding hours, minutes and second to both clocks.

### What did you do particularly well?
I think the overall visual representation of both the clocks was very clear and concise to the user. The menu that pops up giving the user a list of 4 different options to add time to the clocks is also easy to understand.

### Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
In this first project I definitely could have used C++ header files to make my code more readable and secure. Both of the two main displays for the clocks could have gone into a seperate CPP file and then a main.cpp file to run the application. This would also allow me to add more features to the application in the future without having to rewrite all the code.

### Did you find writing any piece of this code challenging, and how did you overcome this? What tools and/or resources are you adding to your support network?

I had a very difficult time at first trying to figure out the best way of manually switching the time from the 12 hour clock between A.M. and P.M. once it had already been switched. I was able to solve this problem by first checking if the hours in the first clock were already past 12 and then if it was morning or afternoon. Then once the time had passed 12 I would manually set the first clock back to 1 and then check again if the time was morning or afternoon.


### What skills from this project will be particularly transferable to other projects and/or course work?
Completing the project was incredibly important as it helped me really understand how a larger scale project in CPP and other languages might work and how much focus should be on creating an intuitive and polished user experience. Working with multiple functions was also helpful as it allowed me to get more comfortable working on larger concepts and ideas.


### How did you make this program maintainable, readable, and adaptable?
I tried to make the program readable and maintainable by documenting and explaining much of the code written. I want this code to be easily understood by everyone reading it and even myself if I ever plan on revisitng it in the future and forget my own though process. I believe the inline comments will help clear up any confusion over what some parts of the code is doing. I also tried the majority of code in seperate functions closer to OOP designs and adatability. I would evenutally like to expand upon this program and create a GUI version of the clock which could display without the command line.
