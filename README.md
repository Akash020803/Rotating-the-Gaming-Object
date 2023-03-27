# Rotating the Gaming Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step 1:
&emsp;Start
### Step 2:
1. Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Exp1)
### Step 3:
1. Click Hierarchy -> 3DObject -> Cylinder
2. Hierarchy -> 3DObject -> Capsule
3. Hierarchy -> 3DObject -> Text
4. Hierarchy -> Effects -> Particle system
### Step 4:
1. Create a folder in project and name as Materials
2. Material folder -> Create -> Material (Name: Capsule)
3. Inspector ->Surface Inputs ->BaseMAp (Choose the color)
4. Drag the Cylinder to the plane and release the mouse


### Step 5:
1. Click Hierarchy -> DirectionalLight
2. Inspector -> Change the color to white (255,255,255)

### Step 6:
&emsp;Create a folder name Coding and create a C# file to add the coding in it.

### Step 7:
&emsp;To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Step 8:
&emsp;Stop

## Program:
```
Developed by: Akash A
Register Number: 212221230003
```
### Rotate Text:
```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class prog1 : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.right, Vector3.down, 90 * Time.deltaTime);
    }
}

```
### Rotate Objects:
```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class prog2 : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.left, Vector3.up, 120 * Time.deltaTime);
    }
}

```
## Output:
![image](https://user-images.githubusercontent.com/94177474/227997374-2b6cd50c-8cf6-4c53-bef2-11b83d546425.png)

https://user-images.githubusercontent.com/94177474/227998064-2568ad71-b13b-44a6-a4da-1950280a8afc.mp4


## Result:
Thus a 3D application for rotating the gaming objects in unity is developed successfully.
