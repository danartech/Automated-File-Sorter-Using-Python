# Automated File Sorter Using Python

This project demonstrates the creation of an automated file sorter for organizing files in File Explorer. The script sorts files into designated folders based on their file types, providing a practical solution for managing large volumes of files efficiently.

## Project Overview

This project was inspired by the YouTube video ["Building an Automated File Sorter in File Explorer using Python"](https://www.youtube.com/watch?v=gs0FNQR0njI). The objective is to automate the process of sorting files into appropriate folders without manual intervention.

## Features

- **Automatic File Sorting**: Sorts files into folders based on their extensions (e.g., `.png`, `.csv`, `.txt`).
- **Folder Creation**: Automatically creates folders if they do not already exist.
- **File Movement**: Moves files into the correct folders based on their type.
- **Scalability**: Can handle sorting large volumes of files, saving significant time and effort.

## Project Structure

- **Main Script**: [`Automatic File Sorter.ipynb`](https://github.com/danartech/Automated-File-Sorter-Using-Python/blob/main/Automatic%20File%20Sorter.ipynb)
- **Output Example**: [`Python project sample.csv`](https://github.com/danartech/Automated-File-Sorter-Using-Python/blob/main/Python%20project%20sample.csv)
- **Python Screenshot**: ![Screenshot](https://github.com/danartech/Automated-File-Sorter-Using-Python/blob/main/Screenshot%202024-06-21%20152245.png)
- **File Explorer Screenshot**: ![Screenshot](https://github.com/danartech/Automated-File-Sorter-Using-Python/blob/main/Screenshot%202024-06-21%20152156.png)
- **File Sorted Screenshot**: ![Screenshot](https://github.com/danartech/Automated-File-Sorter-Using-Python/blob/main/Screenshot%202024-06-21%20152440.png)


## How It Works

1. **Import Libraries**: The script uses the `os` and `shutil` libraries to perform file operations.
2. **Define Paths**: Specifies the path to the directory containing the files to be sorted.
3. **Check and Create Folders**: Checks if the target folders (e.g., `CSV Files`, `Image Files`, `Text Files`) exist; if not, it creates them.
4. **Sort Files**: Loops through the files in the directory, checks their extensions, and moves them to the corresponding folders.

## Contact Me

- **Email**: [danarfintech@gmail.com](mailto:danarfintech@gmail.com)
- **LinkedIn**: [Dana Robinson](https://www.linkedin.com/in/dana-robinson-acct)
- **Portfolio Website**: [Dana's Portfolio](https://danartech.github.io/DanaTheAnalyst.github.io/)
