# Python-Projects-Acronym-Generator 🐍
This repo contains python code that generates an acronym from a phrase.<br>
Run the code.


Python
```python
user_input = str(input("Enter a Phrase: "))
text = user_input.split()
a = " "
for i in text:
    a = a+str(i[0]).upper()
print(a)

```

Output
```python
Enter a Phrase: hello world
 HW
```
