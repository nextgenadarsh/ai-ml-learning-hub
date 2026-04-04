# Module 00: Python Fundamentals for AI/ML

## Overview
Complete Python foundation module designed specifically for AI/ML engineering. No prerequisite programming knowledge required.

## Learning Objectives
By completing this module, you will:
- Understand Python syntax, data types, and operators
- Master control flow and functions
- Work with data structures (lists, dicts, sets, tuples)
- Apply object-oriented and functional programming
- Handle files, errors, and debugging
- Use NumPy for numerical computing
- Create visualizations with Matplotlib
- Set up Python environments for ML development

## Module Structure

### 1. **Python Fundamentals** (01-python-fundamentals.ipynb)
**Duration**: 4-5 hours | **Exercises**: 5

Master core Python concepts needed for every programmer.

**Topics**:
- Variables and data types (int, float, str, bool, None)
- Operators (arithmetic, comparison, logical)
- Control flow (if/elif/else, for loops, while loops)
- Functions (definition, parameters, return values)
- *args and **kwargs for variable arguments
- Variable scope (local, global)
- String operations and formatting

**Key Concepts**:
- Python's dynamic typing system
- Indentation-based syntax
- Function definition and scope rules
- F-strings for formatting

**Exercises**:
1. Create a number checker function (even/odd)
2. Implement factorial calculation
3. Build string reversal function
4. Count vowels in text
5. Temperature unit converter

---

### 2. **Data Structures** (02-data-structures.ipynb)
**Duration**: 4-5 hours | **Exercises**: 5

Essential collections for data manipulation.

**Topics**:
- Lists (creation, indexing, slicing, methods)
- Tuples (immutability, unpacking)
- Dictionaries (key-value pairs, methods)
- Sets (unique items, operations)
- List/dict/set comprehensions
- Nested data structures
- List vs tuple vs dict when to use each

**Key Concepts**:
- Mutable vs immutable types
- Comprehensions for clean code
- Dictionary as data container
- Set operations (union, intersection, difference)

**Exercises**:
1. Remove duplicates from list (preserve order)
2. Invert dictionary (keys ↔ values)
3. Merge lists and return unique items
4. Group list of dictionaries by key
5. Flatten nested lists

---

### 3. **Object-Oriented & Functional Programming** (03-oop-functional.ipynb)
**Duration**: 5-6 hours | **Exercises**: 5

Design code using both programming paradigms.

**Topics**:
- Classes and objects (attributes, methods)
- Constructors and instance methods
- Class methods and static methods
- Inheritance and polymorphism
- Encapsulation (public, protected, private)
- Lambda functions
- Map, filter, reduce
- Decorators (basics)
- ML-relevant class example

**Key Concepts**:
- Object-oriented design principles
- Inheritance hierarchies
- Functional programming style
- Method overriding and polymorphism
- Properties and methods

**Exercises**:
1. Student class with GPA calculation
2. Vehicle inheritance hierarchy
3. Logging function decorator
4. Map/filter for data transformation
5. DataProcessor class for pipelines

---

### 4. **File I/O and Debugging** (04-file-io-debugging.ipynb)
**Duration**: 4-5 hours | **Exercises**: 5

Read/write data and debug effectively.

**Topics**:
- Reading and writing text files
- CSV file operations
- JSON serialization/deserialization
- Error handling (try/except/finally)
- Custom exceptions
- Debugging techniques (print, assert, logging)
- Logging module configuration
- Context managers and 'with' statement
- File system operations (os, pathlib)

**Key Concepts**:
- EAFP (Easier to Ask for Forgiveness than Permission)
- Exception hierarchy
- Logging vs print debugging
- Context managers for resource management

**Exercises**:
1. CSV reader for data extraction
2. Robust JSON configuration loader
3. Custom validation exception class
4. Logging to console and file
5. Mock database context manager

---

### 5. **Python for Machine Learning** (05-python-for-ml.ipynb)
**Duration**: 5-6 hours | **Exercises**: 5

NumPy, Matplotlib, and ML best practices.

**Topics**:
- NumPy arrays (creation, indexing, slicing)
- NumPy operations (element-wise, aggregation)
- Linear algebra (matrix operations, eigenvalues)
- Random number generation
- Matplotlib line plots and scatter plots
- Multiple subplots
- Virtual environments (venv, pip)
- Type hints for code clarity
- Documentation (docstrings)
- Configuration management

**Key Concepts**:
- NumPy vectorization for efficiency
- Broadcasting rules
- Type hints improve IDE support
- Virtual environments isolate dependencies
- Configuration objects for experiments

**Exercises**:
1. NumPy array statistics computation
2. Matrix multiplication verification
3. Multi-function Matplotlib visualization
4. Virtual environment setup
5. Type-hinted preprocessing function

---

## Learning Progression

**Recommended Order**:
1. Start with **Fundamentals** - establish core Python knowledge
2. Move to **Data Structures** - learn to organize data
3. Study **OOP/Functional** - understand design patterns
4. Learn **File I/O** - work with real data
5. Complete **Python for ML** - apply to ML context

## Time Estimates
- **Total Module Duration**: 23-27 hours
- **Per Notebook**: 4-6 hours (including exercises)
- **All Exercises**: 2-3 hours additional practice

## Prerequisites
- ✅ No programming experience required
- ✅ Computer with Python 3.8+ installed
- ✅ Text editor or IDE (VS Code recommended)
- ✅ Willingness to experiment

## Success Criteria
After this module, you should be able to:
- ✅ Write well-structured Python programs
- ✅ Handle different data types and structures effectively
- ✅ Use both OOP and functional programming styles
- ✅ Read/write various file formats
- ✅ Debug code efficiently
- ✅ Perform numerical computations with NumPy
- ✅ Create basic visualizations
- ✅ Set up proper development environments

## Next Steps
After completing this module, proceed to:
- **Module 01: ML Fundamentals** - Core ML concepts (supervised learning, classification)
- **Module 02: Algorithms** - Mathematical foundations (linear algebra, neural networks)
- **Module 03: Data Engineering** - Data processing at scale

## Resources

### Books
- "Python Crash Course" by Eric Matthes
- "Fluent Python" by Luciano Ramalho
- "Think Python" by Allen Downey

### Online Resources
- [Official Python Documentation](https://docs.python.org/3/)
- [NumPy User Guide](https://numpy.org/doc/stable/user/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Real Python](https://realpython.com/)

### Practice Platforms
- [LeetCode](https://leetcode.com/) - Algorithm practice
- [HackerRank](https://www.hackerrank.com/) - Python challenges
- [Codewars](https://www.codewars.com/) - Code kata

## Tips for Success

### Best Practices
1. **Code Along**: Type every example, don't just read
2. **Modify Examples**: Change values and parameters to understand behavior
3. **Read Error Messages**: They're helpful debugging information
4. **Use Type Hints**: Improves code quality and IDE support
5. **Write Docstrings**: Document your functions properly

### Common Mistakes to Avoid
- ❌ Skipping exercises - they're essential
- ❌ Copying without understanding
- ❌ Not testing edge cases
- ❌ Ignoring error messages
- ❌ Writing code without comments

### Challenge Yourself
- Write functions from scratch
- Combine concepts from multiple notebooks
- Solve the same problem in different ways
- Review and refactor old code

## Feedback and Questions
If you have questions or suggestions:
1. Review the material again - concepts often click on second reading
2. Check online resources - others likely had same questions
3. Try different approaches - often multiple solutions exist
4. Document what you learn - teaching others helps you learn

---

**Happy Learning!** 🚀

This module is your foundation for everything that follows. Invest time here to understand core concepts deeply.
