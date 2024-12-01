# Chapter 8: Code Generation

### **1. Issues in Code Generator Design**

- **What are the issues in the design of a code generator?***[2020, 2016, 2014, 2013, 2011]*
- **Or, Illustrate the issues in the design of a code generator.***[2018]*
- **Or, How would you solve the issues in the design of code generators?***[2017]*
- **Or, Explain the problems in code generation.***[2016]*

---

### **2. Directed Acyclic Graph (DAG)**

- **What is DAG? What are the applications of DAG? Write the algorithm for constructing a DAG.***[2021, 2018, 2015, 2013, 2011]*

---

### **3. Basic Blocks and Flow Graphs**

- **What do you mean by basic blocks and flow graphs?***[2015]*

---

### **4. Transformations on Basic Blocks**

- **Describe the structure-preserving transformations on a basic block.***[2016, 2013, 2011]*

---

### **5. Simplifications**

- **Draw a DAG for the following basic block:**
    
    ```
    iota := b + c
    b := a - d
    c := b + c
    d := a - d
    
    ```
    
    *[2020, 2018]*
    
- **What is DAG? Construct the DAG for the following basic block:**
    
    ```
    D := B^ * C
    E := A + B
    B := B^ * C
    A := E - D
    
    ```
    
    *[2016]*
    
- **Define DAG. Construct a DAG and discover the sequence of instructions for:**
    
    ```
    a + a^ * (b - c) + (b - c) * d
    
    ```
    
    *[2017]*
    
- **Construct the syntax tree and DAG for the expression:**
    
    ```
    11 = b^ * -c + b^ * -c
    
    ```
    
    *[2015, 2014]*
    
- **Prepare and eliminate the common sub-expression from the basic block:**
    
    ```
    iota := b + c
    b := a - d
    c := b + c
    d := a - d
    
    ```
    
    *[2017]*
    

---