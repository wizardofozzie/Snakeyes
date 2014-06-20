Snakeyes
========

A simple code-completion system for Pythonista  

Currently a work-in-progress, Snakeyes is a code-completion system for Pythonista. When the script is run, presumably from the action menu, it checks the last three characters typed to see if they are one of the assigned keywords:  
1. def (define)  
2. ifc (if condition)  
3. wlt (while less than)  
4. fea (for entry array)  

Their respective completions are:  

```python  
def func_name():  
```  
  
```python  
if condition:  
```  
  
```python  
while i < num:  
```  
  
```python
for entry in array:  
```  
  
Snakeyes automatically highlights the filler words in the autocompletion text.

Because Snakeyes is a work-in-progress, help with this project through pull requests is greatly appreciated.
