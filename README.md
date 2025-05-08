# 📂 Simple Bash Database Management Project

A mini **database management system** built entirely using **Bash scripting**, ideal for CLI-based data entry and retrieval. 
This project is great for practicing shell scripting, text file manipulation, and user input validation in a Linux environment.

---

## 🧠 Features

✅ **Initialize Database**: Create a CSV file with headers for ID, Name, and Email.

✅ **Create Entry**: Prompt user for a name and a valid email, check for duplicates, and append it with a unique ID.

✅ **Read All Entries**: Nicely formatted display of all entries using the `column` command.

✅ **Update Entry**: Update a record by ID after validating the ID, new name, and email. Prevent duplicate emails.

✅ **Delete Entry**: Delete an entry safely by ID with verification.

✅ **Input Validation**: Ensures name is not empty and email format is correct using regex.

✅ **Duplicate Checks**: Prevents email duplication across records.

✅ **Modular Structure**: Separate script for core functions (`db`) and one for menu interaction.

---

## 📁 Project Structure

```bash
simple-bash-db/
├── db          # Contains all core functions (init, create, read, update, delete)
├── menu        # Main script with menu interface
├── data.txt    # The CSV file (auto-generated)
```

---

## 🛠️ Technologies Used

* Bash (Shell Scripting)
* Linux command-line tools (`sed`, `grep`, `column`, `cut`, `tail`)
* Regex for validation
* CSV file handling

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/simple-bash-db.git
cd simple-bash-db
```

2. **Make scripts executable**

```bash
chmod +x db menu
```

3. **Start the menu interface**

```bash
./menu
```

---

## ▶️ Sample Run

```
====== Simple Bash Database ======
1. Initialize Database
2. Create Entry
3. Read All Entries
4. Update Entry
5. Delete Entry
6. Exit
==================================
Choose an option [1-6]:
```
## 📸 Screenshots / Demo

    Running the menu
   ![1](https://github.com/user-attachments/assets/dc6103a1-cf1c-4272-b88a-047036944897)

    Option 1: Intialize Database
   ![2](https://github.com/user-attachments/assets/0e7934a5-69c3-441e-992a-3a51503ffade)

    Option 2: Create Entry
  ![3](https://github.com/user-attachments/assets/2baa505e-8799-440f-94d1-c05e3b3bba51)

    Option 2: Create Entry (Email Validation)
   ![4 email validation](https://github.com/user-attachments/assets/9421c748-a750-4b56-877a-dd5061080af4)

     Option 2: Create Entry (Name Validation)
  ![5 name validation](https://github.com/user-attachments/assets/6a7a26e3-bef0-4243-a72d-da9b4a1409d6)

    Option 3: Read All Entries
  ![6 read entry](https://github.com/user-attachments/assets/1f7ddcb6-5e0b-4ede-a1c0-ceb49842d1c6)

    Option 4: Update Entry
  ![7 update](https://github.com/user-attachments/assets/61b68fc2-b9bd-417d-9c99-5632d5dfc5c3)

    Option 5: Delete Entry
  ![8 delete](https://github.com/user-attachments/assets/62c8d5bb-5c13-47aa-a4ef-5b5d59a00043)
  
    Option 6: Exiting
  ![9 exit](https://github.com/user-attachments/assets/20e84c71-a948-4aae-8942-2235a8a7bcd8)

## 📌 Author

**@yourusername** — proudly built for learning and refining Bash scripting.

Feel free to contribute or fork the repo!

---

## 🪪 License

MIT License — open for use and modification.
