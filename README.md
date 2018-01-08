## usefulpythoncommands
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
### Pip:
* List all packages
    ```CLI
    pip freeze
    ```

* Update all packages
    ```CLI
    pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U
    ```
