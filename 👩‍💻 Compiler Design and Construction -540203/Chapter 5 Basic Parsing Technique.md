# Chapter 5: Basic Parsing Technique

### **1. Parser Definition and Parsing Types**

- **Define parser. What are the differences between top-down and bottom-up parsers?***[2016]***Or**,**What do you mean by parsing? Differentiate between top-down parsing and bottom-up parsing.***[2019, 2010]*

### **2. Top-Down Parsing**

- **Define top-down parsing. What are the problems of top-down parsing?***[2012]*

### **3. Shift-Reduce Parsing**

- **What is a shift-reduce parser? What are the actions allowed in a shift-reduce parser?***[2011]***Or**,**What do you mean by shift-parsing? What are the four possible actions of a shift-reduce parsing?***[2021, 2012]*

### **4. Predictive Parser and Handle Pruning**

- **Define parser, predictive parser, and handle pruning.***[2012]*
- **What is a predictive parser? Explain the model of a predictive parser.***[2015]*

### **5. Operator Precedence Parsing**

- **How can you find the handle from operator precedence parsing?***[2020, 2017, 2014, 2012]*
- **List the advantages and disadvantages of operator precedence parsing.***[2011]*
- **What is operator precedence parsing?***[2021]*

### **6. LR Parsing**

- **What is an LR parser? Explain the function values of the ACTION function in an LR parser.***[2015, 2012]*
- **What is an LR parser? Write down its importance.***[2014, 2009]*

### **7. Handle and Handle Pruning**

- **Explain handle and handle pruning.***[2015, 2016]***Or**,**What do you mean by handle pruning? Explain with the help of an example.***[2018]*

### **8. FIRST and FOLLOW**

- **Write the rules for FIRST and FOLLOW.***[2017, 2013]*

---

### Simplifications

### **9. Shift-Reduce Parsing Actions**

- **Consider the following grammar:Show the shift-reduce parsing actions in the stack for the input string `id1 + id2 * id3`.***[2021, 2020, 2019, 2016, 2014, 2011]***Or**,**Configure a shift-reduce parser for the input string `id1 + id2 * id3` with the following grammar:***[2018]*
    
    ```
    E → E + E | E * E | (E) | id
    
    ```
    
    ```
    E → E + E | E * E | (E) | id
    
    ```
    

### **10. Left Recursion Elimination**

- **Write the rule to eliminate left recursion in a grammar. Prepare and eliminate left recursion for the grammar:***[2017]*
    
    ```
    S → A a | b
    A → A c | S d | t
    
    ```
    

### **11. Top-Down Parsing Problems**

- **What are the main problems of top-down parsing?**
    - **Consider the grammar:Is there any problem in this grammar for top-down parsing? Eliminate the problem if any.***[2021, 2014, 2011]*
        
        ```
        E → E + T | T
        T → T * F | F
        F → (E) | id
        
        ```
        
    - **Or**,**Eliminate the immediate left recursion for the following grammar:***[2019, 2016, 2009]*
        
        ```
        E → E + T | T
        T → T * F | F
        F → (E) | id
        
        ```
        

### **12. Left Factoring**

- **What do you mean by left factoring for recursive-descent parsing?**
    - **Consider the following grammar:Left factor the above grammar.***[2020, 2019, 2017, 2015, 2012]*
        
        ```
        S → i C t S | i C t S e S | a
        C → b
        
        ```
        

### **13. Finding FIRST and FOLLOW**

- **Find FIRST and FOLLOW for the following grammar:***[2021, 2020, 2018, 2015, 2009]*
    
    ```
    E → T E'
    E' → + T E' | ε
    T → F T'
    T' → * F T' | ε
    F → (E) | id
    
    ```
    

---