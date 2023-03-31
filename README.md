# NPC-Engine 
NPC Engine refers to a system that assists in the spread of information within a virtual 
world. NPC Engine tracks both what the user does and the events of the world to allow the 
player a more immersive, and consequential experience. The end goal is to have a program 
that realistically simulates interactions with the world’s NPC population by utilizing the 
GPT-4 API and a database of information.
# 1 Introduction
This technical report presents NPC Engine, a planned model capable of simulating the intricacies of 
communication, and how that communication spreads across an expansive and detailed world. Such a 
model relies on a deep understanding of the world itself, and will require a database of the world’s 
lore, including available means of transportation of people and information.

One of the primary goals of this model is to replace static and semi-dynamic dialogue options with the 
ability to express oneself to the NPCs however one chooses. In turn, the NPCs will have GPT-4 
generated responses based on their knowledge along with a large quantity of variables to allow for 
further finesse. Such variables may include cultural background, environmental factors, relationship, 
status, personality, age/maturity, current/recent events, and more. This report will go into further detail 
on all of the variables and the extent to an NPC’s knowledge and the formulae that will help generate 
the dialogue. 

Seeing as the user is capable of saying anything to the NPCs, this model should be viewed more as a 
sandbox RPG experience rather than a more traditional one. To counteract this, there are plans to 
develop an optional variable that matches what the user says to the world’s lore database. The 
response to lore unfriendly dialogue is up in the air. 

Another concern is the use of offensive/racist slurs. Although NPC Engine itself won’t be capable of 
generating such responses, care must be taken to minimize harm to users. One way to counteract this 
is to design NPC Engine in a way that encourages responsible dialogue and interactions by subjecting 
the user to consequences for harmful or inappropriate behavior. 

This report also covers edge cases where GPT-4 refuses to respond to a particular prompt, for one 
reason or another. This may need to elicit a dynamic response, or alternatively, an administrative 
message to the user making them aware of the issue if it occurs. This is being worked out. 
However, there are limitations to this model that are difficult to work around. Specifically, because 
NPCs use the GPT-4 API to generate dialogue, response time varies and is of considerable worry. 
Another concern is the programming languages that can interact with the GPT-4 API, possibly 
limiting development.
# 2 Scope and Limitations of this Technical Report 
This report focuses on the concept and ideas surrounding NPC Engine. Development for this project 
has not begun, therefore much of this report is subject to change and may be inaccurate. 
# 3 NPC Engine Design 
## Header Note ## 
### 3.1 NPC Communication 
NPC Engine will be designed to allow for natural and fluid communication between the player and 
the NPCs. The model will use the GPT-4 API to generate responses that take into account the NPC’s 
knowledge, cultural background, environment, relationship, status, personality, age/maturity, and 
current/recent events. 
### 3.2 Lore Database 
NPC Engine requires a vast and intricate database of the world’s lore to simulate realistic interactions 
between the player and the NPCs. This database will include information on the world’s geography, 
history, culture, technology, magic, politics, and more. The lore database will be used to ensure that 
the NPCs’ responses are lore-friendly and consistent with the world’s established rules and history. 
### 3.3 User Input and NPC Responses 
NPC Engine will allow the player to input any dialogue they desire, with the NPC responding based 
on their knowledge, personality, relationship with the player, and other variables. The NPC’s response 
will be generated by the GPT-4 API using the information from the lore database and other relevant 
variables. 
### 3.4 Offensive/Racist Language 
NPC Engine will be designed to minimize harm to users by avoiding the use of offensive or racist 
language. While the GPT-4 API itself will not generate such responses, additional measures will be 
taken to encourage responsible dialogue and interactions by subjecting the user to consequences for 
harmful or inappropriate behavior. 
### 3.5 Edge Cases 
NPC Engine will address edge cases where the GPT-4 API may refuse to respond to a particular 
prompt. The system will either elicit a dynamic response or send an administrative message to the 
user if necessary. 
# 4 Variables 
# 5 NPC Relation Web
