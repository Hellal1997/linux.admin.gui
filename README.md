# linux.admin.gui

# Features

🔑 **Key Highlights:**
- **Divided into Two Sections:** The project is split into two main parts—User Administration and Group Administration. Each section contains tasks tailored to its focus.

  **User Management:**
  - **Add User:**
    - Quickly add new users to the system with an interactive prompt.
    - Checks if the username already exists to avoid conflicts.
  - **Modify User:**
    - Update user details such as home directory, UID, primary group, and more.
    - Features include:
      - **Allow Bad Names:** Enable usernames that don’t meet default naming conventions.
      - **Change Home Directory:** Specify a new home directory for an existing user.
      - **Set Primary Group:** Change the primary group of a user.
      - **Lock/Unlock Account:** Temporarily disable or re-enable user accounts.
      - **Change UID:** Assign a new User ID to an existing account.
      - **Append Groups:** Add the user to additional groups without affecting current memberships.
    - Automatically checks if the user exists before attempting any modifications.
  - **Delete User:**
    - Safely remove users from the system with confirmation prompts to prevent accidental deletions.
    - Validates user existence before proceeding with deletion.

  **Group Management:**
  - **Add Group:**
    - Create new groups with ease, ensuring group names are unique.
  - **Modify Group:**
    - Update group details, including member lists.
    - Checks if the group exists before allowing modifications.
  - **Delete Group:**
    - Remove groups from the system with confirmation prompts.
    - Validates group existence before proceeding with deletion.

  **Account Control:**
  - **Disable User:** Lock user accounts to prevent login, ensuring the user exists before locking the account.
  - **Enable User:** Unlock user accounts, restoring login capabilities.
  - **Change Password:** Change a user’s password securely.

  **System Information:**
  - **List Users:** Display a list of all users currently on the system.
  - **List Groups:** Display all groups on the system, including their associated members.
  - **About:** Get detailed information about the system, including the operating system version, hostname, uptime, and more.

## Installation

Clone this repository and run the script on your Linux system:

```bash
git clone https://github.com/Hellal1997/linux.admin.gui.git
cd Linux-Admin-GUI
chmod +x *
./MainMenu

# Usage
Follow the on-screen prompts to manage users and groups efficiently. The menu-driven interface guides you through each step, ensuring a smooth and error-free experience.

![mainmenu1](https://github.com/user-attachments/assets/4a569a1b-2b06-4bd0-a432-a31523fc628a)
