##Read whole curriculum before starting as there are interdependencies##

Create GitHub account
Download Atom open source editor
Download Github Desktop Client
  *learn to use git in cli*
Connect Github Desktop to your GitHub account

This is all infinitely easier on a unix system so either get the rpi going or
create a debian dual boot on your dev machine

Learn UML Class Diagram modeling (Dia is my favorite program for this)
  Learn to represent classes, association, inheritance, composition etc.

#LEARN OBJECT ORIENTED PROGRAMMING BEST PRACTICES#
  If you follow them in your code
    -When you change one thing, everything else wont break
    -When you want to add something it will be easy
    -Other people who look at your code will have an idea as to what the fuck is going on
  *encapsulate what varies*
  *code to the interface not the implementation*
  *favor composition over inheritance*
  *aim for loosely coupled designs between objects that interact*
  *classes should be open for extension but closed for modification*
  *depend on abstractions, not concrete classes*
  *a class should only have one reason to change*
    ##Learn these rules inside and out##
      Single responsibility
      Open and Close Principle
      Richter substitution
      Dependency Inversion Principle
      LoD Least Knowledge Principle
  *Exercise based on this using UML design*
    Dowload Dia (uml modeling software) (open source so dont worry about viruses)
    Create a naive class diagram for a program that finds a pattern in any string and attempts to continue it
    Now you will test all of this OOP shit rules against it AND
      Make a design that does not violate any of these rules
    Implement it in Java using intellij idea.
      All the while versioning with github
        remember: DETAILED COMMIT DESCRIPTIONS



Watch videos on how to use git, versioning etc.
  *Understanding versioning/forking/merging is more important in a code team than knowing blackmagic code tricks*
Watch videos on documentation best practices.
  In Intelij Idea you can write your documentation directly in your code and then automatically
  generate a full indexed and organized web page that explains every part of your code. Its called javadoc and its worth learning. That goes for most any other language.

##Create Repository Using Github Desktop the click open in Atom##
  *every time you make a significant change to your code*
        You will:
          Go to github desktop
          Create a title for the commit
          And completely describe what you have actually done
          Commit
          and Push to GitHub.com
  \\Come up with a program to code\\
    Decide on a programming language
      *here is a list of languages to work on*
      Python (nice one to start with)
        *install python to your cli*
        *you will run your program via cli using the command >python3 ./yourRepo/pythonfile.py*
      Java
        Just install Intelij Idea IDE and a JDK, its the simplest way to work on this
      Clojure
        *install clojure to cli*
        This is another interpreter language so the workflow is simmilar to python
      PHP :(
        Dont waste time with this, it has been almost entirely replaced by Node.js
      Javascript
        Create an index.html
        Create a script.js
        Link script.js to the index.html
        When you wanna test your code just open index.html in your web browser
      NodeJs
        *cli*
          Install node
          Install npm (package manager)
          *npm init* (in your repo)
          *npm install nodemon*
          create server.js
          *nodemon server.js* this will run the node js server constantly and if there
          is an error it will wait till you fix it to try running the server again
    __REPEAT until you have a good looking, diverse, portfolio(https://github.com/yourUsername?tab=repositories)__

#####You should end up with a GitHub.com/yourUsername that looks like this#####
https://github.com/M4RS-music?tab=repositories

explore my repos
*repo*express js starter pack is a great learning tool for you to figure out node

Create a linkedin
Add your github link and make sure people are drawn to look at it

__Exercise Ideas__
Create a tic tac toe game where either you play against the computer or with a friend
  The idea is making the machine play perfectly, AND making the machine recognize win conditions
  Your game should be able to have the grid size, and amount of peices connected necessary changed
    If you follow OOP this should not be a problem ;P.
