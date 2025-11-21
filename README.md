# 🌟 Day 5 — Java Learning Journey  
A deep dive into **Java Architecture**, **JVM internals**, and **Variables**.  
Today’s session helped me clearly understand how Java works beneath the surface.

---

## 🔁 1. Revision  
Revised all concepts from the previous session to strengthen understanding.

---

# 🧱 2. Java Architecture  

## 🔧 2.1 JDK — Java Development Kit  
Everything a Java developer needs.

Includes:  
- 🛠 **Developer Tools**  
- 📝 **Java Compiler (`javac`)**  
- 🏃‍♂️ **JRE (Java Runtime Environment)**  

---

## ☕ 2.2 JRE — Java Runtime Environment  
Responsible for running Java applications.

Contains:  
- 📚 **Class Library**  
- 🧩 **JVM (Java Virtual Machine)**  

---

## ⚙️ 2.3 JVM — Java Virtual Machine  
The heart of Java execution.

### JVM Components  
- 📥 **Class Loader** — Loads classes into memory  
- 🔒 **Bytecode Verifier** — Ensures bytecode safety  
- 🚀 **Java Execution Engine (JEE)**  
  - ⚡ **JIT Compiler (Just-In-Time)** → Converts bytecode to machine code *at once*  
  - 📖 **Java Interpreter** → Executes bytecode *line by line*  

---

# 🔄 3. Code Execution Pipeline  

```
HLL Code (.java) → javac Compiler → Bytecode (.class) → JVM → Machine Code → Output
```

---

# 🧮 4. Variables in Java

## 🟦 What Are Variables?  
A variable is a container used to store data.

---

## ✍️ Ways to Create Variables

### 1️⃣ Using **data types**

```java
int age = 21;
double salary = 55000.50;
String name = "Manoja";
```

---

### 2️⃣ Using **var** keyword (Type Inference)

```java
var city = "Bangalore";   // Compiler infers String
var marks = 92;           // Compiler infers int
```

📌 When we use **var**, it is called **Type Inference**.

---

# 🔒 5. Extra Notes  
- Java is a **strictly typed language**  
- **Declaration** → Reserving memory  

```java
int x;
```

- **Initialization** → Assigning the first value  

```java
int x = 10;
```

- **Assignment** → Changing the value  

```java
x = 20;
```

---

# ✅ Summary  
Today was all about mastering Java's internal working and understanding variables deeply.  
This strong foundation will help me write efficient Java programs going forward 🚀.
