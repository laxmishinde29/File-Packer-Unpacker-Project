# File Packer and Unpacker Project in java

## 🔧 How It Works

### Packing Flow:
1. User inputs directory name
2. Program scans for `.txt` files
3. Each file is written to a packed file with a 100-byte header
4. Finished packed file can be moved/stored

### Unpacking Flow:
1. User inputs packed file name
2. Each header is read to get file name and size
3. Files are extracted and saved

