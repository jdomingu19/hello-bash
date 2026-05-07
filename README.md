# Hello, Bash!

![Static Badge](https://img.shields.io/badge/bash-5.2.37+-1C2024?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=101010)

**Learning Bash from Scratch!** Voluptate fugiat ea deserunt laboris. Excepteur nostrud occaecat nostrud elit anim. Irure reprehenderit nisi nulla eiusmod cillum cupidatat in laborum ullamco sit. Esse dolore id proident aliqua non aliquip id exercitation magna excepteur cupidatat anim laborum veniam. Eu aliqua commodo nulla ullamco. Aliqua voluptate tempor eu anim.

> Nisi cupidatat ex occaecat ut incididunt irure tempor laboris minim consequat ut. Anim laborum ad esse laboris duis elit officia in elit. Tempor veniam velit aliquip irure cupidatat adipisicing non aute fugiat in consequat eu. Exercitation voluptate nostrud est irure est consequat ipsum velit exercitation in aute consequat amet esse. Sunt incididunt enim do elit veniam sunt aute adipisicing aliqua ipsum sunt.

![header_hello_bash](https://github.com/user-attachments/assets/d407cd7a-b64e-43e8-9d13-d933c5f3c132)

## ❔ What's Bash

> Labore nulla incididunt nulla esse cupidatat. Incididunt id proident aliqua eu eiusmod quis excepteur reprehenderit cillum voluptate occaecat qui Lorem. Mollit eiusmod excepteur sit Lorem aliquip adipisicing consequat eiusmod cupidatat ea. Proident pariatur eiusmod ex irure irure laboris occaecat cillum ea elit ipsum aute esse ad.
>
> Eu ea Lorem elit laborum non velit aute adipisicing nostrud eiusmod adipisicing velit incididunt veniam. Elit tempor anim eu culpa laboris. Sunt duis dolor adipisicing do. Ad quis non magna eiusmod nulla laborum. Mollit aliqua et cillum veniam labore do officia voluptate cillum enim. Ex laboris magna sit enim excepteur reprehenderit deserunt. Ex id nisi nulla mollit.

## 🗂️ Repository Content

### → [`mouredev/`](./mouredev/)

> Aliquip cillum laborum aute et in incididunt in occaecat. Esse est magna consectetur sunt id elit et est nulla. Eiusmod id voluptate pariatur adipisicing aute qui consectetur. Non adipisicing dolor velit cillum laboris fugiat deserunt occaecat mollit pariatur.

### → [`playground/`](./playground/)

> Aliquip cillum laborum aute et in incididunt in occaecat. Esse est magna consectetur sunt id elit et est nulla. Eiusmod id voluptate pariatur adipisicing aute qui consectetur. Non adipisicing dolor velit cillum laboris fugiat deserunt occaecat mollit pariatur.

## 🎯 Repository Goals

> Qui ut ea aute labore nisi in mollit laboris. Eiusmod ipsum est velit nisi velit nulla sit duis. Duis nulla cupidatat incididunt sit velit. Ea consequat ut laboris labore ea veniam. Nostrud ad duis dolor aliqua mollit consequat commodo. Duis officia id sit magna ea ad tempor id laboris irure cupidatat ullamco id cillum.

## Basic Commands

These are the fundamental commands every developer should know. They cover file and directory management, navigation, and basic inspection.

> **1. Create a directory:** Make a new folder.
>
> ```bash
> mkdir <directory-name>
> ```

> **2. Change directory:** Move into a folder.
> 
> ```bash
> cd <directory-name>
> ```

> **3. List files:** Show contents of the current directory.
> 
> ```bash
> ls
> > ```

> **4. Show current path:** Display the working directory.
> 
> ```bash
> pwd
> ```

> **5. Create a file:** Generate an empty file.
> 
> ```bash
> touch <file-name>
> ```

> **6. Copy a file:** Duplicate a file to another location.
> 
> ```bash
> cp <source> <destination>
> ```

> **7. Move or rename a file:** Relocate or rename files.
> 
> ```bash
> mv <source> <destination>
> ```

> **8. Remove a file:** Delete a file permanently.
> 
> ```bash
> rm <file-name>
> ```

> **9. Remove a directory:** Delete a folder and its contents.
> 
> ```bash
> rm -r <directory-name>
> ```

> **10. View file contents:** Print the file to the terminal.
> 
> ```bash
> cat <file-name>
> ```

## Intermediate Commands

These commands help you inspect, measure, and manipulate files and processes more effectively.

> **11. Disk usage of a folder:** Show folder size.
> 
> ```bash
> du -sh <directory-name>
> ```

> **12. Disk usage of a file:** Show file size.
> 
> ```bash
> du -sh <file-name>
> ```

> **13. Find files by name:** Search recursively.
> 
> ```bash
> find . -name "<pattern>"
> ```

> **14. Count lines in a file:** Useful for scripts or logs.
> 
> ```bash
> wc -l <file-name>
> ```

> **15. Search text in files:** Find occurrences of a string.
> 
> ```bash
> grep "<text>" <file-name>
> ```

> **16. Copy directory recursively:** Duplicate entire folders.
> 
> ```bash
> cp -r <source-directory> <destination-directory>
> ```

> **17. Show hidden files:** Include dotfiles in listing.
> 
> ```bash
> ls -a
> ```

> **18. Show running processes:** Inspect active tasks.
> 
> ```bash
> ps aux
> ```

> **19. Kill a process:** Terminate by PID.
> 
> ```bash
> kill <pid>
> ```

> **20. Monitor system activity:** Real‑time process viewer.
> 
> ```bash
> top
> ```

## Advanced Commands

These commands provide powerful ways to automate, analyze, and manage your system.

> **21. Archive files:** Create a `.tar` archive.
> 
> ```bash
> tar -cvf archive.tar <files>
> ```

> **22. Extract archive:** Unpack .tar files.
> 
> ```bash
> tar -xvf archive.tar
> ```

> **23. Compress with gzip:** Reduce file size.
> 
> ```bash
> gzip <file-name>
> ```

> **24. Decompress gzip:** Restore compressed files.
> 
> ```bash
> gunzip <file-name>.gz
> ```

> **25. Redirect output:** Save command output to a file.
> 
> ```bash
> command > output.txt
> ```

> **26. Append output:** Add results to an existing file.
> 
> ```bash
> command >> output.txt
> ```

> **27. Pipe commands:** Chain multiple commands together.
> 
> ```bash
> command1 | command2
> ```

> **28. Find large files:** Sort by size.
> 
> ```bash
> du -ah . | sort -rh | head -n 10
> ```

> **29. Check network connections:** Inspect open ports.
> 
> ```bash
> netstat -tuln
> ```

> **30. Schedule tasks:** Run commands at intervals.
> 
> ```bash
> crontab -e
> ```

## ⚖️ License

This repository is licensed under the terms of the [Apache License 2.0](LICENSE). The license grants permission to use, modify, and distribute the code with proper attribution, while ensuring that improvements and extensions remain open and accessible to the community.

## 

> Built with '\u{2665}' (♥) by Jesús Domínguez [@jdomingu19](https://github.com/jdomingu19/)
