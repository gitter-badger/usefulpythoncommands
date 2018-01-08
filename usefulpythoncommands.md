# usefulpythoncommands
## Python Code:
* End script at this point        
```python
        raise Systemexit
```

## Pip:
* List all packages
```CLI
        pip freeze
```

* Update all packages
```CLI
        pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U
```
