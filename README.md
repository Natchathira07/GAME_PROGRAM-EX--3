# GAME_PROGRAM-EX--3
## EXP - 3 Change the third person character mesh and add animations
Name :Natchathira VD
<BR>
Reg no : 212224230178

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure
Import New Character Mesh and Animations:

In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).
Replace Character Mesh:

Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the Details Panel, change the Skeletal Mesh to the newly imported mesh.
Set Animation Blueprint:

If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.
Preview and Test:

Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.

## Output
<img width="904" height="573" alt="image" src="https://github.com/user-attachments/assets/364bed39-931a-47bd-92ca-312930d9a133" />
<img width="584" height="521" alt="Screenshot 2025-11-19 141918" src="https://github.com/user-attachments/assets/718c8c5e-474d-4615-a672-681e1946b4ac" />
<img width="1587" height="918" alt="image" src="https://github.com/user-attachments/assets/eac780ec-f0f8-4a88-abee-7056d9d3a384" />

## Result
Therefore, the default Third Person is C.
