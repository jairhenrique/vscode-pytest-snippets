# PYTEST SNIPPETS FOR VSCODE

## List of snippets

### praises
```python
with pytest.raises(Exception):
    pass
```


### fixture
```python
@pytest.fixture
def name(request):
    pass
```

### mark
```python
@pytest.mark
```

### parametrize
```python
@pytest.mark.parametrize('foo', ['bar'])
```

### a==
```python
assert 1 == 1
```

### afalse
```python
assert False is False
```

### atrue
```python
assert True is True
```

### a>
```python
assert 2 > 1
```

### a>=
```python
assert 1 >= 1
```

### ain
```python
assert 'a' in ['a']
```

### anotin
```python
assert 1 not in [2]
```

### ais
```python
assert 1 is 1
```

### aisnot
```python
assert 'a' is not 1
```

### a<
```python
assert 1 < 2
```

### a<=
```python
assert 1 <= 1
```

### a!=
```python
assert 1 != 2
```