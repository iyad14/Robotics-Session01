# Bash Script Assignment: Count File Types

## Objective

Create a bash script that counts and displays the number of different file types (directories, regular files, symbolic links) in a specified directory.

## Instructions

1. **Script Name:** `count_file_types.sh`
2. **Input:** The script should accept a directory path as an argument.
3. **Output:** The script should display the count of directories, regular files, and symbolic links in the specified directory.

### Example Usage

```bash
./count_file_types.sh /path/to/directory
```

### Example Output

```bash
Directories: 10
Regular files: 50
Symbolic links: 2
```

## Requirements

1. The script should handle invalid or missing directory paths gracefully.
2. The script should be well-commented to explain the logic.
3. The script should use appropriate bash commands and demonstrate an understanding of different approaches.

## Tips

- Use `find`, `ls`, or other relevant commands to identify file types.
- Consider using loops, conditional statements, and built-in shell variables.
- Ensure the script is executable and handles edge cases.

## Submission

1. Write and test your bash script.
2. Save the script as `count_file_types.sh`.
3. Include comments explaining your logic and approach.
4. Commit the script to your repository.
5. Push your branch and create a pull request for review.

## Assessment Criteria

You will be assessed on:
- Correctness: Does the script correctly count and display the file types?
- Error Handling: Does the script handle invalid or missing input appropriately?
- Code Quality: Is the script well-structured and commented?
- Efficiency: Is the approach efficient and suitable for the task?