# Chapter 4: Syntax Analysis

### **1. Ambiguous Grammar**

- **What is ambiguous grammar? Explain with an example.***[2018]* **Or**, **What is ambiguity? Explain with an example.***[2015]***Or**, **What do you mean by the ambiguity of grammar? Explain with an example.***[2011]*

### **2. Error Detector/Corrector**

- **Describe the plan of an error detector/corrector with a figure.***[2017, 16]***Or**,**Draw the figure of error detector and corrector. What are semantic errors? Explain with an example.***[2012]*

### **3. Error-Recovery Strategies**

- **Explain the error-recovery strategies.***[2016]*

### **4. Panic Mode Error Recovery**

- **Describe the panic mode error recovery strategy. What are the lexical error recovery actions?***[2009]*

### **5. Error Diagnostics**

- **What are the properties of good error diagnostics?***[2018, 15, 13, 12, 11]*

### **6. Sources of Errors**

- **Describe the sources of errors.***[2020, 15, 13]*

---

### Simplification

### **7. Ambiguity Check for Grammar**

- **Consider the following grammar for arithmetic expressions involving `+`, →``, *``, `/`: Is it an ambiguous grammar? Justify your answer.***[2020, 17]*
    
    ```
    E → E + E | E - E | E * E | E / E
    E → (E) | id
    
    ```
    

### **8. Parse Tree Construction**

- **Consider the following grammar:***(Here `i`, `t`, and `e` stand for `if`, `then`, and `else`, and `C` and `S` for "conditional" and "statement".)***Construct a parse tree for the sentence `w = i b t i b t a e a` using leftmost derivation and rightmost derivation.***[2019, 17, 14]*
    
    ```
    S → iC t S e S | i C t S | a | b
    
    ```
    

### **9. Ambiguity Check with Example**

- **Consider the following grammar: Is it an ambiguous grammar? Justify your answer.***[2019]*
    
    ```
    E → E + E | E * E | (E) | id
    
    ```
    

---