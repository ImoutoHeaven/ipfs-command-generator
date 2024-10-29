
# IPFS Command Generator

The **IPFS Command Generator** is a utility to streamline the generation of IPFS commands for different modes of data handling, such as CID extraction, remote pinning, and URL generation. The tool supports six modes, each tailored to specific IPFS command needs.

## Features

- **IPFS Command Extractor**: Extracts and organizes CIDs for multiple files and folders.
- **CID v1 Extractor**: Generates CIDs in v1 format.
- **Remote Pin Retry**: Helps retry remote pin commands for CIDs.
- **IPFS Add Command Generator**: Generates `ipfs add` commands based on folder structure.
- **IPFS Added URL Generator**: Converts file and folder CIDs into URL format.
- **File Table Generator**: Creates a formatted file table for IPFS folders.

## Modes

### 1. IPFS Command Extractor
- **Input**: Text with lines containing "added <CID> <path>"
- **Output**: Organized commands for file and folder handling in IPFS.

### 2. CID v1 Extractor
- **Input**: CID text
- **Output**: CID v1 formatted extraction.

### 3. Remote Pin Retry
- **Input**: Service nickname and CID list.
- **Output**: Retry commands for pinning on remote IPFS service.

### 4. IPFS Add Command Generator
- **Input**: Folder and file list from `ipfs files ls`
- **Output**: Structured `ipfs add` commands.

### 5. IPFS Added URL Generator
- **Input**: IPFS URLs
- **Output**: URL commands for files and folders.

### 6. File Table Generator
- **Input**: Text including "added <CID> <path>"
- **Output**: Table with file and folder CIDs.

## Example Usage

Each mode provides input fields for specific formats and generates corresponding IPFS commands.

### License
This project is licensed under the GPL-3.0 license.
