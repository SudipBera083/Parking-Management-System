# 🚗 Parking Management System (C Program)

## 📖 Overview
This project is a simple **Parking Management System** written in C.  
It helps manage the number of vehicles entering a parking area, track their counts, calculate total earnings, and reset data when required.

---

## 🧠 Features
- Add **Bus**, **Rikshaw**, or **Cycle** entries  
- View **current parking details** (number of vehicles, total amount, etc.)  
- **Delete all records** (reset data)  
- Simple and interactive **menu-driven console interface**  
- Calculates **total revenue** automatically  

---

## ⚙️ Menu Options

| Option | Description |
|:-------:|:------------|
| 1 | Entry the Bus |
| 2 | Entry the Rikshaw |
| 3 | Entry the Cycle |
| 4 | See your Status |
| 5 | Delete the whole Data |
| 6 | Exit the Program |

---

## 💰 Charges per Vehicle

| Vehicle Type | Charge (₹) |
|:--------------|:------------:|
| Bus | 100 |
| Rikshaw | 50 |
| Cycle | 20 |

---

## 🧾 Output Example

```
1.Entry the Bus
2.Entry the Rikshaw
3.Entry the Cycle
4.See your Status
5.Delete the whole Data
6.Exit
Enter your choice:
1
Data entered successfully

1.Entry the Bus
2.Entry the Rikshaw
3.Entry the Cycle
4.See your Status
5.Delete the whole Data
6.Exit
Enter your choice:
4
Number of Bus: 1
Number of Rikshaw: 0
Number of Cycle: 0
Total amount: 100
Total number of Vehicles: 1
```

---

## 🧩 Functions Breakdown

| Function | Description |
|:----------|:-------------|
| `menue()` | Displays options and returns user choice |
| `bus()` | Adds a Bus entry and updates amount |
| `rikshaw()` | Adds a Rikshaw entry and updates amount |
| `cycle()` | Adds a Cycle entry and updates amount |
| `details()` | Displays all vehicle counts and total amount |
| `deletes()` | Resets all data to zero |

---

## 🛠️ How to Run

1. Save the code as `parking.c`
2. Compile it using:
   ```bash
   gcc parking.c -o parking
   ```
3. Run the program:
   ```bash
   ./parking
   ```

---

## 👨‍💻 Author
**Sudip Bera**  
💼 Programmer Analyst @ Cognizant  
🧠 Passionate about system programming and AI  

---

## 🏁 License
This project is open-source and free to use for educational purposes.
