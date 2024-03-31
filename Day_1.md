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
