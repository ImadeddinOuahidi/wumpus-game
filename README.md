

# wumpus-game

## Summary

The Wumpus world is a simple world example to illustrate the worth of a knowledge-based agent and to represent knowledge representation. The Wumpus world is a cave that has 16 rooms.

## Background

 The Wumpus is a beast that eats anyone who enters the room; the Wumpus is located in only one of the rooms and he can be shot by the agent, but the agent has a single arrow. In the Wumpus world, there are some Pits rooms that are bottomless, and if an agent falls into Pits, then he will be stuck there forever. The goal is to search for the gold without falling into the pits or entering the Wumpus room. We will discuss the game details in this report.




## How is it used?

•	Safe (X,Y): it will return all the adjacent rooms (X,Y) that are safe.
•	grabGold(): it will return “Gold found in: (X,Y), PICK IT!” if the gold is in (X,Y) else it will return false. (X,Y) are the coordinates of the agent.
•	shootWumpus(): it will return true if  the Wumpus is in one of the adjacent rooms and false if not.
•	agent_position(X,Y): return the agent position.
•	breeze(X,Y): return yes if there is a breeze in room R(X,Y), else it returns no.
•	pit_position(X,Y): return whether the pit is in the room (X,Y) or not.
•	wumpus_position(X,Y): return whether the Wumpus is in the room (X,Y) or not.
•	stench(X,Y): return yes if the Wumpus is in one of the adjacent rooms else return no.
•	grab():  grab the gold in the current room
•	shoot_arrow(): it will shoot the arrow if there is one.
•	can_leave_cave(): it will return yes if the agent can leave else no.
•	climb(): it will leave the cave if the agent is able to.
•	check_down_room(): return ‘Room (~d,~d) is safe.’ If the below room is safe else return false. 
•	check_up_room(): return ‘Room (~d,~d) is safe.’ If the upper room is safe else return false. 
•	check_right_room(): return ‘Room (~d,~d) is safe.’ If the right room is safe else return false. 
•	check_left_room(): return ‘Room (~d,~d) is safe.’ If the left room is safe else return false. 
