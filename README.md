# GAME_PROGRAM-EXP-6
# Implement the AI random movement.

# AIM :
Implement the AI random movement.
# Algorithm:
Step:01 Create a Character Blueprint.

Step:02 Create a Blackboard.

Step:03 Open the Behavior Tree editor.

Step:04 Create Behavior Tree nodes for the following,  "Selector" node: Controls the execution of child nodes.  "Service" node: Monitors and updates values in the Blackboard.  "Sequence" node: Executes child nodes in sequential order.  "Random" decorator: Randomly selects a child node to execute.  "Move To" task: Moves the AI character to a specified location.

Step:05 Set up the Blackboard with vector key and bool keys and save it.

Step:06 Set up the AI character Blueprint with the help of AI controller component.

Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AI Character Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”

Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the desired play area.

# OUTPUT :

<img width="1125" height="814" alt="image" src="https://github.com/user-attachments/assets/b54be6be-7ef3-4ab6-9787-57fc2b3d055e" />

<img width="1006" height="393" alt="image" src="https://github.com/user-attachments/assets/4896e370-cd78-4ab6-8380-09ddf34c6a9d" />

<img width="1098" height="397" alt="image" src="https://github.com/user-attachments/assets/aef9f49e-1a85-4fc0-81bc-be09b3974db7" />

# RESULT :

Thus, the AI concept to the actor for a random movement is implemented.

