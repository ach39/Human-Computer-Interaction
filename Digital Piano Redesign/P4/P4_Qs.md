
Goal is to submit assignement and subsequently receving grade and feedback.

Tasks :
1. (Prerequiste) - Complete the assignment
2. Submit the assignment
3. wait (for assignment to be graded)
4. Check grades and read the feedback

Plan : do 1 , 2
	when email notification for grade-completion is received
	  do 4
	
Hierarchial Task Analyis of above task# 2 and 3 is presenetd below.
	





#Q1  GOMS

Initial State : Student has questions about her grade and wants to get an explaintion from Professor


Selection Rule : Select method-1, if request_type = non-urgent(ie can wait for >= 48 hours) or formal and if contacting Professor via Piazza is allowed per course policy. 
Method 1: Piazza
1. Open computer
2. Accomplish Login(Piazza)
3. Click 'New Post'
4. select Post-Type = Question  
5. Click radio button 'Instructor' . Set Post_to =  Professor's name (can be selected from drop-down menu)
6. Type in one line summary  in 'Summary' field
7. Type in inquiry regarding grade 'Details' field.
8. Proof read post-description.
9. Hit 'Post My Question' button


Selection Rule : Select Method-2, if request_type = non-urgent and formal
Method 2 : Email
1. Open computer
2. Accomplish Login(Email Application - gatech O365 outlook)
3. Click 'New' button (on top left) to compose email.
4. Enter Professor's email-id in To field.
5. Add a subject line
6. Type in inquiry regarding grade in Message box
5. Proof read email.
9. Hit 'Send' button


Selection Rule : Select Method-3, if (student_type = on-Campus) and (request_type = urgent (require response ASAP)  or back and forth conversation is expected)   
Method 3: In-person
1. Walk to Professor's office
2. If Professor = 'Available' to talk
	Enter the room
    Greet professor 
	Ask questions regarding grade.
	Once all questions are answered, thank Professor.
	Leave office 
  Else :
	if Professor = 'Out of town'
		select other method (Email or Piazza)
	else :
		Leave a note requesting in-person appointment with professor


Selection Rule : Select Method-4, if request_type = urgent and if contacting Professor via phone is allowed per course policy.   
Method 4: Phone

1. Goto Professor's website.
		1a. Open computer.
		1b. Open browser
		1c. Type in Professor's website url.
		1d. hit enter 
			
2. Note professor's office-phone number.
3. Note Hours when calling Professor is allowed.
4. Wait until correct  
5. Pick up phone.
6. Dial in professor's phone number.
7. Press call button.
if professor picks up phone 
	8. greet professor 
	9. Ask questions regarding grade.
	10. Once all questions are answered, thank Professor.
	11. End the call - press disconnet button.
else
	if voice-mail is setup
		12. leave message for Professor
	else
		13. Hang up


Selection Rule : Select Method-5, if back and forth conversation is expected and contacting professor via chat is allowed per course policy ) 
Method 5 : Chat(Slack)

1. Open computer
2. Accomplish Login(slack)
3. Goto desired class
if professor is available online
	4. greet professor 
	5. Ask questions regarding grade.
	6. Once all questions are answered, thank Professor.
	7. End the call - press disconnet button.
else 
	8. leave an offline message for professor
	
	
	
Sub_method : Login(Application)
Instantiate this Application by clicking icon or typing in its url
1.Recall your login for this Application.
2.Type in your login
3.hit Enter (cursor moves to password field)
4.Recall your password for this Application.
5.Type in your pasword.
6.Hit enter

Goal : Student's questions regarding her grade are addressed by professor. 




#Q3 Analyze this system from the perspective of distributed cognition: 
# what cognitive activities, including perception, memory, reasoning, and acting, does each part of the system perform? 
# Make sure to differentiate and individually comment on the driver, the passenger, the map, and at least one other piece of the system.

Ans
Conginitve activities - The task of driving is congnitively demanding. It requires user to perform multiple actvities in parallel such as monitor surronding traffic, keep track of his speed ,monitor route. In given scenario, task of driving involves mutltiple agents and artificats, each contribution to success of task by sharing the congnitve load.More specfically,

1. Driver : Driver(wife) uses perception to monitor surrounding cars to determine when its safe to change lane and adjust her own speed. She also percieves weather condition and reasons over this information to take appropraite action.Eg : she lowers her speed  if there is low visbility due to heavy rain.

2. Navigator  : Navigator (Husband) uses his perception to determine possible route(s) to destination on Map. He reasons over these routes to determines best route  Eg : take scenic route if they are not in hurry or take local roads if higways are too crowded during that time. He translate this info verbally to provide directions to wife as she is driving.
If couple is visiting a known area, husband can also draw upon his memrory to recall the best route, without heavily relyin on Map.

3. Map :  Map serves as an extension of navigator's memory. It offload's navigator from having to rememberentire route.Navigator refers to map to accomplish his moment to moment goals such how far is the next exit , whether exit is on right or on left.

4. Surrounding traffic : From speed of surrounding cars, user can percieve traffic conditions and adjust her speed accordingly.Type of vehicles (presence of Police cars and/or ambulance) helps driver infer that there might an accident and prompt Navigator to look for alternate route.


5. Road/Exit signs and landmarks : While Map can be thought of as extension user's long-term memory, Exit signs and landmarks serves extension of 'working memroy'.She doesn't have to rememeber that in x meters she needs to take the exit. Rather she relys on exit-sign and acts accordingly as soon as she sees one.


#Q3b bcompare and contrast this same situation with a lone driver using a GPS
# Focus specifically on the social components that are present with a human navigator but absent with a GPS navigator.
# what does social cognition reveal about the situation that distributed cognition does not? 
# How might the social relationships among the parts of the system affect the success of the system as a whole?


Now consider the case where GPS replaces human navigator. From following three scenarios we can see the social relationship between driver and navigator shapes the success of system/task of 'Reaching destination safely and on time'  

1. While GPS is good at providing directions, it can't accurately infer the context in which driving is occuring or driver's state of mind. In contrast, human navigator can see driver didn't fully stop as Stop sign or is driving above speed-limit and warn driver about it. With no such warnings, driver might get pulled over by cop and hence may not reach destination on time.

2. Assuming couple has emabarked on long drive , human navigator can gauage driver's level of fatigue after few hours of drive, which GPS can't. Human navigator can offer to take the wheels or start an interesting conversation or play music that driver likes if driver is feeling sleepy. This reduces chances of accident.

3. GPS is as as good as data it gets and can't beat human navigator's improvisation.If driving through moutainous area, GPS receiver needs to be able to see enough of the sky to receive signal from GPS satellite. Fortunatley, human navigator doesn't have this dependency and a map is all he need to successfully accomplish the task of reaching destination.










#Q4

#describe the pieces of the system.
 -- Water supply , electricty, detergent 

My mobile

Weight sensors - select load type 

Spin speed
job-scheduling - 
	can allow wash to start at certain time.
	fabric softner needs to added at a certian satge of wash

Safety lock -


# what cognitive tasks (memory ,perception, reason, action) are performed by each member of the system, both human and artifact alike


My mobile - extension of my memory

Weight sensors - senses wt and reason over it to select right load type

spin speed - reason over spin cycle fabric type

job-scheduling - memory and takes action

Safety lock - proactively percieve the danger someone accidentally opening the lid while there is water in the dri






