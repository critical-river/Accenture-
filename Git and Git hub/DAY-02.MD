
## Additional Linux Interview Questions

### 11. What is the difference between a process and a thread in Linux?

- A process is an independent program in execution with its own memory space.
- A thread is a smaller execution unit within a process that shares the same memory/resources.
- Processes are heavier than threads.

### 12. What is the purpose of the `sudo` command?

- `sudo` allows a permitted user to execute commands with superuser (root) privileges.
- It improves security by avoiding direct root login.
- Example:

```bash
sudo apt update
