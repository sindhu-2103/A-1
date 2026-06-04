# DevOps Assignment: Linux Basics

## 1. Creating and Renaming Files/Directories

### Commands

```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt
cd ..
```

### Explanation

The `mkdir` command creates a new directory named `test_dir`. Inside the directory, `touch` creates an empty file named `example.txt`. The `mv` command renames `example.txt` to `renamed_example.txt`.

Screenshot: `screenshots/01_create_and_rename.png`

---

## 2. Viewing File Contents

### Commands

```bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

### Explanation

The `cat` command displays the complete contents of `/etc/passwd`. The `head -n 5` command displays the first five lines. The `tail -n 5` command displays the last five lines.

Screenshot: `screenshots/02_view_file_contents.png`

---

## 3. Searching for Patterns

### Command

```bash
grep root /etc/passwd
```

### Explanation

The `grep` command searches for a specific word or pattern in a file. Here, it displays all lines containing the word `root` in `/etc/passwd`.

Screenshot: `screenshots/03_grep_root.png`

---

## 4. Zipping and Unzipping

### Commands

```bash
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir
```

### Explanation

The `zip -r` command compresses the `test_dir` directory into `test_dir.zip`. The `unzip` command extracts the zip file into a new directory named `unzipped_dir`.

Screenshot: `screenshots/04_zip_unzip.png`

---

## 5. Downloading Files

### Command

```bash
wget -O sample.txt https://example.com/
```

### Explanation

The `wget` command downloads files from the internet. The `-O sample.txt` option saves the downloaded content with the file name `sample.txt`.

Screenshot: `screenshots/05_wget_download.png`

---

## 6. Changing Permissions

### Commands

```bash
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt
```

### Explanation

The `touch` command creates an empty file named `secure.txt`. The `chmod 444` command changes the file permissions to read-only for owner, group, and others. The `ls -l` command verifies the permission change.

Screenshot: `screenshots/06_chmod_permissions.png`

---

## 7. Working with Environment Variables

### Commands

```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

### Explanation

The `export` command creates an environment variable named `MY_VAR`. The `echo $MY_VAR` command displays the value stored in the variable.

Screenshot: `screenshots/07_environment_variable.png`

---

## Conclusion

In this assignment, I practiced basic Linux commands used for file management, viewing file contents, searching text, compressing files, downloading files, changing permissions, and creating environment variables.
