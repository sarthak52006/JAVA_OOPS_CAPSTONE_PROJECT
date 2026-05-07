# Gym Membership System 🏋️‍♂️

A modern **Java Swing GUI application** for managing gym memberships using **Object-Oriented Programming (OOP)** concepts.  
This project demonstrates concepts like **Encapsulation, Inheritance, Polymorphism, and Abstraction** with an interactive desktop interface.

---

## 📌 Features

- ➕ Add new gym members
- 🔍 Search members by name
- ❌ Remove members
- 📋 Display all members in a styled table
- 🌟 Premium member support with trainer allocation
- 🎨 Modern dark-themed Java Swing UI
- ✅ Input validation and status updates

---

## 🛠️ Technologies Used

- **Java**
- **Java Swing**
- **OOP Concepts**
- **ArrayList**
- **JTable & DefaultTableModel**

---

## 🧠 OOP Concepts Implemented

| Concept | Implementation |
|---|---|
| Class & Object | `Member`, `PremiumMember`, `GymMembershipSystem` |
| Encapsulation | Private fields with getters |
| Inheritance | `PremiumMember extends Member` |
| Polymorphism | Overriding `getRowData()` |
| Abstraction | Hiding table row generation logic |

---

## 📂 Project Structure

```bash
GymMembershipSystem.java
```

Main classes inside the file:

- `Member`
- `PremiumMember`
- `GymMembershipSystem`

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/gym-membership-system.git
```

### 2️⃣ Open in IDE

Open the project in:

- IntelliJ IDEA
- Eclipse
- VS Code

### 3️⃣ Compile and Run

```bash
javac GymMembershipSystem.java
java GymMembershipSystem
```

---

## 🖥️ UI Preview

### Main Features:
- Header section with status updates
- Styled member table
- Add/Search/Remove buttons
- Premium plan highlighting

---

## 📋 Sample Members Included

| ID | Name | Plan |
|---|---|---|
| 1 | Rahul Sharma | Basic |
| 2 | Priya Mehta | Premium |
| 3 | Sarthak | Basic |
| 4 | Shailja | Basic |

---

## 🔧 Functionalities

### ➕ Add Member
- Add Basic or Premium members
- Trainer field enabled only for Premium plan

### 🔍 Search Member
- Search members using partial name matching

### ❌ Remove Member
- Remove by selecting table row
- Remove using Member ID

---

## 🎨 UI Customization

The project uses custom colors and styling through:

```java
setBackground()
setForeground()
BorderFactory
MouseAdapter
```

Custom dark mode theme improves the overall appearance of the application.

---

## 📚 Learning Outcomes

This project helps in understanding:

- Java Swing GUI development
- Event handling
- Data binding with tables
- Real-world OOP implementation
- Desktop application structure

---

## 👨‍💻 Author

**Sarthak Chauhan**

---

## ⭐ Future Improvements

- Database integration (MySQL)
- Login authentication
- Membership fee management
- Attendance tracking
- Export data to CSV/PDF

---

## 📄 License

This project is for educational purposes.
