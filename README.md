## Usage
Autofill SMS Verification Code via `sms` keyword

![sms](https://github.com/roodq3/alfred-workflow-sms-code/assets/2068890/2b2b712d-cff1-4d25-ac8e-6d322acceafe)

![sms_code](https://github.com/roodq3/alfred-workflow-sms-code/assets/2068890/2c503c7c-959a-4e69-a149-c97420ec16ff)

* <kbd>↩</kbd>: Fill.

## Requirements

### 1. Install SQLite

This workflow requires SQLite, a lightweight database engine, to be installed on your MacOS system.

#### Installation Steps for MacOS:

- SQLite usually comes pre-installed on MacOS.
- To check if SQLite is installed, open the Terminal and type `sqlite3 --version`.
- If it's not installed or you need to update it, you can use Homebrew:
  - Install Homebrew by running `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` in the Terminal.
  - Then, install SQLite by running `brew install sqlite`.

### 2. Allowing Full Disk Access for Alfred

In MacOS, it is necessary to give Full Disk Access to Alfred to enable it to interact seamlessly with system files and other applications.

#### Steps to Allow Full Disk Access for Alfred:

1. Open "System Preferences" on your Mac.
2. Go to "Security & Privacy".
3. Select the "Privacy" tab.
4. Scroll down and select "Full Disk Access" from the sidebar.
5. Click the lock icon at the bottom left to make changes (you might need to enter your administrator password).
6. Click the '+' button and navigate to Alfred in your Applications folder.
7. Select Alfred and ensure that the checkbox next to it is checked.
8. Close System Preferences and restart Alfred for the changes to take effect.
