# Notes for my personal wiki application

Pushes will trigger webhook to [personal-wiki](https://github.com/conormag94/personal-wiki)

Categories can be added by putting the note in a folder, **e.g.** `git/some-note.md`

**Some sample code**
```
@requires_authorization
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1 + 0b10l) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
```

```
l = [1, 2, 3]
r = l[::-1]
```

```
$ some_command.sh
```