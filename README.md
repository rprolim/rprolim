```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class PhysicsStudent:

  def __init__(self):
    self.name = 'Raphael Rolim'
    self.nation = 'Brazil'
    self.role = 'Undergraduate Student'
    self.research = 'Cosmology'
    self.member = 'BINGO/ABDUS radio-telescope'
    self.language_computer = ['Python', 'C++', 'SQL']
    self.language_real = ['pt_BR', 'en_US']
    self.loves = {'Book':'Dune', 'Movie':'Star Wars', 'Food':'Sfiha'}
    
  def says_hy(self):
    print('Hello there!')

me = PhysicsStudent()
me.says_hy()
```
