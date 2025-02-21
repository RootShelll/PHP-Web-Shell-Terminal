# PHP Web Shell Terminal

PHP Web Shell Terminal is an educational tool that allows users to interact with servers through custom commands. Learn how to install, use, and optimize the terminal for educational purposes. This tool is intended to be used only on servers you own or control.

![PHP-Web-Shell-Terminal](https://r00t-shell.com/wp-content/uploads/2025/02/PHP-Web-Shell-Terminal.png)
*Image Caption: PHP-Web-Shell-Terminal Interface*

## Features

- **Command History**: View a list of previously executed commands.
- **Terminal Screen Clearing**: Clear the terminal screen with the `clear` command.
- **Help Command**: Displays a help message with available commands.
- **File Viewing**: Open and view file content with `open <file>` or scroll through it with `less <file>`.
- **File Upload**: Upload files to specific directories using the `upload <dir>` command.
- **PHP Info**: View the PHP configuration information via the `open /phpinfo` command.

## Additional Features

The terminal supports file obfuscation. The file `terminal.php` is an obfuscated version of the main `terminal.php` file, adding an extra layer of security and making it harder for external users to reverse-engineer the code.

> **Important:** Always ensure that the server you are using this script on is your own. Unauthorized use may lead to legal consequences.

## Installation

Follow these steps to install the PHP Web Shell Terminal on your server:

1. Download the `terminal.php` file from the GitHub repository.
2. Upload the file to your server, preferably to a secure location.
3. Access the `terminal.php` file through a web browser by navigating to the uploaded location (e.g., `http://yourdomain.com/terminal.php`).
4. Enter your desired commands directly into the terminal and start using it.

## Available Commands

- `history` - Displays a list of previously executed commands.
- `clear` - Clears the terminal screen.
- `help` - Displays a help message with available commands.
- `open <file>` - Opens a file and displays its content in a new window as plain text.
- `open /phpinfo` - Displays the PHP info page in a new window.
- `upload <dir>` - Uploads an attached file to a specified directory on the server (e.g., `upload /tmp/`).
- `less <command>` - Allows you to view the contents of a file with the ability to scroll. Press `q` to quit or `space` to page down. Example: `less cat index.php`.
- `lessl <command>` - Similar to `less` but with line numbers for better readability.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
