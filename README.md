# Mutual-TLS

A simple and secure system that uses **2 boxes** and **2 locks** to ensure easy and safe data handling, designed to be intuitive for beginners.

## ✨ Features

- 🔒 Two-layer locking mechanism for enhanced security  
- 📦 Two distinct boxes representing data storage and processing  
- ✅ Easy to understand and implement  
- ⚙️ Modular design for flexibility and extension

<br>

## 🏗️ Architecture Overview

This system uses a simple analogy of **2 boxes** and **2 locks** to explain how data is protected and processed:

### 1️⃣ First Box & Lock — Data Storage  
The **first box** is where raw data is kept, secured by the **first lock**.  
Only authorized processes can open this lock to access or modify the stored data.  

### 2️⃣ Second Box & Lock — Data Processing  
The **second box** holds processed or intermediate data, protected by the **second lock**.  
This lock ensures data integrity during transformation and communication between components.

---

✅ **Why this matters:**  
- Each box isolates different stages of data handling for better organization.  
- Two locks provide layered security, making unauthorized access harder.  
- The analogy makes the architecture easy to grasp and implement, especially for newcomers.

<br>

## 🚀 Getting Started

### Installation  
Add this project to your environment easily:

⚡ Usage Example
**Imagine how the boxes and locks work together in three simple steps:**
1. Unlock Box 1 using Lock 1 to fetch raw data
2. Process data safely inside Box 2 protected by Lock 2
3. Lock Box 2 before sending data forward to ensure security
