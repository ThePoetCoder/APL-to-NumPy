# APL-to-NumPy
Converting APL primitives into executable NumPy

This project is an ode to good code. I am blown away by how powerful and sensible APL is as a language. As soon as I saw the Primer of [tryapl.org](tryapl.org) and the innate usefulness of each glyph, I knew I needed this functionality in my daily language of Python, and set to work translating APL to NumPy.

Here, every one of the APL primitives has been translated to executable Python / NumPy expressions and functions. In addition, I tried to use the exact same examples seen on tryapl.org as tests for my code. Not only does this allow you to take a look at the way these operators and functions would be implemented in Python, it also allows you to quantify exactly how many more characters / complexity you would need to type out in Python to express the same operations and transformations.

Each cell has the same basic structure, with the APL code up top and commented out while the Python / NumPy code is at the bottom being executed:

```
#------------------------
# Example Cell Structure
#------------------------

#       {APL Code Example}
# {APL Output}

numpy_code_example = "Numpy Code Input"
numpy_code_example = numpy_code_example.replace("Input", "Output")
numpy_code_example
```

'Numpy Code Output'

