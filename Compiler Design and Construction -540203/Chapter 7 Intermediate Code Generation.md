# Chapter 7: Intermediate Code Generation

---

### **1. Three-Address Code**

- **What do you mean by three-address code? What is the implementation method of three-address code? Describe with an example.***[2020, 2018, 2014, 2011, 2009]*
- **Or, What do you mean by three-address code? Describe with an example.***[2013]*
- **Or, Explain the three-address code with an example.***[2017]*

---

### **2. Machine Independent Intermediate Code**

- **What are the advantages of machine-independent intermediate code?***[2012, 2009]*
- **Or, What are the benefits of machine-independent intermediate code?***[2019]*

---

### **3. Quadruples vs. Triples**

- **Write down the advantages and disadvantages of quadruples over triples.***[2015]*

---

### **4. Simplifications**

- **Translate the arithmetic expression `[a + a^ * (b - c)] + [(b - c)^ * d]` into:**
    
    *(i) Three-address code*
    
    *(ii) Quadruples*
    
    *(iii) Triples*
    
    *[2016, 2010]*
    
- **Write quadruples, triples, and indirect triples for the expression `(a + b) + (c + d) - (a + b + c)`.**
    
    *[2015]*
    

---

### **5. Code Generation**

- **The assignment `d := (a - b) + (a - c) + (a - c)` might be translated into the following three-address code sequence:**
    
    ```
    t := a - b
    u := a - c
    v := t + u
    d := v + u
    
    ```
    
    - **With `d` live at the end, what are the code sequences for the above three-address code using the code generation algorithm?***[2014]*

---

### **6. Target Code Cost**

- **Prepare the total cost of the following target code:***[2017]*
    
    ```
    MOV a, R0
    ADD b, R0
    MOV c, R0
    ADD R0, R1
    MOV R1, X
    
    ```
    

---

### **7. Expression Translation**

- **What do you mean by three-address code? Translate the following arithmetic expression `a := b^ * -c + b^ * -c` into:***(i) Quadruples(ii) Triples(iii) Indirect Triples[2021, 2019]*

---

This format organizes the questions into clear sections for better navigation and understanding. Let me know if you need any further refinements!