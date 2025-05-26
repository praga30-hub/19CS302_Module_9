# EX 42 C program to write a fuctions to perform push,pop,display,peek in stack using array.

## AIM:
To write a fuctions to perform push,pop,display,peek in stack using array.

## Algorithm
1. Start.
2. Define a variables.
3. Write a functions to perform push,pop,display,peek in stack using array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End
     

## Program:
```
int stack[100];
int size=3,top=-1,i; 
void push (float data)
{
if(top==size-1)
{
printf("stack is full\n");
}
else{ 
top=top+1;
stack[top]=data;}
} void display(){
for(i=top; i>=0; i--){
printf("%d ",stack[i]);
}
if(top==-1)
{
printf("stack is empty\n");
}
Void pop()
{
if(top==-1)
{
printf("stack is empty\n");
}
else{
top=top-1;
}
}
void peek()
{
printf("%d ",stack[top]);
}

```

## Output:
![image](https://github.com/user-attachments/assets/a08ed9a1-b757-4c3c-8104-2c5d125218aa)



## Result:
Thus the program was executed and the output was verified successfully.
