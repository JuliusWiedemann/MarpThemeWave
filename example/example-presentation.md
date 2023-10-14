---
marp: true
theme: wave
header: "This is the header of the presentation"
footer: "This is the footer of the presentation"
paginate: true
transition: fade 0.3s
---

<!-- 
_header: ""
_footer: ""
_paginate: false 
-->

# Wave Theme 🌊
### Custom theme "wave" for the marp presentation framework

---

## Basic bullet point slide
- irmod tempor invidunt
- ut labore et dolore magna aliquyam erat
- sed diam voluptua. At vero eos et accusam
- et justo duo dolores et ea rebum

---

## Basic bullet point slide with image
- irmod tempor invidunt
- ut labore et dolore magna aliquyam erat
- sed diam voluptua. At vero eos et accusam

![bg right:40% width:400](icon.png)

---

## Bullet point comparison slide

<div class = "columns">
<div>

#### Part 1
- Lorem ipsum 
- consetetur sadipscing
- eirmod tempor

</div>
<div>

#### Part 2
- Stet clita kasd gubergren
- At vero eos 

</div>
</div>

---

Text | Text | Text | Text 
-----|------|------|------
Text | Text | Text | Text  
Text | Text | Text | Text  
Text | Text | Text | Text    

---

<!-- 
_header: ""
_footer: "" 
-->
![bg left:25% width:200](icon.png)
_Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At ve_

---

# Big image with text
![bg right width:500px](./icon.png)


---

## Python Code
```python
class MyPerson:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age

    def getName(self):
        return self.name

mike = MyPerson("Mike", 20, "m")
print(mike.getName())
```

---

## Shell
```
PS C:\repository\ pylint main.py

--------------------------------------------------------------------
Your code has been rated at 10.00/10 (previous run: -2.50/10, +12.50) 
```

---

## Large c code block
```c
#include <stdio.h>

int main() {
  // get no. of terms from user
  printf("Enter the number of terms: ");
  scanf("%d", &n);

  // print 3rd to nth terms
  for (i = 3; i <= n; ++i) {
    printf("%d, ", nextTerm);
    t1 = t2;
    t2 = nextTerm;
    nextTerm = t1 + t2;
  }

  return 0;
}
```
