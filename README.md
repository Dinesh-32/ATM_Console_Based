# ATM_Console_Based
Here’s a description for your README file:  

---

# ATM Simulation in Python  

This is a simple **ATM simulation program** written in Python. It allows users to perform basic banking operations like **withdrawals, deposits, PIN generation, and checking account details**. The program uses a dictionary to store account details and continuously runs in a loop until the user chooses to exit.  

## Features  

✅ **Withdrawal** – Users can withdraw money from their account after entering a valid PIN.  
✅ **Deposit** – Users can deposit money into their account.  
✅ **PIN Generation** – Users can set a PIN if they don’t have one.  
✅ **Mini Statement** – Users can check their account details, including balance and date of birth.  
✅ **Exit Option** – Allows users to exit the program.  

## How It Works  

1. The program starts with a welcome message and displays the main menu.  
2. Users select an option (1-5).  
3. If an option requires authentication, the user must enter a valid **account number and PIN**.  
4. The program processes the request and displays the appropriate message.  
5. The loop continues until the user selects **Exit (Option 5)**.  

## Account Data Structure  

The account details are stored in a Python dictionary with the following structure:  

```python
accounts = {
    1111 : ["dinesh","05-11-2024",30000,1234],  # Account number: [Name, DOB, Balance, PIN]
    2222 : ["abhishek","07-07-2024",20000,5678],
    3333 : ["ram","25-05-2024",6000,None]  # No PIN set initially
}
```

## How to Run the Program  

1. Copy the Python script into a file, e.g., `atm.py`.  
2. Run the script using Python:  

   ```sh
   python atm.py
   ```

3. Follow the on-screen instructions to interact with the ATM.  

## Future Improvements  

🔹 Implement user authentication with **username and password**.  
🔹 Add a **transaction history** feature.  
🔹 Improve **error handling** for invalid inputs.  

---

This README gives a clear overview of your project. Let me know if you need any changes! 🚀
