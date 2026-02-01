# Complete Linux Documentation  
**From Fundamentals to Advanced Commands**

---

## Table of Contents

- [Linux Fundamentals & Basics](#linux-fundamentals--basics)
- [Linux Command Documentation](#linux-command-documentation)
- [File Time Stamps](#file-time-stamps)
- [Command Examples](#command-examples)
- [User Management (Amazon Linux)](#user-management-amazon-linux)
- [File Metadata & Locking](#file-metadata--locking)

---

## Linux Fundamentals & Basics

### Windows vs Linux Path Structure

- **Windows**: Uses backward slash `\`  
  Example: `C:\Program Files`
- **Linux**: Uses forward slash `/`  
  Example: `/home/user`

### Linux Root Directory Structure

Linux follows a single top-level root directory represented by `/`.

| Directory   | Description                                      |
|-------------|--------------------------------------------------|
| `/`         | Top-level root directory                         |
| `/root`     | Home directory of the root user                  |
| `/home`     | Home directories for normal users                |
| `/boot`     | Contains bootloader and bootable files           |
| `/etc`      | System-wide configuration files                  |
| `/bin`      | Essential commands used by all users             |
| `/sbin`     | System commands mainly used by root user         |
| `/usr`      | User-installed software and libraries            |
| `/opt`      | Optional application packages                    |
| `/dev`      | Device and terminal files                        |

### Linux Fundamentals

- Open-source operating system
- Secure and stable
- Lightweight compared to other operating systems
- Supports multitasking
- Multiuser system
- Available in multiple distributions (Ubuntu, Amazon Linux, CentOS, Fedora, Debian, Arch, etc.)

### CPU & Users Concept

- Linux supports multiple users working simultaneously
- CPU resources are shared between users and processes
- No need for extra RAM per user → efficient resource usage

### File & Directory Structure

- **Everything in Linux is treated as a file**
- Directories store files and subdirectories
- Packages are installed in predefined directories

### Important Commands (Basics)

- `cat`    – Display file content
- `touch`  – Create an empty file or update timestamps
- `ls`     – List files and directories
- `pwd`    – Show current working directory

---

## Linux Command Documentation

### File Creation Methods

- `cat > filename`        Create and edit a file (Ctrl+D to save)
- `touch filename`        Create empty file or update timestamps
- `vi` / `vim filename`   Create/edit with vi/vim text editor
- `nano filename`         Create/edit with nano editor (beginner friendly)

### `cat` Command Uses

- `cat file`              Display file content
- `cat > file`            Create new file (type content, Ctrl+D to save)
- `cat file1 file2`       Concatenate and display multiple files
- `cat file1 file2 > all` Combine files into new file named `all`

### `touch` Command Options

- `touch file1 file2 ...`      Create multiple empty files
- `touch -a file`              Update **only access time**
- `touch -m file`              Update **only modify time**
- `touch file.s`               Create file with `.s` extension

---

## File Time Stamps

Three main timestamps in Linux:

- **Access Time** (atime)  
  Last time a file was **accessed/read**

- **Modify Time** (mtime)  
  Last time a file's **content** was modified

- **Change Time** (ctime)  
  Last time a file's **metadata** was changed (permissions, ownership, etc.)

> **Tip**: Use the `stat` command to see all three timestamps + more details

```bash
stat filename
