# morsecode-py
Package for Python made by me.

# Documentation
This package translates from text to morse code and viceversa.
Here's a basic example:
```python
from morsecode import morse

m = morse(lettercase='upper')

text = input('Write here something: ')

e = m.encode(text)

print(e, m.decode(e))
```
**Output**
```python
.... . .-.. .-.. ---  HELLO 
```

**class morse(lettercase='upper')**
The *lettercase* variable has just two answers: **upper** or **lower**.
This is for get the decoded text in uppercase or lowercase.

**morse.encode(string or int)**
With this command you encode any text to morse code.

**morse.decode(string or int)**
With this command you decode any morse code to text.
