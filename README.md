<?xml version="1.0" encoding="UTF-8"?>
<README>
  
  <Project>
    <Name>Student Information System</Name>
    <Level>Intermediate Java Project</Level>
    <Description>
      A console-based Student Information System developed in Java.
      This project demonstrates Object-Oriented Programming (OOP) principles 
      and the implementation of fundamental Data Structures 
      such as Linked List and Binary Search Tree (BST).
    </Description>
  </Project>

  <Features>
    <Feature>Add new student records with ID, Name, Department, and Grade</Feature>
    <Feature>View all stored student information</Feature>
    <Feature>Search students by ID using Linked List (Linear Search)</Feature>
    <Feature>Search students by ID using Binary Search Tree (Efficient Search)</Feature>
    <Feature>Interactive menu-driven console application</Feature>
  </Features>

  <Technologies>
    <Language>Java</Language>
    <Concepts>
      <Concept>Encapsulation (private fields with getters and setters)</Concept>
      <Concept>Custom Linked List implementation</Concept>
      <Concept>Binary Search Tree for optimized searching</Concept>
      <Concept>Menu-driven user interaction</Concept>
    </Concepts>
  </Technologies>

  <ClassStructure>
    <Class name="Student">
      <Role>Represents a student entity with ID, Name, Department, and Grade</Role>
    </Class>
    <Class name="StudentLinkedList">
      <Role>Stores student objects in a singly linked list and performs linear search</Role>
    </Class>
    <Class name="StudentBST">
      <Role>Stores student objects in a binary search tree and performs efficient search</Role>
    </Class>
    <Class name="StudentInformationSystem">
      <Role>Main driver class providing menu options and handling user interaction</Role>
    </Class>
  </ClassStructure>

  <Installation>
    <Step>1. Ensure Java (JDK) is installed on your system</Step>
    <Step>2. Save the source code in <File>StudentInformationSystem.java</File></Step>
    <Step>3. Open terminal/command prompt in the project directory</Step>
    <Step>4. Compile: <Command>javac StudentInformationSystem.java</Command></Step>
    <Step>5. Run: <Command>java StudentInformationSystem</Command></Step>
  </Installation>

  <Usage>
    <MenuOptions>
      <Option>1 → Add Student</Option>
      <Option>2 → View All Students</Option>
      <Option>3 → Search Student by ID (LinkedList)</Option>
      <Option>4 → Search Student by ID (BST)</Option>
      <Option>5 → Exit</Option>
    </MenuOptions>
  </Usage>

  <Example>
    <Input>
      <![CDATA[
      Choose Option: 1
      Enter Student ID: 101
      Enter Student Name: John Doe
      Enter Department: Computer Science
      Enter Grade: 8.7
      ]]>
    </Input>
    <Output>
      <![CDATA[
      Student added successfully!
      ]]>
    </Output>
  </Example>

  <FutureEnhancements>
    <Enhancement>Implement file/database persistence for student records</Enhancement>
    <Enhancement>Add update and delete functionality</Enhancement>
    <Enhancement>Integrate graphical user interface (JavaFX/Swing)</Enhancement>
    <Enhancement>Implement input validation and exception handling</Enhancement>
  </FutureEnhancements>

  <Author>
    <Name>Your Name</Name>
    <Repository>https://github.com/your-repo-url</Repository>
  </Author>

</README>
