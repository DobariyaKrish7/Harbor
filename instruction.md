# Word Count Task

## Objective
Write a shell script that counts the number of words in a text file and writes the result to an output file.

## Task Details
1. The input file is located at `/app/input.txt`
2. Your script should count the number of words in this file
3. The output should be written to `/app/output.txt` in the following format:
   ```
   <number_of_words>
   ```
   Where `<number_of_words>` is the total count of words in the input file.

## Word Definition
- A word is defined as a sequence of characters separated by whitespace
- Words can contain letters, numbers, and common punctuation
- Empty lines should not be counted as words

## Example
If `input.txt` contains:
```
Hello world! This is a test.
Another line of text.
```

Then `output.txt` should contain:
```
8
```

## Notes
- The script should be placed in `/app/solve.sh`
- The script will be made executable automatically
- The script should exit with status code 0 on success
- The script should handle empty files correctly (output should be `0`)
