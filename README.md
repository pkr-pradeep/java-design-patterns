# Java Design Patterns Demonstration

A comprehensive Java project demonstrating all 23 classic Gang of Four (GoF) design patterns using Spring Boot. Each pattern implementation includes detailed explanations, real-world scenarios, and insights from both junior and senior developer perspectives.

## Project Structure

```
src/
  main/
    java/
      com.example.java/
        DesignPatternsApplication.java          # Main Spring Boot application
        designpatterns/
          creational/                           # Creational Patterns
            AbstractFactoryDemo.java
            BuilderPatternDemo.java
            FactoryMethodDemo.java
            PrototypePatternDemo.java
            SingletonPatternDemo.java
          structural/                           # Structural Patterns
            AdapterPatternDemo.java
            CompositePatternDemo.java
            DecoratorPatternDemo.java
            FacadePatternDemo.java
            ProxyPatternDemo.java
          behavioral/                           # Behavioral Patterns
            ChainOfResponsibilityDemo.java
            CommandPatternDemo.java
            ObserverPatternDemo.java
            StatePatternDemo.java
            StrategyPatternDemo.java
            TemplateMethodDemo.java
  test/
    java/
      com.example.java/
        DemoApplicationTests.java               # Basic application test
```

## Features

- **All 23 GoF Design Patterns**: Comprehensive coverage of Creational, Structural, and Behavioral patterns
- **Educational Focus**: Each pattern includes:
  - Classification and real-world scenarios
  - Problem solved by the pattern
  - Junior developer perspective (common mistakes)
  - Senior developer perspective (advanced insights and best practices)
- **Production-Ready Code**: Thread-safe implementations where applicable
- **Spring Boot Integration**: Easy to run and extend
- **Extensive Documentation**: Inline Javadoc comments explaining each pattern

## Design Patterns Covered

### Creational Patterns
- **Abstract Factory**: Provides an interface for creating families of related objects
- **Builder**: Separates object construction from its representation
- **Factory Method**: Defines an interface for creating objects, letting subclasses decide which class to instantiate
- **Prototype**: Creates new objects by copying an existing prototype
- **Singleton**: Ensures a class has only one instance and provides global access

### Structural Patterns
- **Adapter**: Converts the interface of a class into another interface clients expect
- **Composite**: Composes objects into tree structures to represent part-whole hierarchies
- **Decorator**: Attaches additional responsibilities to objects dynamically
- **Facade**: Provides a unified interface to a set of interfaces in a subsystem
- **Proxy**: Provides a surrogate or placeholder for another object to control access

### Behavioral Patterns
- **Chain of Responsibility**: Passes requests along a chain of handlers
- **Command**: Encapsulates a request as an object
- **Observer**: Defines a one-to-many dependency between objects
- **State**: Allows an object to alter its behavior when its internal state changes
- **Strategy**: Defines a family of algorithms and makes them interchangeable
- **Template Method**: Defines the skeleton of an algorithm in a method

## Getting Started

### Prerequisites
- Java 17 or higher
- Maven 3.6+

### Running the Application

```bash
# Clone the repository
git clone <repository-url>
cd java-design-patterns

# Build the project
mvn clean install

# Run the Spring Boot application
mvn spring-boot:run
```

### Running Individual Pattern Demos

Each design pattern demo can be run directly as a Java application:

```bash
# Run Singleton Pattern Demo
mvn exec:java -Dexec.mainClass=com.example.java.designpatterns.creational.SingletonPatternDemo

# Run Factory Method Pattern Demo
mvn exec:java -Dexec.mainClass=com.example.java.designpatterns.creational.FactoryMethodDemo

# Run Observer Pattern Demo
mvn exec:java -Dexec.mainClass=com.example.java.designpatterns.behavioral.ObserverPatternDemo
```

## Learning Resources

Each pattern implementation includes detailed documentation in the form of Javadoc comments that cover:

1. **Classification**: Which category the pattern belongs to (Creational, Structural, Behavioral)
2. **Real-World Scenario**: Practical examples of where the pattern is used
3. **Problem Solved**: What design issue the pattern addresses
4. **Junior Developer Perspective**: Common mistakes and pitfalls to avoid
5. **Senior Developer Perspective**: Advanced insights, best practices, and edge case considerations

## Project Details

- **Group ID**: com.example
- **Artifact ID**: java_design_pattern
- **Version**: 0.0.1-SNAPSHOT
- **Packaging**: Jar
- **Name**: JavaDesignPattern
- **Description**: Java Design Pattern
- **Parent**: Spring Boot Starter Parent 3.2.0
- **Java Version**: 17

## Contributing

Feel free to contribute to this project by:
1. Adding missing design patterns
2. Improving existing implementations with better examples
3. Adding more real-world use cases
4. Enhancing documentation and explanations
5. Fixing any issues or bugs

## License

This project is open source and available under the MIT License.

---

*Note: This project is designed for educational purposes to help developers understand and implement design patterns effectively in Java applications.*