We used the programing language lisp to create an Intelligent knowledge based system about magic. The user can watch a magic trick, then answer the questions asked by the system and the system will tell him how the magic trick is done

To create this knowledge based system, we used 3 databases, a fact database, a rule database and a question database.
The fact database is what we update according to the user's answer the rule database.
The rule database is based on my knowledge of my card magics, we use it to update the fact database.
The question database is where we store every questions that our system can ask about the magic trick.

We used an inference engine that workson 2 level.
First the egine will ask the question with the first priority based on our knowledge of magic. The engine will update the fact database with the user's answer and by confronting the rules and the fact database.
Then, the egine will determine which questions should be asked to get to an answer the fastest way possible, and it will ask this question. It will update the fact database the same way.
The engine will continue until it has found an answer or there is no more questions to ask.


This project was created by Alexandre Mazgaj and Guillaume Galasso
