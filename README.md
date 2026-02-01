  Complete Linux Documentation /\* Reset and Base Styles \*/ \* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; } body { background-color: #f5f7fa; color: #333; line-height: 1.6; } /\* Header and Navigation \*/ header { background: linear-gradient(135deg, #1f2937 0%, #374151 100%); color: white; padding: 20px 0; position: sticky; top: 0; z-index: 100; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); } .nav-container { max-width: 1200px; margin: 0 auto; padding: 0 20px; display: flex; justify-content: space-between; align-items: center; } .logo h1 { font-size: 1.8rem; margin-bottom: 5px; } .logo p { font-size: 0.9rem; opacity: 0.8; } nav ul { display: flex; list-style: none; } nav li { margin-left: 25px; } nav a { color: white; text-decoration: none; padding: 8px 12px; border-radius: 4px; transition: background-color 0.3s; } nav a:hover { background-color: rgba(255, 255, 255, 0.1); } /\* Main Container \*/ .container { max-width: 1200px; margin: 0 auto; padding: 30px 20px; } /\* Basics Sections \*/ .basics-section { background: white; margin-bottom: 30px; padding: 25px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08); border-left: 4px solid #3b82f6; } .basics-section h2 { margin-top: 0; color: #111827; border-bottom: 2px solid #e5e7eb; padding-bottom: 10px; margin-bottom: 20px; } /\* Tables \*/ table { width: 100%; border-collapse: collapse; margin-top: 15px; margin-bottom: 20px; } table th, table td { border: 1px solid #e5e7eb; padding: 12px; text-align: left; } table th { background: #f3f4f6; font-weight: 600; } table tr:nth-child(even) { background-color: #f9fafb; } /\* Code Styling \*/ code { background: #eef2ff; padding: 2px 6px; border-radius: 4px; font-size: 90%; font-family: 'Courier New', monospace; } /\* Lists \*/ ul { margin: 10px 0 0 20px; } li { margin-bottom: 8px; } /\* Command Documentation Styles \*/ .content-grid { display: grid; grid-template-columns: 1fr; gap: 25px; margin-top: 30px; } @media (min-width: 768px) { .content-grid { grid-template-columns: 1fr 1fr; } } @media (min-width: 1024px) { .content-grid { grid-template-columns: 1fr 1fr 1fr; } } .card { background: white; border-radius: 10px; padding: 25px; box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05); transition: transform 0.3s ease, box-shadow 0.3s ease; border-top: 4px solid #3498db; } .card:hover { transform: translateY(-5px); box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1); } .card:nth-child(2) { border-top-color: #2ecc71; } .card:nth-child(3) { border-top-color: #e74c3c; } .card:nth-child(4) { border-top-color: #f39c12; } .card:nth-child(5) { border-top-color: #9b59b6; } .card-title { font-size: 1.5rem; margin-bottom: 15px; color: #2c3e50; display: flex; align-items: center; } .card-title i { margin-right: 10px; font-size: 1.3rem; } .command-list { list-style-type: none; margin: 0; } .command-list li { padding: 8px 0; border-bottom: 1px solid #eee; display: flex; align-items: flex-start; } .command-list li:last-child { border-bottom: none; } .command { background-color: #f8f9fa; font-family: 'Courier New', monospace; padding: 3px 8px; border-radius: 4px; border-left: 3px solid #3498db; margin-right: 10px; min-width: 200px; flex-shrink: 0; } .description { color: #555; } /\* Terminal \*/ .terminal { background-color: #2c3e50; color: #ecf0f1; border-radius: 8px; padding: 20px; margin-top: 20px; overflow-x: auto; font-family: 'Courier New', monospace; box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.3); } .terminal .prompt { color: #2ecc71; } .terminal .command { color: #3498db; border: none; background: none; padding: 0; min-width: auto; } .terminal .output { color: #bdc3c7; margin-top: 10px; } /\* Time Stamps \*/ .time-stamps { background-color: #fff; border-radius: 10px; padding: 25px; margin-top: 20px; box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05); } .time-item { margin-bottom: 15px; padding-bottom: 15px; border-bottom: 1px solid #eee; } .time-item:last-child { border-bottom: none; margin-bottom: 0; padding-bottom: 0; } .time-label { font-weight: bold; color: #2c3e50; display: inline-block; min-width: 150px; } /\* Notes and Tips \*/ .note { background-color: #fff8e1; border-left: 4px solid #ffc107; padding: 15px; margin: 20px 0; border-radius: 0 4px 4px 0; } .user-switch { background-color: #e8f4fc; border-radius: 8px; padding: 15px; margin-top: 15px; border-left: 4px solid #3498db; } /\* Icons \*/ .icon { display: inline-block; width: 30px; text-align: center; margin-right: 8px; } /\* Footer \*/ footer { text-align: center; margin-top: 50px; padding: 20px; color: #6b7280; font-size: 0.9rem; border-top: 1px solid #eee; } /\* Section Headers \*/ h2 { margin: 40px 0 20px; color: #2c3e50; border-bottom: 2px solid #3498db; padding-bottom: 10px; } h3 { margin: 25px 0 15px; color: #2c3e50; } /\* Back to Top Button \*/ .back-to-top { position: fixed; bottom: 30px; right: 30px; background-color: #3b82f6; color: white; width: 50px; height: 50px; border-radius: 50%; display: flex; align-items: center; justify-content: center; text-decoration: none; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2); opacity: 0; transition: opacity 0.3s; } .back-to-top.show { opacity: 1; } /\* Responsive Design \*/ @media (max-width: 768px) { .nav-container { flex-direction: column; text-align: center; } nav ul { margin-top: 15px; flex-wrap: wrap; justify-content: center; } nav li { margin: 5px; } .content-grid { grid-template-columns: 1fr; } .command-list li { flex-direction: column; } .command { margin-bottom: 5px; min-width: auto; } }  

Complete Linux Documentation
============================

From Fundamentals to Advanced Commands

*   [Fundamentals](#basics)
*   [Commands](#commands)
*   [Timestamps](#timestamps)
*   [Examples](#examples)

Linux Fundamentals & Basics
---------------------------

### Windows vs Linux Path Structure

*   **Windows:** Uses backward slash `\` (example: `C:\Program Files`)
*   **Linux:** Uses forward slash `/` (example: `/home/user`)

Linux Root Directory Structure
------------------------------

Linux follows a single top-level root directory represented by `/`.

Directory

Description

`/`

Top-level root directory

`/root`

Home directory of the root user

`/home`

Home directories for normal users

`/boot`

Contains bootloader and bootable files

`/etc`

System-wide configuration files

`/bin`

Essential commands used by all users

`/sbin`

System commands mainly used by root user

`/usr`

User-installed software and libraries

`/opt`

Optional application packages

`/dev`

Device and terminal files

Linux Fundamentals
------------------

*   Open-source operating system
*   Secure and stable
*   Lightweight compared to other operating systems
*   Supports multitasking
*   Multiuser system
*   Available in multiple distributions (Ubuntu, Amazon Linux, CentOS, etc.)

CPU & Users Concept
-------------------

*   Linux supports multiple users working at the same time
*   CPU resources are shared between users and processes
*   No need for extra RAM per user; efficient resource usage

File & Directory Structure
--------------------------

*   Everything in Linux is treated as a file
*   Directories store files and subdirectories
*   Packages are installed in predefined directories

Important Commands (Basics)
---------------------------

*   `cat` – Display file content
*   `touch` – Create an empty file
*   `ls` – List files and directories
*   `pwd` – Show current directory

Linux Command Documentation
---------------------------

### File Creation Methods

*   cat > filename
    
    Create and edit a file
    
*   touch filename
    
    Create empty file or update timestamps
    
*   vi/vim filename
    
    Create/edit with text editor
    
*   nano filename
    
    Create/edit with nano editor
    

### Cat Command Uses

*   cat file
    
    Display file content
    
*   cat > file
    
    Create new file (Ctrl+D to save)
    
*   cat file1 file2
    
    Concatenate and display multiple files
    
*   cat file1 file2 > all
    
    Combine files into new file
    

### Touch Command Options

*   touch file1 file2...
    
    Create empty files
    
*   touch -a file
    
    Update only access time
    
*   touch -m file
    
    Update only modify time
    
*   touch file.s
    
    Create file with extension
    

File Time Stamps
----------------

Access Time: Last time a file was accessed/read

Modify Time: Last time a file's content was modified

Change Time: Last time a file's metadata was changed (permissions, ownership, etc.)

**Note:** Use the `stat` command to get detailed file metadata including all three timestamps.

Command Examples
----------------

### Cat Command Examples

\[user@ip\] $ cat > file1

\# Type content, then press Ctrl+D to save

what is this

how are you

thank you - to client

  

\[user@ip\] $ cat file1

what is this

how are you

thank you - to client

  

\[user@ip\] $ cat file1 file2 > all

\# Combines file1 and file2 into new file 'all'

### Touch Command Examples

\[root@ip\] $ touch file1, file2, file3, file4

\# Creates four empty files

  

\[root@ip\] $ touch file2.s

\# Creates file with .s extension

  

\[root@ip\] $ touch -a file3

\# Updates only the access time of file3

  

\[root@ip\] $ touch -m file4

\# Updates only the modify time of file4

User Management (Amazon Linux)
------------------------------

\[ec2-user@ip\] $ sudo su

\# Switch to superuser/root (super user do switch user)

  

\[root@ip\] # \# Now you have root privileges

**Amazon Linux Default:** Login as `ec2-user`, then use `sudo su` to switch to root user.

File Metadata & Locking
-----------------------

\[root@ip\] $ stat file1

\# Displays file metadata including timestamps, size, permissions, etc.

  

\[root@ip\] $ ls -list

\# List files with detailed information

  

\[root@ip\] $ lock file1.s

\# Lock a file (conceptual - actual locking may vary)

**Tip:** The `stat` command provides comprehensive file information including all three timestamps (Access, Modify, Change), file size, inode, permissions, and more.

Complete Linux Documentation | From Fundamentals to Advanced Commands

Includes: Linux basics, directory structure, cat, touch, file operations, timestamps, user management

[](#)// Add a simple interaction to highlight code when clicked document.addEventListener('DOMContentLoaded', function() { const commands = document.querySelectorAll('.command'); commands.forEach(cmd => { cmd.addEventListener('click', function() { const originalColor = this.style.backgroundColor; this.style.backgroundColor = '#e3f2fd'; setTimeout(() => { this.style.backgroundColor = originalColor; }, 300); }); }); // Make terminal prompts copyable const terminalPrompts = document.querySelectorAll('.terminal .command'); terminalPrompts.forEach(prompt => { prompt.style.cursor = 'pointer'; prompt.title = 'Click to select command'; prompt.addEventListener('click', function() { const textToCopy = this.textContent; navigator.clipboard.writeText(textToCopy).then(() => { const originalText = this.textContent; this.textContent = 'Copied!'; this.style.color = '#2ecc71'; setTimeout(() => { this.textContent = originalText; this.style.color = '#3498db'; }, 1000); }); }); }); // Smooth scrolling for navigation links document.querySelectorAll('nav a').forEach(anchor => { anchor.addEventListener('click', function(e) { e.preventDefault(); const targetId = this.getAttribute('href'); if (targetId === '#') return; const targetElement = document.querySelector(targetId); if (targetElement) { window.scrollTo({ top: targetElement.offsetTop - 80, behavior: 'smooth' }); } }); }); // Back to top button functionality const backToTopButton = document.getElementById('backToTop'); window.addEventListener('scroll', function() { if (window.scrollY > 300) { backToTopButton.classList.add('show'); } else { backToTopButton.classList.remove('show'); } }); backToTopButton.addEventListener('click', function(e) { e.preventDefault(); window.scrollTo({ top: 0, behavior: 'smooth' }); }); });
