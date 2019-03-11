# bookish-couscous
A consolidation of the course Mathematics for Machine Learning: Linear Algebra

Jupyter Notebooks can be used with the anaconda navigator:

1. Load the anaconda navigator.

2. Launch Jupyter Notebook.

3. Upload the notebook.

4. Run the notebook and view/edit the code accordingly.

Anaconda, and thus the navigator, can be attained via the following method:

Windows:  

1. Go to the Anaconda Website and choose a Python 3.x graphical installer (A) or a Python 2.x graphical installer (B). If you aren't sure which Python version you want to install, choose Python 3. Do not choose both.

2. Locate your download and double click it.

3. Click "next" once you're able.

4. Read the license agreement and, assuming you agree, click on "I Agree".

5. Click "next" once you're able.

6. Note the installation location (or change it if you like, but make sure it's remembered) and click "next".

7. This is an important part of the installation process. The recommended approach is to not check the box to add Anaconda to your path. This means you will have to use Anaconda Navigator or the Anaconda Command Prompt (located in the Start Menu under "Anaconda") when you wish to use Anaconda (you can always add Anaconda to your PATH later if you don't check the box).

8. You can install Microsoft VSCode if you wish, but it is optional.

9. Click "Finish".

Linux:

For x86 systems.

1. In your browser, download the Anaconda installer for Linux.

  1a. Optional: Verify data integrity with MD5 or SHA-256. (For more information on hashes, see cryptographic hash validation.)

  1b. Run the following:

  1c. md5sum /path/filename  OR:  sha256sum /path/filename

  1d. NOTE: Replace /path/filename with the actual path and filename of the file you downloaded.

  1e. Optional: Verify results against the proper hash page to make sure the hashes match.

2. Enter the following to install Anaconda for Python 3.7:

    bash ~/Downloads/Anaconda3-5.3.0-Linux-x86_64.sh

    OR Enter the following to install Anaconda for Python 2.7:

    bash ~/Downloads/Anaconda2-5.3.0-Linux-x86_64.sh

  2b. NOTE: Include the bash command regardless of whether or not you are using Bash shell.

  2c. NOTE: If you did not download to your Downloads directory, replace ~/Downloads/ with the path to the file you downloaded.

  2d. NOTE: Choose “Install Anaconda as a user” unless root privileges are required.

3. The installer prompts “In order to continue the installation process, please review the license agreement.” Click Enter to view license terms. Scroll to the bottom of the license terms and enter “Yes” to agree.

4. The installer prompts you to click Enter to accept the default install location, CTRL-C to cancel the installation, or specify an alternate installation directory. If you accept the default install location, the installer displays “PREFIX=/home/<user>/anaconda<2 or 3>” and continues the installation. It may take a few minutes to complete.

5. The installer prompts “Do you wish the installer to prepend the Anaconda<2 or 3> install location to PATH in your /home/<user>/.bashrc ?” Enter Yes.

  5b. NOTE: If you enter “No”, you must manually add the path to Anaconda or conda will not work. See FAQ.

6. The installer describes Microsoft VS Code and asks if you would like to install VS Code. Enter yes or no. If you selected yes, follow the instructions on screen to complete the VS Code installation.

  6b. NOTE: Installing VS Code with the Anaconda installer requires an internet connection. Offline users may be able to find an offline VS Code installer from Microsoft.

  6c. The installer finishes and displays “Thank you for installing Anaconda<2 or 3>!”

7. Close and open your terminal window for the installation to take effect, or you can enter the command source ~/.bashrc.

8. After your install is complete, verify it by opening Anaconda Navigator, a program that is included with Anaconda: Open a Terminal window and type anaconda-navigator. 

  8b. If Navigator opens, you have successfully installed Anaconda. If not, check that you completed each step above.
  
  8c. If you have completed each step above and it still doesn't load, the script is in the bin folder and can be loaded manually.
