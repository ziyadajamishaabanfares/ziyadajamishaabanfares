<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,100:302b63&height=200&section=header&text=Ziyad%20Ajamisha%20Abanfares&fontSize=45&fontColor=ffffff&fontAlignY=38&desc=Developer%20%7C%20Innovator%20%7C%20AI%20Enthusiast&descAlignY=60&descSize=20" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=700&lines=Welcome+to+My+Presidential+Profile+%F0%9F%8F%9B%EF%B8%8F;I+am+a+Software+Developer+%F0%9F%92%BB;Studying+Artificial+Intelligence+%F0%9F%A4%96;Building+the+Future+One+Line+at+a+Time+%E2%9C%A8)](https://git.io/typing-svg)

</div>

---

## 🏛️ About Me — The Presidential Statement

> *"Every great empire was built not by swords, but by vision. Mine is being built line by line, algorithm by algorithm."*

Hello, I am **Ziyad Ajamisha Abanfares** — a passionate and determined individual on a mission to master the world of **technology, software development, and artificial intelligence**. I believe that knowledge is the most powerful weapon, and I wield it every single day through code.

I am not just learning — I am **building myself** into a world-class developer. My journey is one of discipline, ambition, and relentless growth. I study not to pass tests, but to **change the world**.

---

<div align="center">

## 🌍 My Development Journey

| 🗓️ Year | 🎯 Milestone |
|---------|------------|
| 2023 | Started my programming journey — first lines of code |
| 2024 | Deep dive into Software Development & Data Structures |
| 2025 | Exploring Artificial Intelligence & Machine Learning |
| 2026 | Building real-world projects & contributing to open source |

</div>

---

## 💻 Programming Languages I'm Studying

<div align="center">

### 🐍 Python — The Language of Intelligence

```python
# Python: The cornerstone of AI and Data Science
class Developer:
    def __init__(self):
        self.name = "Ziyad Ajamisha Abanfares"
        self.languages = ["Python", "JavaScript", "C++", "SQL"]
        self.passion = "Artificial Intelligence"
        self.goal = "Change the world through code"
        self.mindset = "Presidential 👑"

    def greet(self):
        return f"Hello World! I'm {self.name}, and I'm here to build the future."

    def learn(self, topic):
        print(f"📚 Currently mastering: {topic}")
        return "Knowledge acquired. Power increased."

me = Developer()
print(me.greet())
me.learn("Machine Learning")
```

### ⚡ JavaScript — The Language of the Web

```javascript
// JavaScript: Bringing ideas to life on the web
const ziyad = {
  name: "Ziyad Ajamisha Abanfares",
  role: "Full-Stack Developer in Training",
  skills: ["HTML", "CSS", "JavaScript", "React", "Node.js"],
  currentFocus: "Building dynamic web applications",
  
  introduce: function() {
    return `I am ${this.name} — a developer with presidential ambitions! 🏛️`;
  },
  
  dailyRoutine: () => {
    const activities = ["Code", "Learn", "Build", "Repeat"];
    activities.forEach(activity => console.log(`✅ ${activity}`));
  }
};

console.log(ziyad.introduce());
ziyad.dailyRoutine();
```

### ⚙️ C++ — The Language of Power

```cpp
// C++: The foundation of performance and systems programming
#include <iostream>
#include <string>
using namespace std;

class PresidentialDeveloper {
private:
    string name;
    string mission;
    int linesOfCodeWritten;

public:
    PresidentialDeveloper(string n, string m) {
        name = n;
        mission = m;
        linesOfCodeWritten = 0;
    }

    void writeCode(int lines) {
        linesOfCodeWritten += lines;
        cout << "✅ Wrote " << lines << " lines. Total: " << linesOfCodeWritten << endl;
    }

    void displayProfile() {
        cout << "👑 Name: " << name << endl;
        cout << "🎯 Mission: " << mission << endl;
        cout << "💻 Code Written: " << linesOfCodeWritten << " lines" << endl;
    }
};

int main() {
    PresidentialDeveloper ziyad("Ziyad Ajamisha Abanfares", "Master AI & Software Engineering");
    ziyad.writeCode(500);
    ziyad.writeCode(300);
    ziyad.displayProfile();
    return 0;
}
```

</div>

---

## 🤖 Artificial Intelligence — My Grand Ambition

<div align="center">

> *"Artificial Intelligence is not the future — it is the present, and I am here to master it."*

</div>

I am currently diving deep into the world of **Artificial Intelligence** and **Machine Learning**. Here are the key concepts I am actively studying:

### 🧠 Core AI/ML Concepts I'm Mastering

```
📦 MACHINE LEARNING
├── 📊 Supervised Learning
│   ├── Linear Regression
│   ├── Logistic Regression
│   ├── Decision Trees
│   ├── Random Forests
│   └── Support Vector Machines (SVM)
├── 🔍 Unsupervised Learning
│   ├── K-Means Clustering
│   ├── Principal Component Analysis (PCA)
│   └── Association Rules
├── 🎮 Reinforcement Learning
│   ├── Q-Learning
│   └── Deep Q-Networks (DQN)
└── 📈 Model Evaluation
    ├── Accuracy, Precision, Recall
    ├── F1 Score
    └── Cross-Validation

🧬 DEEP LEARNING
├── 🔗 Neural Networks
│   ├── Feedforward Neural Networks
│   ├── Backpropagation
│   └── Activation Functions (ReLU, Sigmoid, Tanh)
├── 🖼️ Convolutional Neural Networks (CNN)
│   └── Image Recognition & Classification
├── 🔄 Recurrent Neural Networks (RNN)
│   ├── LSTM (Long Short-Term Memory)
│   └── Natural Language Processing
└── 🤗 Transformers
    ├── Attention Mechanism
    ├── BERT, GPT Architecture
    └── Large Language Models (LLMs)
```

### 🐍 My AI Code in Action

```python
import numpy as np

# Neural Network from Scratch — Understanding the Fundamentals
class NeuralNetwork:
    def __init__(self, layers):
        """
        layers: list of layer sizes e.g. [2, 4, 1]
        """
        self.weights = []
        self.biases = []
        
        for i in range(len(layers) - 1):
            w = np.random.randn(layers[i], layers[i+1]) * 0.01
            b = np.zeros((1, layers[i+1]))
            self.weights.append(w)
            self.biases.append(b)
    
    def sigmoid(self, z):
        """Activation function: squashes values between 0 and 1"""
        return 1 / (1 + np.exp(-z))
    
    def sigmoid_derivative(self, z):
        """Derivative for backpropagation"""
        return self.sigmoid(z) * (1 - self.sigmoid(z))
    
    def forward(self, X):
        """Forward pass: propagate input through the network"""
        self.activations = [X]
        current = X
        
        for w, b in zip(self.weights, self.biases):
            z = np.dot(current, w) + b
            current = self.sigmoid(z)
            self.activations.append(current)
        
        return current
    
    def predict(self, X):
        output = self.forward(X)
        return (output > 0.5).astype(int)

# Building my first neural network!
nn = NeuralNetwork([3, 5, 4, 1])
X = np.array([[0.5, 0.2, 0.8]])
prediction = nn.forward(X)
print(f"🤖 Neural Network Output: {prediction}")
print("🚀 AI Journey: INITIATED")
```

---

## 🏗️ Software Development Concepts

<div align="center">

> *"A great developer doesn't just write code — they design systems, architect solutions, and engineer the future."*

</div>

### 📐 Data Structures & Algorithms

```python
# ========================
# DATA STRUCTURES I STUDY
# ========================

# 1️⃣ LINKED LIST
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class LinkedList:
    def __init__(self):
        self.head = None
    
    def append(self, data):
        new_node = Node(data)
        if not self.head:
            self.head = new_node
            return
        current = self.head
        while current.next:
            current = current.next
        current.next = new_node
    
    def display(self):
        elements = []
        current = self.head
        while current:
            elements.append(current.data)
            current = current.next
        print(" → ".join(map(str, elements)) + " → NULL")

# 2️⃣ BINARY SEARCH TREE
class BSTNode:
    def __init__(self, val):
        self.val = val
        self.left = None
        self.right = None

class BinarySearchTree:
    def __init__(self):
        self.root = None
    
    def insert(self, val):
        def _insert(node, val):
            if not node:
                return BSTNode(val)
            if val < node.val:
                node.left = _insert(node.left, val)
            else:
                node.right = _insert(node.right, val)
            return node
        self.root = _insert(self.root, val)
    
    def inorder(self, node, result=[]):
        if node:
            self.inorder(node.left, result)
            result.append(node.val)
            self.inorder(node.right, result)
        return result

# 3️⃣ SORTING ALGORITHMS
def merge_sort(arr):
    """Divide and Conquer — O(n log n)"""
    if len(arr) <= 1:
        return arr
    mid = len(arr) // 2
    left = merge_sort(arr[:mid])
    right = merge_sort(arr[mid:])
    return merge(left, right)

def merge(left, right):
    result = []
    i = j = 0
    while i < len(left) and j < len(right):
        if left[i] <= right[j]:
            result.append(left[i])
            i += 1
        else:
            result.append(right[j])
            j += 1
    result.extend(left[i:])
    result.extend(right[j:])
    return result

print("✅ Merge Sort:", merge_sort([64, 34, 25, 12, 22, 11, 90]))
```

### 🏛️ Object-Oriented Programming (OOP)

```python
# The Four Pillars of OOP

# 1. ENCAPSULATION — Hiding internal details
class BankAccount:
    def __init__(self, owner, balance):
        self.__owner = owner        # Private attribute
        self.__balance = balance    # Private attribute
    
    def deposit(self, amount):
        if amount > 0:
            self.__balance += amount
            print(f"✅ Deposited ${amount}. New balance: ${self.__balance}")
    
    def get_balance(self):
        return self.__balance  # Controlled access

# 2. INHERITANCE — Reusing and extending code
class Animal:
    def __init__(self, name):
        self.name = name
    
    def speak(self):
        return "..."

class Dog(Animal):
    def speak(self):
        return f"{self.name} says: Woof! 🐕"

class Cat(Animal):
    def speak(self):
        return f"{self.name} says: Meow! 🐈"

# 3. POLYMORPHISM — Many forms
animals = [Dog("Rex"), Cat("Luna"), Dog("Max")]
for animal in animals:
    print(animal.speak())  # Each behaves differently!

# 4. ABSTRACTION — Simplifying complexity
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass
    
    @abstractmethod
    def perimeter(self):
        pass

class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius
    
    def area(self):
        return 3.14159 * self.radius ** 2
    
    def perimeter(self):
        return 2 * 3.14159 * self.radius

circle = Circle(5)
print(f"🔵 Circle Area: {circle.area():.2f}")
```

---

## 🔧 Technologies & Tools

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### AI & Data Science
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 📊 My Learning Roadmap

```
🗺️  ZIYAD'S DEVELOPER ROADMAP 2025-2027
═══════════════════════════════════════════════════════════

PHASE 1: FOUNDATIONS ✅ (Completed)
├── ✅ Programming Fundamentals (Variables, Loops, Functions)
├── ✅ Object-Oriented Programming
├── ✅ Basic Data Structures (Arrays, Lists, Stacks, Queues)
└── ✅ Version Control with Git & GitHub

PHASE 2: INTERMEDIATE 🔄 (In Progress)
├── 🔄 Advanced Data Structures (Trees, Graphs, Hash Tables)
├── 🔄 Algorithms & Complexity (Big-O Notation)
├── 🔄 Web Development (HTML, CSS, JavaScript)
├── 🔄 Database Design & SQL
└── 🔄 Introduction to Machine Learning

PHASE 3: ADVANCED 📋 (Upcoming)
├── 📋 Deep Learning & Neural Networks
├── 📋 Natural Language Processing (NLP)
├── 📋 Computer Vision
├── 📋 Cloud Computing (AWS / Azure / GCP)
├── 📋 System Design & Architecture
└── 📋 Full-Stack Web Development

PHASE 4: MASTERY 🏆 (Future Vision)
├── 🏆 AI Research & Innovation
├── 🏆 Open Source Leadership
├── 🏆 Building My Own AI Products
└── 🏆 Mentoring the Next Generation
```

---

## 🧮 Computer Science Fundamentals

### Big-O Complexity — The Language of Efficiency

```
⏱️  TIME COMPLEXITY CHEAT SHEET
════════════════════════════════════════════════════

O(1)        → Constant    ██░░░░░░░░  BEST    ⭐⭐⭐⭐⭐
            Example: Array access by index

O(log n)    → Logarithmic █████░░░░░  GREAT   ⭐⭐⭐⭐
            Example: Binary Search

O(n)        → Linear      ██████░░░░  GOOD    ⭐⭐⭐
            Example: Linear Search

O(n log n)  → Log-Linear  ███████░░░  OK      ⭐⭐
            Example: Merge Sort, Quick Sort

O(n²)       → Quadratic   █████████░  BAD     ⭐
            Example: Bubble Sort, Nested Loops

O(2ⁿ)       → Exponential ██████████  AVOID   ❌
            Example: Recursive Fibonacci (naive)

O(n!)       → Factorial   ██████████  AVOID   ❌❌
            Example: Traveling Salesman (brute force)
```

### Algorithms I Study

```python
# ============================================
# FUNDAMENTAL ALGORITHMS
# ============================================

# 🔍 BINARY SEARCH — O(log n)
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid          # Found!
        elif arr[mid] < target:
            left = mid + 1      # Search right half
        else:
            right = mid - 1     # Search left half
    return -1                   # Not found

# 🔄 DYNAMIC PROGRAMMING — Fibonacci with Memoization
def fibonacci(n, memo={}):
    if n in memo:
        return memo[n]
    if n <= 1:
        return n
    memo[n] = fibonacci(n-1, memo) + fibonacci(n-2, memo)
    return memo[n]

# Print first 10 Fibonacci numbers
fib_sequence = [fibonacci(i) for i in range(10)]
print(f"🌀 Fibonacci: {fib_sequence}")

# 📊 GRAPH — BFS (Breadth-First Search)
from collections import deque

def bfs(graph, start):
    visited = set()
    queue = deque([start])
    order = []
    
    while queue:
        node = queue.popleft()
        if node not in visited:
            visited.add(node)
            order.append(node)
            for neighbor in graph.get(node, []):
                if neighbor not in visited:
                    queue.append(neighbor)
    
    return order

graph = {'A': ['B', 'C'], 'B': ['D', 'E'], 'C': ['F'], 'D': [], 'E': [], 'F': []}
print(f"🗺️ BFS Order: {bfs(graph, 'A')}")
```

---

## 🌐 Web Development Skills

```javascript
// ============================================
// MODERN JAVASCRIPT CONCEPTS
// ============================================

// Promises & Async/Await
async function fetchUserData(userId) {
    try {
        const response = await fetch(`https://api.example.com/users/${userId}`);
        const data = await response.json();
        return data;
    } catch (error) {
        console.error("❌ Error fetching data:", error);
    }
}

// ES6+ Features I'm Learning
const skills = ["Python", "JavaScript", "C++", "AI/ML"];

// Destructuring
const [firstSkill, ...restSkills] = skills;
console.log(`🥇 Main skill: ${firstSkill}`);
console.log(`📚 Other skills: ${restSkills.join(", ")}`);

// Spread operator & Object manipulation
const profile = {
    name: "Ziyad Ajamisha Abanfares",
    role: "Developer",
    ...{ country: "My Country", year: 2026 }
};

// Arrow functions & Higher-order functions
const skillLengths = skills.map(skill => skill.length);
const longSkills = skills.filter(skill => skill.length > 5);
const allSkills = skills.reduce((acc, skill) => acc + " | " + skill);

console.log("🏗️ Building the future with JavaScript!");
```

---

## 📈 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ziyadajamishaabanfares&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ziyadajamishaabanfares&theme=tokyonight&hide_border=true" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ziyadajamishaabanfares&layout=compact&theme=tokyonight&hide_border=true" width="40%"/>

</div>

---

## 🏆 My Values & Philosophy

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║           THE PRESIDENTIAL DEVELOPER'S CREED                ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║   "I code not to compete, but to CREATE."                   ║
║                                                              ║
║   "Every bug I fix makes me stronger."                      ║
║                                                              ║
║   "I study AI because I want to BUILD intelligence."        ║
║                                                              ║
║   "Today's learner is tomorrow's innovator."                ║
║                                                              ║
║   "The best code is written with patience and vision."      ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 🤝 Let's Connect

<div align="center">

I am always open to collaborating, learning, and growing together!

[![GitHub](https://img.shields.io/badge/GitHub-ziyadajamishaabanfares-181717?style=for-the-badge&logo=github)](https://github.com/ziyadajamishaabanfares)

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:302b63,100:0f0c29&height=120&section=footer&text=Keep+Coding+%E2%9C%A8+Keep+Growing+%F0%9F%9A%80&fontSize=20&fontColor=ffffff" width="100%"/>

</div>

---

<div align="center">
<sub>⭐ Star my repositories if you find them helpful! | Last Updated: March 2026</sub>
</div>
