# A small Java Course

## Idea

Even with a Java course fresh in mind, it can be tough to bootstrap a Java project from scratch and to get a working program from an IDE. This course is intended to show whats ongoing behind the IDE scenes and to help beginners with Java. Even with language details understood, the tooling is complex and there are many scenarios, options and conventions to go with. Due to some external constraints, this course in detail goes with Java 8 and Java 9. The favourized IDE is Eclipse, Gradle and Maven will be used as build tools.

## Requirements
 
 * One should be familar how to use command lines like Windows CMD or Gnu Bash
 * A JDK should be installed (Oracle JDK8 or 9)

## Lessons

### 1. Basics (*[lesson 1 handout](lesson-01-basics/doc/handout.pdf)*)

 * How to create a Java project manually with just the JDK on board?
 * How to setup a simple Eclipse project?
 * Create the source, compile it and create a runnable JAR with most basic tooling - just the JDK.
    
### 2. Bootstrap a project using Maven and Gradle
 
 * What do Maven and Gradle do?
 * Using Maven archetype to create a project.
 * Use gradle init to create a project.
 * Import the projects into Eclipse.
 * Create a runnable JAR (build and run the project).
 
### 3. Add external dependencies.
 
 * Create a runnable JAR with having the dependencies in a lib folder.
 * Create a runnable JAR with all dependencies included.

### 4. Add test frameworks such as JUnit, TestNG.
