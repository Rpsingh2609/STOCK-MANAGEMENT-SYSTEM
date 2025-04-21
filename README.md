# 📈 Command Line Stock Management System (C++ OOP Project)

This is a **Command Line Based Stock Management System** developed in C++ using Object-Oriented Programming principles. The system simulates the functionalities of a personal stock trading manager where users can:

- 💰 Add or withdraw money from their account  
- 🛒 Buy and sell stocks  
- 📊 View portfolio details  
- 🧾 Check transaction history  

---

## 🚀 Features

- **User Account Management**: Add or withdraw balance.
- **Stock Trading**: Buy and sell stocks with real-time updates to account and portfolio.
- **Portfolio Overview**: Displays all current holdings, stock quantities, and valuation.
- **Transaction History**: Detailed list of all transactions (buys, sells, deposits, and withdrawals).
- **Object-Oriented Design**: Built using C++ classes and OOP concepts such as inheritance, encapsulation, and abstraction.

---

## 🧠 Data Structures Used

This project demonstrates the use of **all major C++ STL (Standard Template Library) data structures**, showing a strong understanding of data handling and performance optimization:

- `std::vector` – For storing dynamic lists like transaction history and owned stocks.
- `std::map` – For mapping stock symbols to prices, quantities, and transaction records.
- `std::set` – To maintain unique stock entries and sorted collections where needed.
- `std::stack` – To manage last-in-first-out access such as undo operations.
- `std::queue` – To simulate sequential stock operations or user request queues.
- `std::pair` – For returning and handling pairs of values (e.g., stock and quantity).
- `std::string` – To handle user inputs, stock names, and textual outputs.

By combining these data structures, the system ensures efficient, clean, and reliable execution of stock management features.

---

## 🧩 Technologies Used

- Language: **C++**
- Concepts: **OOP (Classes, Inheritance, Polymorphism, Encapsulation)**  
- Platform: **Command Line Interface**
- STL: `vector`, `map`, `set`, `stack`, `queue`, `pair`, `string`

---

## 🏗️ Project Structure

- `main.cpp` – Entry point of the application
- `Account` – Manages balance, deposits, and withdrawals
- `Stock` – Represents stock information (name, price, quantity)
- `Transaction` – Logs all user activities and actions
- `Portfolio` – Tracks user's stock holdings
- `MyStocks` – Combines account, portfolio, and transaction logic

---

## 🧪 How to Run

 **Clone the repository**
   ```bash
   git clone https://github.com/your-username/stock-management-system.git
   cd stock-management-system  

 ---

## 📚 Learning Outcomes

    Mastered Object-Oriented Programming in C++

    Applied STL data structures in real-world scenarios

    Designed modular and maintainable code

    Simulated real trading functionalities through a command-line interface
