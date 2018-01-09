## usefulpythoncommands

[![Join the chat at https://gitter.im/usefulpythoncommands/Lobby](https://badges.gitter.im/usefulpythoncommands/Lobby.svg)](https://gitter.im/usefulpythoncommands/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
usefulpythoncommands is a list of useful python commands

### Python Code:
* End script at this point        
    ```python
    raise Systemexit
    ```
* Variable string in one line
    ```python
    s = ("" if iterationcount == 1 else "s")
    ```
* Combining multiple strings
    ```python
    test = ['I', 'Like', 'Python', 'automation']
    print ''.join(test)
    ```
* Set recursion limit (default 1000)
    ```python
    import sys
    sys.setrecursionlimit(1001)
    ```
* List comprehensions for multidimensional arrays
    ```python
    [[a, b, c] for a in range(x + 1)
               for b in range(y + 1)
               for c in range(z + 1)
               if a + b + c != n]
    ```
   

### Pip:
* List all packages
    ```CLI
    pip freeze
    ```
* Update all packages
    ```CLI
    pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U
    ```
