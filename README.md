# Java_Interview_Questions

Q : Can we override a static method?

A : No

1. How many types of modifiers in Java?

Ans: There are two types of modifiers in Java:

Access modifiers
Non- access modifiers
2. What are Access modifiers in java?

Ans: Access Modifiers are those modifiers that are used to restrict the visibility of classes, fields, methods, and constructors.

Java supports four types of access modifiers:

Private
Default
Protected
Public
a) Private: Private members of a class can be accessed only within the class. It cannot be accessed from outside the class.

b) Default: Default members of a class are accessible within the same package due to visible only within the package. They cannot be accessed from outside the package.

c) Protected: Protected members of a class are visible within the package. Therefore, we can only access within the package but can be accessed to the subclasses outside the package through the inheritance only.

d) Public: Public members are visible anywhere. So, we can access it anywhere within or outside the package.

3. Can we have a private constructor in Java?

Ans: Yes, we can have a private constructor in Java.

The private constructor is used when we do not want to create the object of that class.
We cannot create a subclass of that class.
It is also used in Singleton design and Factory method design patterns.

4. Which access modifiers can be used with a class?
Ans: Public and Default access modifiers can be used with a class.

5. Can we instantiate the object of derived class if the parent constructor is protected?

Ans: No, we cannot instantiate the object of derived class if the parent constructor is protected.

6. What are non-access modifiers in Java?

Ans: There are four non-access modifiers in Java. They are as follows:

Static
Final
Abstract
Synchronized
a) Static: This modifier is used to check that a member is a class member or instance member. If you declare a class as static, this class will be executed first.

b) Final: Final is a keyword that is used to restrict the users. In other words, it is used to restrict further modification of a class, field, or method. If a class is declared as ‘final’, the class cannot be subclassed.

c) Abstract: Abstract is a keyword that is used with a class or a method. An abstract class or abstract method is used for further modification. If a class is declared as ‘abstract’, the class cannot be instantiated.

d) Synchronized: It is used to achieve thread safeness. Only one thread can enter in a synchronized method or block at a given time.



7. Can we declare a top-level class as private?
Ans: No, we cannot declare a top-level or outer class as private. It can have either “public” or no modifier.

If you declare a top-level class as a private, the compiler will complain that the “modifier private is not allowed here” but an inner class can be private.

Inner class means class as a member of another class. The same is the case with protected.

8. Can we declare an abstract method as private?

Ans: No, an abstract method cannot be private. They must be declared as public, protected, or default so that they can be further modified.

9. Can we declare a top-level class as protected?

Ans: No, we cannot declare a class as protected. An inner class can be protected but not an outer class.

10. Can a method or a class be final and abstract at the same time?

Ans: No, it is not possible. A class or a method cannot be final or abstract at the same time because the final method or final class cannot be further modified whereas an abstract class or an abstract method must be modified further.

11. Why are access modifiers used?

Ans: The access modifiers are used to restrict the access of a class and its members. Access modifiers are used to reduce the visibility of the members of a class.

12. Which is the default access modifier?

Ans: ‘Internal’ is the default access modifier if no access modifier is mentioned with a class or its members. Internal is a keyword that is used for declaration.

13. What is the default access modifier for Interface?

Ans: The public is the default access modifier for the interface. No other access modifier is allowed for them

14. Can we define struct members as protected?

Ans: No, we cannot define struct members as protected because struct does not support inheritance.

15. What is the default access specifier for a class, an interface, and struct declared directly with a namespace?

Ans: Internal

16. What is access modifier for enumeration?

Ans: Enumeration members are always public. No other access modifiers are allowed.

17. What is the role of private constructor in Java?

Ans: If you declare any constructor of a class as private, we cannot create the object of a class from outside the class. In other words, we cannot create the subclass of that class.

18. Which is the least restrictive access modifier in Java?

Ans: Public

19. Which is the most restrictive access modifier in Java?

Ans: Private

20. Which access modifier is also known as Universal access modifier?

Ans: Public

21. Explain visibility control in Java.

Ans: Visibility control in Java is implemented by the access modifiers.
![image](https://github.com/alihaider8480/Java_Interview_Questions/assets/40827670/c6c350c0-7d26-40f4-a4d0-c03da2677e57)
