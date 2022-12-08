<h1><strong><span style="color: #77C8D5;">STUDENT VERSION (TW-5)</strong></span>

![logo](teamwork_logo.png)

<br>
<br>
<br>
<br>
<br>
<br>

<h1><strong><span style="color: #3498DB;">Meeting Agenda</strong></h1></span>

<span class="c16 c30">▶ </span><span
class="c42 c82">Icebreaking</span><span class="c16 c23"> </span>

<span class="c16 c30">▶ </span><span
class="c42 c82">Questions</span><span class="c46 c42 c48"> </span>

<span class="c16 c30">▶ </span><span
class="c46 c48 c42">Interview Questions</span>

<span class="c16 c30">▶ </span><span
class="c46 c48 c42">Coffee Break</span>

<span class="c16 c30">▶ </span><span class="c23 c16">Video of the
week</span>

<span class="c16 c30">▶ </span><span class="c23 c16">Retro
meeting</span>


<br>
<br>
<br>

<h1><strong><span style="color: #3498DB;">Teamwork Schedule</strong></h1></span>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Ice-breaking</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

- Personal Questions (Stay at home & Corona, 
Study Environment, Kids etc.) 
- Any challenges (Classes, Coding, studying, etc.) 
- Ask how they’re studying, give personal advice. 
- Remind that practice makes perfect. 

<br>
<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Ask Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>30m</p><td>                </tr>
</table>

<br>

**1. What will be the output of the following Python code?**

```bash
def printMax(a, b):
    if a > b:
        print(a, 'is maximum')
    elif a == b:
        print(a, 'is equal to', b)
    else:
        print(b, 'is maximum')
printMax(3, 4)
```
<strong>A.</strong>  3<br>
<strong>B.</strong> 4<br>
<strong>C.</strong>  4 is maximum<br>
<strong>D.</strong> 3 is maximum


<br>

**2. What is the output of the following program?**

```bash
x = 50
def func(x):
    print('x is', x)
    x = 2
    print('Changed local x to', x)
func(x)
print('x is now', x)
```

<strong>A.

```bash
x is 50
Changed local x to 2
x is now 50
```

<strong>B.

```bash
x is 50
Changed local x to 2
x is now 2
```

<strong>C.

```bash
x is 50
Changed local x to 2
x is now 100
```
<strong>D.</strong> None of the mentioned


<br>

**3. What will be the output of the following Python code snippet?**

```bash
def function1(var1=5, var2=7):
    var2=9
    var1=3
    print (var1, " ", var2)
function1(10,12)
```

<strong>A.</strong> 5 7<br>
<strong>B.</strong>  3 9<br>
<strong>C.</strong>  10 12<br>
<strong>D.</strong>  error
<br>


<br>

**4. What is called when a function is defined inside a class?**

<strong>A.</strong> Module<br>
<strong>B.</strong>  Method<br>
<strong>C.</strong>  Class <br>
<strong>D.</strong>  Another function
<br>


<br>

**5. What is the purpose of the “def” keyword in Python?**

<strong>A.</strong>  It is slang that means "the following code is really cool"<br>
<strong>B.</strong>  It indicates the start of a function<br>
<strong>C.</strong>  It indicates that the following indented section of code is to be stored for later<br>
<strong>D.</strong>    b and c are both true
<br>


<br>


**6. What will be the output of the following Python code?**

```bash
def san(x):
    print(x+1)
x=-2
x=4
san(12)
```
<strong>A.</strong> 13<br>
<strong>B.</strong> 10<br>
<strong>C.</strong> 2<br>
<strong>D.</strong> 5


<br>

**7. What is the output of the following program?**

```bash
def foo(fname, val):
    print(fname(val))
foo(max, [1, 2, 3])
foo(min, [1, 2, 3])
```

<strong>A.

```bash
3
1
```

<strong>B.

```bash
1
3
```

<strong>C.

```bash
1
1
```
<strong>D.

```bash
3
2
```


<br>

**8. What will be the output of the following Python code snippet?**


```bash
f=lambda x:bool(x%2)
print(f(20), f(21))
```

<strong>A.</strong>  False True<br>
<strong>B.</strong>  False False<br>
<strong>C.</strong>  True True<br>
<strong>D.</strong>     True False
<br>


<br>

**9. What will be the output of the following Python code?**

```bash
random.randrange(0,91,5)
```
<strong>A.</strong> 10<br>
<strong>B.</strong> 18<br>
<strong>C.</strong> 79<br>
<strong>D.</strong> 95


<br>

**10. What is the output of the following program?**

```bash
def foo():
    try:
        return 1
    finally:
        return 2
k = foo()
print(k)
```
<strong>A.</strong> 8<br>
<strong>B.</strong> 6<br>
<strong>C.</strong> 4<br>
<strong>D.</strong> 2


<br>


**11. What will be the output of the following Python code?**

```bash
def f(x, y, z): return x + y + z
print(f(2, 30, 400))
```
<strong>A.</strong> 431<br>
<strong>B.</strong> 432<br>
<strong>C.</strong> 230400<br>
<strong>D.</strong> 2212


**12. What will be the output of the following Python code?**

```bash
print({a**2 for a in range(4)})
```
<strong>A.</strong> {1, 4, 9, 16}<br>
<strong>B.</strong>  {0, 1, 4, 9, 16}<br>
<strong>C.</strong> {0, 1, 4, 9}<br>
<strong>D.</strong> Error


<br>

**13.  What will be the output of the following Python code?**

```bash
a=[1,2,3,4]
b=[sum(a[0:x+1]) for x in range(0,len(a))]
print(b)
```
<strong>A.</strong>  10<br>
<strong>B.</strong>   [1,3,5,7]<br>
<strong>C.</strong> [1,3,6,10]<br>
<strong>D.</strong>  8


<b>

<b>
<b>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>15m</p><td>                </tr>
</table>

<b>

**1. How can I make a tuple out of a list?**
 



<br>

**2.  What is the Python data type SET, and how can I use it?**


<br>
<br>
<hr><hr>


 :coffee: 
<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Coffee Break</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

:coffee:
<br>
<hr><hr>
<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>ADDITIONAL RESOURCES/td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

- [Workshop-3(student)](https://github.com/clarusway/DS-1322-EU-DA-Module-Students/blob/main/2-%20Weekly%20Agendas/Week%205/Workshop-3(student).ipynb)

<br>
<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>20m</p><td>                </tr>
</table>

- [How to google](https://www.youtube.com/watch?v=xD0jkUCJFr8&list=PL6Mbwnna00j28LCaMBUQ_4u6BNGrYnJfg)



<br>
<hr>

<table style= "width:97%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Retro Meeting on a personal and team level</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

Ask the questions below:

- What went well? 
- What could be improved? 
- What will we commit to do better in the next week? 


<br>
<hr>

<table style= "width:105%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Closing</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                   </tr>
</table>

- Next week’s plan

- QA Session 

<hr>
