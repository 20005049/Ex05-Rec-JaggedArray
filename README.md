# Ex05-Rec-JaggedArray
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## Algorithm:
### Step 1:
Start the C# program in visual studio 2022.


### Step 2:
Declare a Jagged Array for four element.


### Step 3:
Initialize the elements.


### Step 4:
Accessing the elements.


### Step 5:
Accessing the elements.


### Step 6:
Take the screenshot of the output of the program.

## Program:

```
using System;
class CPUactivity
{
    public static void Main(String[] args)
    {
        int[][] array = new int[4][];
        array[0] = new int[3];
        array[1] = new int[5];
        array[2] = new int[6];
        array[3] = new int[4];
        for(int i=0; i<4; i++)
        {
            for(int j=0; j<array[i].Length; j++)
            {
                array[i][j] = i*j+70;
            }
        }
        for(int i=0; i<array.Length; i++)
        {
            for(int j=0;j<array[i].Length; j++)
            {
                Console.WriteLine("CPU usage at node"+ i +" is "+ array[i][j]+"%");
            }
            Console.WriteLine();
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/75241366/167247167-3add923e-2b5e-4d35-83ea-c00fba3117e5.png)


## Result:
Thus, the C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
