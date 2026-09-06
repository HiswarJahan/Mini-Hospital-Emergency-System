
# Mini Hospital Emergency Management System

## 1. Introduction

The **Mini Hospital Emergency Management System** is a Java-based application developed for the CIT300 - Data Structures and Algorithms individual assignment.

The purpose of this system is to simulate how a hospital manages patients, emergency treatment requests, completed treatments, and previous patient visits.

The system demonstrates the practical use of different data structures in a hospital environment.

---

## 2. Objectives

The main objectives of this project are:

* To register and manage patient records.
* To search and delete patient records.
* To manage emergency patients using a queue.
* To store completed treatment records using a stack.
* To maintain patient visit history using a singly linked list.
* To demonstrate the practical use of data structures in Java.

---

## 3. Technologies Used

* **Programming Language:** Java
* **IDE:** Eclipse IDE
* **Version Control:** GitHub
* **Data Structures:** Binary Search Tree, Queue, Stack, Singly Linked List

---

## 4. Data Structures Used

### 4.1 Binary Search Tree (BST)

The Binary Search Tree is used to store patient records.

The **Patient ID** is used as the key for the BST.

The system supports:

* Insert a new patient
* Search for a patient
* Delete a patient
* In-order traversal

The in-order traversal displays patients in ascending order according to their Patient ID.

---

### 4.2 Queue

A Queue is used to manage patients waiting for emergency treatment.

The queue follows the **FIFO (First-In, First-Out)** principle.

The system supports:

* Enqueue a patient
* Dequeue the next patient
* Display waiting patients
* Handle an empty queue

---

### 4.3 Stack

A Stack is used to store completed treatment records.

The stack follows the **LIFO (Last-In, First-Out)** principle.

The system supports:

* Push a treatment record
* Pop the most recently completed treatment
* Display treatment records
* Handle an empty stack

---

### 4.4 Singly Linked List

A Singly Linked List is used to maintain a patient's previous hospital visits.

Each visit can contain:

* Visit ID
* Visit Date
* Doctor Name
* Diagnosis
* Treatment

The system supports:

* Add a visit
* Remove a visit
* Search for a visit
* Display visit history

---

## 5. Patient Information

Each patient record contains:

* Patient ID
* Patient Name
* Age
* Contact Number
* Medical Condition

---

## 6. Main System Features

The system provides the following features:

1. Register a new patient.
2. Search for a patient using Patient ID.
3. Delete a patient.
4. Display all patients using BST in-order traversal.
5. Add a patient to the emergency queue.
6. Treat the next patient in the queue.
7. Display patients currently waiting.
8. Add completed treatment records.
9. Remove the latest treatment record.
10. Display treatment history.
11. Add a patient's previous visit.
12. Search for a visit.
13. Remove a visit.
14. Display patient visit history.

---

## 7. Project Structure

The project is organized into several Java classes:

```text
MiniHospitalEmergencySystem
│
├── src
│   └── hospital
│       ├── Patient.java
│       ├── PatientBST.java
│       ├── EmergencyQueue.java
│       ├── TreatmentRecord.java
│       ├── TreatmentStack.java
│       ├── Visit.java
│       ├── VisitHistory.java
│       └── HospitalManagementSystem.java
│
└── README.md
```

---

## 8. How to Run the Program

1. Open **Eclipse IDE**.
2. Import or open the `MiniHospitalEmergencySystem` project.
3. Make sure all Java files are inside the `hospital` package.
4. Open `HospitalManagementSystem.java`.
5. Right-click the file.
6. Select **Run As → Java Application**.
7. The hospital management menu will appear in the console.
8. Select the required option by entering the corresponding number.

---

## 9. Testing

The system should be tested using different patient records and operations.

### BST Testing

Test:

* Patient insertion
* Patient searching
* Patient deletion
* In-order traversal

### Queue Testing

Test:

* Adding patients to the queue
* Removing patients from the queue
* Displaying waiting patients
* Empty queue handling

### Stack Testing

Test:

* Adding treatment records
* Removing the latest treatment
* Displaying treatment history
* Empty stack handling

### Linked List Testing

Test:

* Adding visits
* Searching visits
* Removing visits
* Displaying visit history

---

## 10. GitHub Development

The project is maintained using GitHub to demonstrate the development process.

Meaningful commits include:

```text
Created project structure
Implemented Patient class
Implemented Patient BST
Added BST search and deletion
Implemented emergency queue
Implemented treatment stack
Implemented patient visit linked list
Added system integration
Added testing
Updated README
```

The project is developed progressively rather than being uploaded as one final commit.

---

## 11. Learning Outcomes

Through this project, I learned how different data structures can be applied to solve practical problems.

I gained experience in implementing:

* Binary Search Trees
* Queues
* Stacks
* Singly Linked Lists

I also improved my understanding of Java programming, object-oriented programming, debugging, testing, GitHub, and version control.

---

## 12. Conclusion

The Mini Hospital Emergency Management System demonstrates how data structures can be used to manage different hospital operations.

The Binary Search Tree manages patient records, the Queue manages emergency patients, the Stack stores completed treatments, and the Singly Linked List maintains patient visit history.

Overall, the project provides practical experience in applying data structures to a real-world problem using Java.
