# 🔁 Duplicate File Remover (Bash Script)

This Bash script scans a given directory (or current directory by default), detects **duplicate files** using MD5 checksums, 
and deletes all but one copy of each duplicate group.

---

## 📜 Script Overview

**Filename**: `remove_duplicates.sh`

### 🔍 What It Does:
- Scans a directory recursively for all files.
- Generates MD5 checksums for each file.
- Detects duplicates based on identical checksums.
- Keeps one file from each group of duplicates and deletes the rest.
- Outputs actions to the console for transparency.

---

## ⚙️ Usage

```bash
./remove_duplicates.sh [directory]
