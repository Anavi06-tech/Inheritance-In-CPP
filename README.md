🧬 Inheritance in C++-

📚 Theory-

Inheritance is a fundamental concept in Object-Oriented Programming (OOP). It allows a new class (called the derived class) to acquire the properties and behaviors of an existing class (called the base class). This promotes code reuse, modularity, and hierarchical classification.

🔑 Key Concepts-

Base Class: The class whose members (data and functions) are inherited by another class.

Derived Class: The class that inherits from the base class.

Access Specifiers:

public – Public and protected members of the base class remain accessible as they are.

protected – Public and protected members become protected in the derived class.

private – Public and protected members become private in the derived class.

🏗️ Types of Inheritance in C++-

C++ supports several types of inheritance:

🔹 Single Inheritance-

A single derived class inherits from a single base class.

Example:
Vehicle → Car

A Car inherits features (e.g., color, engine) from the Vehicle class.

🔹 Multilevel Inheritance-

A class is derived from another derived class, forming a chain of inheritance.

Example:
University → Department → Lab

A Lab inherits from Department, which in turn inherits from University.

🔹 Hierarchical Inheritance-

Multiple classes are derived from the same base class.

Example:
University → Department, University → Hostel, University → Library

Department, Hostel, and Library all share features of University.

🔹 Multiple Inheritance-

A single class inherits from more than one base class.

Example:
Department → University + Facility

Department inherits features from both University and Facility.

🔹 Hybrid Inheritance-

A combination of two or more types of inheritance (e.g., multiple + hierarchical).

Example:
University → Department, University → Hostel, and Lab → Department + Facility

Lab inherits from both Department and Facility, forming a hybrid structure.

✅ Benefits of Inheritance-

♻️ Code Reusability: Reuse common logic and functionality in derived classes.

🏗️ Extensibility: Add new features to derived classes without modifying base classes.

🌳 Hierarchy Modeling: Clearly model real-world relationships.

⚡ Flexibility: Build complex and scalable class architectures using different inheritance types.

📦 Encapsulation & Abstraction: Keeps implementation details hidden and exposes only necessary interfaces.

Inheritance enables polymorphism, which is the foundation for designing flexible and maintainable object-oriented systems in C++.
