Here is a **simple README.md** based on your code:

# Hospital Patient Priority Queue

## Description

The **Hospital Patient Priority Queue** is a simple C program used to manage patients based on their medical priority. Patients with higher priority are treated before patients with lower priority.

### Priority Levels

* **1 – Emergency**
* **2 – Urgent**
* **3 – Routine**

If two patients have the same priority, the patient who arrived first is treated first.

## Features

* Add a patient
* Assign priority to a patient
* Treat the next patient
* Display waiting patients
* Exit the program

## Data Structure

The program uses a **Priority Queue with a Min-Heap**.

The patient with the smallest priority number is treated first.

## How to Run

Save the program as:

```text
patient_queue.c
```

Compile:

```bash
gcc patient_queue.c -o patient_queue
```

Run:

```bash
./patient_queue
```

## Example

```text
1. Add Patient
2. Treat Next Patient
3. Display Waiting Patients
4. Exit
```

If **John** has priority 3 and **Anu** has priority 1, Anu will be treated first because priority 1 represents an emergency.

## Conclusion

This project demonstrates how a **Priority Queue** can be used in a hospital to organize patients and ensure that emergency cases are handled first.
