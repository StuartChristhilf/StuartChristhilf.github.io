
---
<span style="font-family: Comic Sans MS; font-size: 30px;">
[Turtle Typer](https://stuartchristhilf.github.io/turtletyper.git.io/): A Fun Typing Game with a Twist
</span>

Turtle Typer is a Java Data Structures (H) final project I developed during my junior year of high school. It's not just a typical typing test; it's a challenge that measures your typing speed using interesting turtle facts.

---
## Planning
For the planning of my code I designed a flowchart outlining my code. It had a couple main aspects, being that I wanted two data structures one that holds all the characters the player types and one that holds the characters of the sentence they are supposed to type. I wanted the sentences to be held in a tree that I could go through depending on how well they do. I also wanted an observer that would compare the two data structures as if they were a hash table. Using this as my basic plan I was able to create a working code that almost did everything I wanted at first.

## Programming Process 
As for the process of actually programming I started off by programming the actual site shown in a file called index.html. It was the backbone of the entire project being what the player actually sees. After creating it I went on to create the player list and have its inputs be made by what the player types in the html element text box in the index file. After I made the player list I made the turtle tree class which holds all the sentences/ facts that the player will need to type. Once I had created that I had a little trouble making it so that you could navigate that tree in the index class so that it could be displayed on the website, but figured out a flaw in the constructors of my original tree class and could then easily navigate through it in the index class, in the process also making it a singleton because it could only be called by the index class because of the variables required to call it. Next I had to make an observer to compare the two data structures of characters to make sure they match. This took by far the longest because of getting all the data and comparing it, but by adding some extra methods I was able to get it to be able to access the other data structures and be able to check them, and then cause the index code to move on to the next sentence.
Using and Showing Off Your Code 

## Slides
[link](https://docs.google.com/presentation/d/1LPZ2BaYflQkgZNC0BkFV4Fwin5DjhRhYnGcx9SLzeBk/edit)

Here is the slides where I go in-depth on my code and its uses that I used for my presentation.
