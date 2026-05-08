# Wnano

Wnano is a customized, up-to-date distribution of GNU Nano for Windows.

## Installation

To install Wnano, follow these steps:

1. Go to the **Releases** section on the right side of this repository.
2. Download the **Source code** of the latest version.
3. Extract the ZIP file to a location of your choice (e.g., `C:\wnano`).

## Project Structure

Inside the extracted folder, you will find the following directory layout:

* **usr\bin**: Contains `nano.exe` and the necessary system libraries.
* **etc**: Contains the `nanorc` configuration file 
* **usr\share\nano**: Contains syntax highlighting files (e.g., `c.nanorc`, `python.nanorc`).

## Adding Wnano to PATH

To use the `wnano` command from any terminal window, you need to add the directory containing your launch script to your system's PATH environment variable:

1. Open the **Start Menu**, search for "Edit the system environment variables", and press Enter.
2. Click the **Environment Variables** button.
3. Under **System variables**, find and select the **Path** variable, then click **Edit**.
4. Click **New** and paste the full path to your `wnano` folder.
5. Click **OK** on all windows to save the changes.
6. Restart your terminal (Command Prompt, PowerShell, or Git Bash) for the changes to take effect.

## License

This project is distributed under the **GNU General Public License v3.0**. See the LICENSE file for more details.
