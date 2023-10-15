# Ex05-Rec-JaggedArray

## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.

## Algorithm:
### Step1:
Create a new Class named cpu.

### Step 2:
Create a jagged array of 4 arrays.

int[][] array = new int[][];

### Step 3:
Create as many sub-nodes as you wish inside one node of jagged array.

### Step 4:
Give the sample CPU usage in the jagged array.

### Step 5:
Print the sample CPU usage in the jagged array.

### Step 6:
End the Program.


## Program:
Developed by : KAVIYA SHREE S

Register number : 212222110018

```
using System;
class jaggedarray
{
    public static void Main(String[] args)
    {
        int[][] array = new int[4][];
        array[0] = new int[3];
        array[1] = new int[5];
        array[2] = new int[6];
        array[3] = new int[4];
        for (int i = 0; i < 4; i++)
        {
            for (int j = 0; j < array[i].Length; j++)
            {
                array[i][j] = i * j + 70;
            }
        }
        for (int i = 0; i < array.Length; i++)
        {
            for (int j = 0; j < array[i].Length; j++)
            {
                Console.WriteLine("CPU usage {0} is {1} %" , i + 1, array[i][j]);
            }
            Console.WriteLine();
        }
    }
}
```


## Output:
![1](https://github.com/Leann4468/Ex05-Rec-JaggedArray/assets/121165979/7e9b19f1-18ff-4a99-b9f0-9edd016627ad)

## Result:
C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
