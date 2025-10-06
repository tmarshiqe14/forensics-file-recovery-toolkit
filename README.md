# Digital Forensics File Recovery Tool

A **C-based digital forensics tool** designed to recover deleted or corrupted files from raw disk images. This project demonstrates file carving techniques, forensic analysis, and data integrity verification — essential skills in cybersecurity and incident response.

---

## Features

- **Recover multiple file types**: JPG, PNG, PDF, ZIP (easily extendable)
- **Automatic file naming**: `000.jpg`, `001.png`, etc.
- **SHA-256 hashing**: Computes hash for each recovered file for integrity verification
- **Logging**: Generates a `recovery_log.txt` with file names and hashes
- **Block-level recovery**: Reads memory card / disk image in 512-byte blocks
- **Modular design**: Easily extendable for additional file types or forensic features

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
