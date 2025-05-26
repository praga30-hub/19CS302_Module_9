# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.

## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to display queue elements using array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
      

## Program:
```

int size=10,rear=-1,front=-1;
char queue[50];
void enqueue(char data)
{
    if(front==-1)
    {
        front=0;
    }
    rear++;
    queue[rear]=data;
}void display()
{
    for(int i=front;i<=rear;i++)
    {
     printf("%.1f ",queue[i]);
    }
    if(front>rear)
    {
     printf("No elements to display\n");
    }
}
```

## Output:

![image](https://github.com/user-attachments/assets/24283981-a133-4c56-9e2f-24cd0a22be97)


## Result:
Thus the program was executed and the output was verified successfully.
