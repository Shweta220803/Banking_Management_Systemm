# Bank Managment System in Java

A basic banking system, providing account login, creation, balance inquiry, fund transfers, Bank Statement and more. 

## Features

- `Login:` Existing customers can log in to their accounts.
- `Create Account:` New customers can create a new bank account.
- `Balance Inquiry:` Customers can check their account balance.
- `Account Details:` Customers can view their account information.
- `Fund Transfer:` Customers can transfer funds to other accounts.
- `Transaction History:` View transaction history.
- `Account Closure:` Customers can close their bank accounts.

## Usage

Upon running the program, you will be prompted with two options:
1. `Login:` Enter 1 to log in to your existing account.
2. `Create Account:` Enter 2 to create a new bank account.

For existing customers:
- Enter your account number and PIN to log in. (ID & Password is located in credentials.txt)
- After successful login, you will be presented with a menu to access various banking features.

For new customers:
- Follow the instructions to create a new account, providing necessary details.

## Project Structure
The project consists of the following main classes:

- `Main:` The main class that serves as the entry point to the program. It provides the user with options to log in or create a new account.
- `Login:` This class handles the login functionality. It validates the user's credentials and allows them to access their account.
- `Creation:` This class facilitates the creation of new bank accounts.
- `BalanceInquiry:` This class provides the functionality to check the balance in a user's account.
- `AccountDetails:` This class allows users to view their account details.
- `Transaction:` This class enables users to transfer funds from one account to another.
- `Deletion:` This class handles the closure of user accounts, deleting their data from the system.

## File Structure
The project utilizes several files to store and manage data:

- credentials.txt: This file stores the username and password information of all registered users.
- userDB.txt: This file holds the account details of all registered users, such as their account number, name, and contact information.
- balanceDB.txt: This file maintains the account balance for all users.
- acc_[accNo].txt: This file maintains the transaction of each account.

# Our Team 

<table>
    <tbody>
      <tr>
        <th>Team Name </th>
        <td>Tech Army</td></tr>
      <tr>
        <th>Project Title</th>
        <td>Banking Management Sysytem </td>
      </tr>
    <tr>
        <th>Team Member info </th>
        <td>
            <ul>
                <li>Ansh Raj [21BTCSE1037]</li> 
                <li>Aryan Goel [21BTCSE1020]</li> 
                <li>Deepak Rawat [21BTCSE1057]</li>
                <li>Mohan Naudiyal [21BTCSE1058]</li>
                <li>Shweta Bharti [21BTCSE1065]</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>Technologies info </th>
        <td>
          <ul>
            <li>Java</li>
            <li>File Handling</li>
            <li>Console Based Application </li>
          </ul>
        </td>
    </tr>
</tbody>
</table>
