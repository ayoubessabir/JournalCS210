# finalproject

#Summarize the project and what problem it was solving.
This program receives a list of the history of items purchased from a grocery store and sorts that into a list of items and the amount of times each item was purchased, as well as create a backup of the original list.

#What did you do particularly well?
I'm happy with my choice to use a map to store each item as a key and associate each key with the amount of times they were purchased.

#Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
For this program, I had to use two vectors and a map. I used the map to print each item with their frequency of purchase, but I used one of the vectors to print a histogram of the items purchased and another vector to retrieve the original list before adding the items as objects. That was the easiest way for me to do it at the time but I think that I should have used only a map for each function to reduce the amount of lists I had to work with and maintain cleaner code. I also believe that there are functions I can find in the STL to streamline some of the code that I wrote manually. I would also like to have the Produce class separately and take some of the code out of the main method.

#Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
I had not used a map before this project, so I had to read and understand that function from the textbook as well as cppreference.com to figure out how to use it and what it's capable of.

#What skills from this project will be particularly transferable to other projects or course work?
Researching STL functions with cppreference.com was incredibly useful to me and I think it's going to be essential throughout my CS career.

#How did you make this program maintainable, readable, and adaptable?
I tried to separate tasks into their own methods to keep the main method readable and easier to maintain so that if I had to change it, I could easily do so.
