# Linux Command Line Code

## Directory Structure

The Linux file system follows a tree-like hierarchical structure, resembling an upside-down tree:

```
                       \
                _______|______
               |              |
              cat             dog
            ___|___       _______|_______
           |       |     |       |       |
         lion    tiger dingoes hyenas  wolves
```

## Common Linux Commands

### 1. List the Contents of a Directory

To list the contents of a directory, use:

```bash
ls
```

**Note**: Linux is case-sensitive, so ensure you use the correct case when typing commands.

### 2. Display File Contents

To view the content of a file in a paginated format, use:

```bash
more filename
```

### 3. Create a Directory

To create a new directory, use:

```bash
mkdir directory_name
```

### 4. Move or Rename a File

The `mv` command is used for two purposes:

- **Move a file to another directory**:

  ```bash
  mv filename /path/to/destination
  ```

- **Rename a file**:

  ```bash
  mv old_filename new_filename
  ```

### 5. Change the Directory

To navigate to a different directory, use:

```bash
cd directory_name
```

### 6. Get the Current Directory

To display the current directory path, use:

```bash
pwd
```
>>>>>>> master
