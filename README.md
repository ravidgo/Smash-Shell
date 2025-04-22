# Smash Shell

## Description
The Smash project is a simple shell implementation for Linux, designed to deepen understanding of processes, process signaling, and basic system calls. This shell supports both built-in commands and external commands. It demonstrates the management of process states, job control, and signal handling within a Linux environment.

## Technologies Used
- **Programming Languages**: C++  
- **Libraries/Frameworks**: POSIX Threads (pthreads), POSIX System Calls  
- **Tools**: Git for version control  

## Features
- **Built-in Commands**: Implements several built-in commands like `showpid`, `pwd`, `cd`, `jobs`, `kill`, `fg`, `bg`, `quit`, and `diff`.  
- **External Commands**: Executes external programs and handles them as background or foreground jobs.  
- **Job Management**: Supports job control, including listing jobs, sending signals, and managing job states (foreground, background, stopped).  
- **Signal Handling**: Responds to Ctrl-C and Ctrl-Z to terminate or suspend processes respectively.  
- **Process Management**: Handles up to 100 simultaneous processes and manages their states effectively.  

## Getting Started

### Prerequisites
- **Compiler**: GCC or any C++ compiler  
- **Operating System**: Linux  

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/[YourGitHubUsername]/smash.git
   cd smash
   ```
2. Compile the program:
   ```bash
   make
   ```

### Usage
**Running the Shell:**
   ```bash
   ./smash
   ```

**Examples of Built-in Commands:**
   ```bash
   smash > showpid
   smash > pwd
   smash > cd /home/user
   smash > jobs
   smash > kill -9 1
   smash > fg 2
   smash > bg 3
   smash > quit
   smash > diff file1 file2
   ```

**Examples of External Commands:**
   ```bash
   smash > /bin/sleep 10 &
   smash > ls -l
   ```

## Contributing
Contributions to the Smash project are welcome! Please feel free to fork the repository, make your changes, and submit a pull request with your improvements.

---

Let me know if you need any more adjustments!
