# Task 1: Using Absolute Paths

## 1. Create an alias (abs_cp_mv) that performs the following tasks:
   - Copy the content of file1.txt located in `/home/user/Yash/dir1/subdir1/subsubdir1/` to a new file named file1_copy.txt in `/home/user/Yash/dir2/subdir2/subsubdir2/`.
   - Move file2.txt from `/home/user/Yash/dir2/subdir2/subsubdir2/` to `/home/user/Yash/backup_files/`.

# Task 2: Using Relative Paths

## 1. Create an alias (rel_cp_mv) that performs the following tasks:
   - Copy the content of file1.txt located in `Yash/dir1/subdir1/subsubdir1/` (relative to the current directory) to a new file named file1_copy.txt in `Yash/dir2/subdir2/subsubdir2/`.
   - Move file2.txt from `Yash/dir2/subdir2/subsubdir2/` (relative to the current directory) to `Yash/backup_files/`.

# Task 3: Combining Commands and Redirection

## 1. Create an alias (combined_task) that performs the following tasks:
   - Create a new directory named `new_dir` in the current directory.
   - Create a new file named `new_file.txt` in the `new_dir/` directory and write "This is a new file" into it using `echo` command.
   - Append the content of `new_file.txt` to `file1.txt` located in `Yash/dir1/subdir1/subsubdir1/`.
   - Copy the content of `file1.txt` located in `Yash/dir1/subdir1/subsubdir1/` to `file1_copy.txt` located in `new_dir/`.
   - Move `file2.txt` from `Yash/dir2/subdir2/subsubdir2/` to `new_dir/`.
   - Concatenate the contents of `file1_copy.txt` and `file2.txt` and redirect the output to a new file named `combined_content.txt` in `new_dir/`.

# Task 4: Using Alias for File Operations

## 1. Create an alias (file_ops) that performs the following tasks:
   - Create a new directory named `temp_dir` in the current directory.
   - Create a new file named `temp_file.txt` in the `temp_dir/` directory and write "Temporary file content" into it using `echo` command.
   - Copy `temp_file.txt` to `file3.txt` located in `Yash/dir1/subdir1/subsubdir1/`.
   - Move `file3.txt` from `Yash/dir1/subdir1/subsubdir1/` to `Yash/dir2/subdir2/subsubdir2/`.
   - Append the content of `temp_file.txt` to `file2.txt` located in `Yash/dir2/subdir2/subsubdir2/`.
   - Remove the `temp_dir/` directory and its contents.

# Task 5: Advanced File Management

## 1. Create an alias (adv_file_mgmt) that performs the following tasks:
   - Create a new directory named `advanced_files` in the current directory.
   - Create a new file named `important_info.txt` in the `advanced_files/` directory and write "Important information goes here" into it using `echo` command.
   - Copy `important_info.txt` to `backup_info.txt` located in `Yash/backup_files/`.
   - Move `file1.txt` from `Yash/dir1/subdir1/subsubdir1/` to `advanced_files/`.
   - Append the content of `file2.txt` located in `Yash/dir2/subdir2/subsubdir2/` to `important_info.txt`.
   - Copy `important_info.txt` to `file4.txt` located in `Yash/dir1/subdir1/subsubdir1/`.
   - Remove the `advanced_files/` directory and its contents.

# Task 6: Secure File Operations

## 1. Create an alias (secure_file_ops) that performs the following tasks:
   - Create a new directory named `secure_data` in the current directory.
   - Create a new file named `encrypted_data.txt` in the `secure_data/` directory and write "Encrypted data goes here" into it using `echo` command.
   - Copy `encrypted_data.txt` to `backup_encrypted.txt` located in `Yash/backup_files/`.
   - Move `file2.txt` from `Yash/dir2/subdir2/subsubdir2/` to `secure_data/`.
   - Append the content of `file1.txt` located in `Yash/dir1/subdir1/subsubdir1/` to `encrypted_data.txt`.
   - Encrypt `encrypted_data.txt` using a secure encryption algorithm.
   - Remove the `secure_data/` directory and its contents.
