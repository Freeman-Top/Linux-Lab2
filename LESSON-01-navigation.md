# Lesson 1: Linux Terminal and Filesystem Navigation

## Objective

Learn to inspect the current working directory, list files, navigate between directories, and understand absolute and relative paths.

## Environment

- Host OS: Windows 11
- Linux environment: Ubuntu
- Repository: Linux-Lab2

## Commands Practised

```bash
pwd
ls
ls -l
ls -lah
cd ~
cd ..
cd -
cd /
mkdir -p practice/navigation/logs
find practice -maxdepth 3 -type d
```

## Key Concepts

- `/` is the filesystem root.
- `~` represents my home directory.
- `.` represents the current directory.
- `..` represents the parent directory.
- Absolute paths start at `/`.
- Relative paths are interpreted from the current directory.

## Practical Exercise

Created a practice directory structure containing:

- `practice/navigation/logs`
- `practice/navigation/config`
- `practice/navigation/scripts`

## Results

Record my actual command outputs and any errors here.

## Troubleshooting

Record any issue encountered, the error message, and the solution.

## Reflection

1. What is the difference between `/` and `~`?
2. What is the difference between `cd ..` and `cd -`?
3. Why should an administrator verify their current directory before modifying files?

## Mini-Challenge

Navigate from my home directory into `practice/navigation/logs` without using an absolute path. Then return to the repository root using relative navigation.

Record the commands and results here.

































