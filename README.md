# program-5d
# 🧪 C Programming Lab
## 📘 Experiment No: 5d
### 🔹
**Date:** 29/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
To write a c program to count the number of alphabets in a given string.
---

## 🧠 ALGORITHM
1.Get a string as an input fromm the user.
2.Count the number of alphabets in the string using for loop.
3.print the result using printf() function.
---

## 💻 PROGRAM
```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[100];
    int count=0;
    fgets(str,sizeof(str),stdin);
    for(int i=0;str[i]!='\0';i++)
    {
        if((str[i]>=60&&str[i]<=90)||(str[i]>=97&&str[i]<=122))
        count++;
    }
    printf("Number of Alphabets in the string is : %d",count);
}
```

## 🖼️ OUTPUT SCREENSHOT

<img width="810" height="82" alt="image" src="https://github.com/user-attachments/assets/2ed7989e-d8b5-46ed-a324-e2bdbe6bd657" />


---

## ✅ RESULT
Thus the C program to count the number of alphabets in the given string is executed successfully.
