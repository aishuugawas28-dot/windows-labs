#  Lab 02 - Windows User Management

##  Objective

Learn how to manage local user accounts and groups in Windows using Command Prompt.

---

##  Environment

- Operating System: Windows 11 Pro (VirtualBox)
- Platform: Oracle VirtualBox
- Command Line: Command Prompt (Administrator)

---

##  Commands Performed

### 1. Display Current Logged-in User

```cmd
whoami
```

---

### 2. List All Local Users

```cmd
net user
```

---

### 3. Display User Details

```cmd
net user testuser
```

---

### 4. Create a New Local User

```cmd
net user testuser P@ss123 /add
```

---

### 5. View Available Local Groups

```cmd
net localgroup
```

---

### 6. View Members of the Administrators Group

```cmd
net localgroup administrators
```

---

### 7. View Members of the Users Group

```cmd
net localgroup users
```

---

### 8. Delete the Test User

```cmd
net user testuser /delete
```

---

### 9. Verify User Deletion

```cmd
net user
```

---

#  Screenshots

All screenshots are available inside the **screenshots/** folder.

- whoami
- net user
- testuser details
- create user
- local groups
- administrators group
- users group
- delete user
- verify deletion

---

#  What I Learned

- Managing local Windows users
- Creating and deleting user accounts
- Viewing user account information
- Understanding local Windows groups
- Using Command Prompt with Administrator privileges

---

#  Real-World Use Cases

- Creating employee accounts
- Managing local administrators
- Removing inactive users
- Troubleshooting Windows login issues
- Basic Windows system administration
- IT Support and Help Desk operations

---

#  Lab Status

**Completed Successfully**
