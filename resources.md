# Resources

- [Closing Issues on GitHub Using Keywords](https://help.github.com/articles/closing-issues-using-keywords/)
- [flake8](https://medium.com/python-pandemonium/what-is-flake8-and-why-we-should-use-it-b89bd78073f2)
- [doctest](https://docs.python.org/3.7/library/doctest.html)
- [Numpy docstrings](https://numpydoc.readthedocs.io/en/latest/example.html#example)
- [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008/)

---

#### doctest 
- reference:  https://docs.python.org/3.7/library/doctest.html#doctest.ELLIPSIS
- explanation:  https://github.com/scikit-learn/scikit-learn/pull/12799#discussion_r242147232

---

#### `flake8` Formatting Tests
Can install using `pip` or `conda`:  

>my example
```python
conda install flake8 
```

### Running `flake8`
`flake8` <filename.py>

>my example
```bash
flake8 /Users/reshamashaikh/scikit-learn/sklearn/metrics/scorer.py
```

When there are formatting issues, here's an example of what it will return:  

>my example
```bash
(sklearndev) % flake8 scorer.py
scorer.py:186:39: E225 missing whitespace around operator
scorer.py:189:80: E501 line too long (85 > 79 characters)
scorer.py:190:80: E501 line too long (87 > 79 characters)
```



