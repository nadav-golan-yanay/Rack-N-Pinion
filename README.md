# Rack-N-Pinion

https://cad.onshape.com/documents/f628dda98c75944375f40e69/w/c4f0d4abc367084e68fe07da/e/85d5af73aea108f7bda9cd61?renderMode=0&uiState=6705ae35456faf2b82659182

## How to Use the Feature
### 1. Create a Spur Gear
Using the Spur Gear FeatureScript, create a gear.

You can modify the depth of all the parameters except the Pressure Angle.

Remember the Module of the gear!

![image](https://github.com/user-attachments/assets/9daa6886-68f7-498b-9ce1-9359d6ff3916)


### 2. Create a Point

Create a new `sketch`, and at the intersection between the `top plane` and the `pitch circle`, create a point.

![image](https://github.com/user-attachments/assets/582791ec-a439-4f74-89e3-77f8ba65e114)


### 3. Creat the Rack
Using the `Rack And Pinion` FeatureScript, create the first tooth.

In the `Sketch vertex or mate connector`, select the point from the previous step.

Select the correct `Module` and choose the desired `Depth`.

![image](https://github.com/user-attachments/assets/44cfab29-a2b3-4135-8e72-944183a30b12)


### 4. Create a Linear Pattern of the teeth
*Currently, you need to create your own linear pattern using Onshape's linear pattern feature. I'm working on including this in the Rack-N-Pinion script.*

Create a `Linear pattern`. In the `Entities to pattern` field, select the tooth you created. In the `Direction` field, select its edge.
The `Distance` should be **Module × π** (PI).
Choose how many teeth you want, then click the green checkmark..

![image](https://github.com/user-attachments/assets/9f7b88a1-8ac0-4682-ab85-91f85319e90f)


**Congratulations!** You've just created a Rack and Pinion! Use it wisely!!!


##Future Goals

- [ ] Include the linear pattern in the script.
- [ ] Make it automatic, so you only need to select the center point and the edge of the gear's tooth.
- [ ] Add a length parameter for the rack tooth base.

If you'd like to help, feel free to send me a script for any of these goals, and I'll include it in my script. I'm also open to suggestions!
