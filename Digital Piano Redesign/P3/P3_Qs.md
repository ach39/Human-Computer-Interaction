
# Q1

1.1 principles that help in bridging  gulf of Eval or Execution

Discoverability
Feedback
Simplicity

Consistentcy
 If your UI components are all in the same place, have the same color and function the say way then your interface will disappear slowly over time… kind of like Marty McFly. But just simply putting all your call-to-action buttons in the same place on every page or calling a particular action the same thing through the app might not solve the consistency problem.
 
  An invisible interface has “real consistency“, meaning that not only are components, values, links, and other data presented consistently throughout the app, they are also consistent in context and meaning.
 
 
1.2 select two principles and describe how each principle could be used to create interfaces that emphasize the participant view of the user;
 1. Tolerance - asks for confirmation if document should save the doc.  e-purchase , interface asks if user would like to review his cart and shipping info before hitting 'palce order' button. In one iterface u can see your items, shipping address & method of payment.
 Forgiving the user means that we don’t punish them when they make mistakes. User mistakes are more often the result of the user not knowing what to expect. We tend to blame the user for making mistakes and we punish them with big warnings and errors. A more invisible UI refrains from punishing the user when they fall into a trap. Rather than displaying an error, a well designed UI predicts where there is a higher chance of user error in the app and provides a way for the mistake to be resolved or even deflected.
 
2. Equity - 
pulling down a menu or flipping a page in e-book is intuitive to both novice and expert user. Theses maninpulations ingrained in basic human behaviour and transends lanuguage barrier. 
 Text editor - use of scissors icon 
 
----------------------------------------------------------------------------------------- 
# Q2 select an interface that is intolerant of errors the user commits
 
2.1 Work VPN. 3 wrong tries and they freeze all your accounts, including access to different DBs and analytic tools.
 
2.2 Describe how constraints might be used to improve the interface to avoid errors in the first place
Just like 3-pronged plug, don't let user re-enter pwd until 60 sec expire. 
 
2.3 Describe how improved mappings could be used to avoid errors. *creating interfaces that makes it clear what the EFFECT OF THEIR ACTIONS ARE*
Display on window number of wrong attempts user has made until now. So it slows down as it reaches the max limit of 3.
 
2.4 Describe how improved affordances could be used to avoid errors
 In addition to above , one can throw a pop-up when user enters 3 time wrong answer within given time frame 
Interface should keep track if user entered x attmepts within 60 sec window.
 
-----------------------------------------------------------------------------------------
# Q3 
Temple Run is a 3D endless running video game developed and published by Imangi Studios. The game controls an explorer who obtained an ancient relic and is running from evil demon monkeys who are chasinghim.As the game is an endless running game, there is no end to the temple; the player plays until the character collides into a large obstacle, falls into the water or is overtaken by the demon monkeys. 
- Guy Dangerous, an explorer,
When the player needs to turn left or right, the touchscreen can be swiped in the corresponding direction. If the player wishes to jump over an object, the screen can be swiped upwards; if the player wishes to slide under an object, the screen can be swiped downwards. 

3.2  Describe a slip. Why slip occurs ? How interface can avoid it ?
I make mistakes like I know I am supposed to go right and I go left. I know I am supposed to jump but I accidently slide. These mistakes are sometimes results of rapid changing course and most often , me not paying attention.
- change : 
As course takes twist and turns, may a cue to what action to take can help user. Introduce check points from where user can restart the game if he fails an obstacle , rather than starting the run from the begining.
Interface should light the path with a different color as I reach that window , so that I know that its time to make the jump.

3.3  Describe an error. Why error occurs ? How interface can avoid it ?
I can see that I am reaching an obstacle that will require me to jump. I attempt to jump but still fall. why ? because game expects you make the jump when explorer reaches within certain distance of that obstacle. Too early or too late, you end up in ditch.For me as  novice user, it is hard to determine that window of perfect jump. For different obstacle this window is different.
- change : 
Interface should light the path with a different color as I reach that window , so that I know that its time to make the jump.

3.4 describe something that makes the game challenging, but that is not a slip or a mistake
 As the game progress, course becomes more difficult. At that point , explorers survival rests on player's reflexes.It escape a hurdle player needs to quickly decides (in matter of seconds) whether to jump or slide.

-----------------------------------------------------------------------------------------

Q4 
4.1 Interface with a good representation ?
Email Application
- exemplify at least two criteria of a good representation ?
good representations make relationships explicit : ~40+ emails in per day, it allows to quickly determine which ones are more important than other - email from Boss can assigned different color, so I must look into those first. Flag color on the side shows if I need to follow today or can I postpone is it till tomorrow. This layout shows me that I have more unread emails than read emails , flag colors show that I have more emails with that must be followed up today.

Second, good representations bring objects  and relationships together. object is email and relationship is importance of email.
Its allow conveys relative importance of emails in my inbox ( how important one email is in relation to other emails in my inbox.


4.2 select an interface that you would argue does not use a good representation of its underlying content
 Evaluating data in excel that has positional data.
 Incontrast , we if view that in Power-BI, it understands lat/long or zipcode/state/Country and projects relevant stats on a map.

- violate at least two criteria of a good representation?
good representations make relationships explicit - I can't determine the relatioship of postinal data with other fields in the data.
In fact, effective visualization of data is a key tenet of good representation.  

Doesn't expose natural constraint - In pivot table, interface allows user to put in lat/long which by default show average of lat/long 
which is meaningless. Plot it on a map.




4.1  

my area's light rail system MAP
a good representation excludes extraneous details - removes distance / underlying topology.

good representations make relationships explicit - Laying things out like this makes it easy to tell for which route I multiple options vs route with single options







A slip is when a user has the correct mental model of how a system works, but accidentally made the wrong action. 

A mistake, however, is when the user does exactly what they intend to do, but they have the wrong mental model of how the system works.

