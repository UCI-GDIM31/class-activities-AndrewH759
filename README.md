# in-class-activities
## "Hello World!"
### W1
"Hello World!"
### W7
https://docs.google.com/document/d/1FI6_2kwBTTaRBxAmNkWfBAGIedIvuOI0K7P5KUZhsA8/edit?tab=t.0 
gameplay system and a bit of outline

### W6

https://docs.google.com/document/d/1v9abHr0z2I_ynx3ik8Slda9mncvm8eCeKY5KIBUfL-c/edit?tab=t.0
### W5 


1. Vector is never overkill. 
2. First to make the class  with monobehavior and then get the Transform of the object and make the serialized field so we can change it in unity. Then, make a member variable for transform object - make a member variable for the mesh. Make a start method so that we can initialize  the NavMeshAgent with the current gameobject Mesh. Then int the start method change the destination of the navmeshto the position of the transform.


### W4

Table 17:
Do your best to describe the following lines of code:

    line 17: private bool _isGrounded = true;
    This sets a member variable of type boolean to the value true 

    line 28: if (Input.GetKeyDown(KeyCode.Space) && _isGrounded)
    This line calls the method GetKeyDown() with the parameter KeyCode.Space to see if the space key was clicked and it checks if the isGrounded member variable is true.

    line 32:_isGrounded = false;
    This line changes the _isGrounded member variable to false

    Pt2. 

    I did rigid body for the cat and ball because those collide and i did istrigger for the goal because it examines if ball is in r out.

    I accidently put the istrigger on the ball because and it fell through the floor. 







### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.

The r,g,b variables are floats instead of ints because they derive from the color wheel going from 0 to 1. Bounce is an integer because it can only bounce once at a time and not like half a boucne. Every bounce is a full 'one' bounce. Step 4 part two had a missing semicolon at the end of the line - which is essential to execute the statment. 

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 