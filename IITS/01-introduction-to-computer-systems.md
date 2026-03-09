# Definition of Computer System
A computer system is an electronic system that accepts data (input), processes it according to a set of instructions (programs), stores it, and produces meaningful information (output).  
In simple words, a computer system is a combination of hardware and software that work together to perform tasks efficiently and accurately.

# Block Diagram of Computer System
A computer system mainly consists of the following units:
1. Input Unit
2. Central Processing Unit (CPU)
3. Memory Unit
4. Output Unit

## Explanation of Each Unit
1. **Input Unit:** The input unit is used to enter data and instructions into the computer. It converts human-readable data into machine-readable form. Examples: Keyboard, Mouse, Scanner, Microphone

2. **Central Processing Unit (CPU):** The CPU is the brain of the computer. It performs all calculations, logical decisions, and controls the operations of the entire computer system. The CPU consists of:
    - Arithmetic Logic Unit (ALU): Performs arithmetic operations (addition, subtraction, multiplication, division) and logical operations (AND, OR, NOT, comparisons).
    - Control Unit (CU): Directs and coordinates all operations of the computer system. It controls the flow of data between memory, ALU, and input/output devices.
    - Registers: Small, high-speed memory locations inside the CPU used to store temporary data and instructions during processing.

3. **Memory Unit:** The memory unit stores data, instructions, and results. It plays a vital role in processing speed and efficiency. Memory is mainly classified into: 
    - **Primary Memory (Main Memory)**
        - Directly accessible by the CPU 
        - Fast but limited in capacity
        - Types of Primary Memory:
            - **RAM (Random Access Memory):** Volatile memory used to store data temporarily while the computer is running.
            - **ROM (Read Only Memory):** Non-volatile memory that stores permanent instructions such as booting programs.
    - **Secondary Memory (Auxiliary Memory)**
        - Used for long-term data storage
        - Non-volatile and larger in capacity
            - Examples: HDD, SSD, Pen Drive, CD/DVD

4. **Output Unit:** The output unit presents processed information in a human-readable form. Examples: Monitor, Printer, Speakers, Projector.

# Components of Computer System
A computer system has two major components:
1. Hardware
2. Software  

## Hardware Components
Hardware refers to the physical parts of a computer that can be seen and touched.
1. **Central Processing Unit (CPU):** it performs processing and control functions.

2. **Memory:** stores data and instructions required for processing. 

3. **Display Units:** Display units are output devices used to show information visually. Types of Display Units:
    - **CRT (Cathode Ray Tube):** Old type, bulky and consumes more power.
    - **LCD (Liquid Crystal Display):** Thin, lightweight, low power consumption. 
    - **LED (Light Emitting Diode):** Improved version of LCD with better brightness and efficiency

4. **Keyboard:** A keyboard is an input device used to enter text, numbers, and commands. Types of keys:
    - Alphanumeric keys
    - Function keys
    - Control keys
    - Numeric keypad

5. **Mouse:** A mouse is a pointing device used to select, drag, and interact with graphical elements on the screen.

6. **Hard Disk Drive (HDD)**:
    - Secondary storage device
    - Uses magnetic storage
    - Slower compared to SSD
    - Lower cost per GB

7. **Solid State Drive (SSD)**
    - Advanced secondary storage device
    - Uses flash memory
    - Faster data access
    - More durable and energy-efficient

8. **Other Peripheral Devices:** Scanner, Printer, Webcam, Microphone, Joystick, Speakers.

# Software
Software is a set of programs and instructions that tell the computer what to do. Software cannot be touched physically.

## Types of Software 
1. **Application Software**
    -Application software is designed to perform specific user-oriented tasks. Examples: MS Word, MS Excel, Web browsers, Media players, Accounting software. 

2. **System Software**
    - System software controls the operation of the computer hardware and provides a platform for running application software. Examples: Operating Systems, Device Drivers, Language Translators (Compiler, Interpreter)

3. **Utility Software**
    - Utility software is used for system maintenance and performance improvement. Examples: Antivirus software, Disk cleanup tools, Backup utilities, File compression tools

# Overview of Operating System (OS)
An Operating System (OS) is system software that acts as an interface between the user and computer hardware.

- **Functions of Operating System**
    - **Resource management:** if multiple users are accessing, there occurs a need for resource management to allocate one hardware to each user which is done by the OS. This becomes important as we need to manage resources specially in multiple devices where we need to access a particular hardware. 
    - **Process management:** Suppose we are performing multiple programs in one time like MS Office, Media Player, etc. how efficiently you manage them all is done by process management.
    - **Memory management:** this is the function of OS that allocates, tracks and controls main memory among processes efficiently. 
    - **File management:** how efficiently files are allocated in the sysetm drive and RAM for efficiently storage use is done by storage management. 
    - **File management:** to organize, store, retrieve and control access to files on storage devices. 
    - **Device management:** to contol coordinate and allocates hardware devices to processes. 
    - **Security and access control:** if a task gains unrestricted access to memory, it is blocked so that there is no interference between processes. 
    - **User interface management:** provides means for users to interact with system through command-line or graphical interfaces. 

<div style="page-break-after: always"></div>

- **Examples of Operating Systems**: Windows, Linux, macOS, Android, iOS. 

> OS provides convenience and throughput (executing multiple tasks at one time) to the user

## Evolution of Operating System 
1. **1st generation computer (1948-1955):** there was no OS and programs were written in machine language. 
2. **2nd generation computer (1955-1965):** batch processing was introduced and programs were executed in batches. 
3. **3rd generation computer (1965-1980):** multiprogramming and time sharing was introduced and UNIX was developed. 
4. **4th generation computer (1980-present):** windows, linux GUI-basic OS introduced. 

## Types of OS 
1. **Batch OS:** job executed in batches. No user interaction 
2. **Time-sharing OS:** multiple users share CPU time 
3. **Real time OS:** fast response time. E.g.: UNIX. Used in control systems. E.g.: air-control system, robotics, etc. 
4. **Distributed OS:** multiple computers work as one system. 
5. **Network OS:** manages network resources. E.g.: windows servers. 
6. **Multiprogrammed OS:** allows multiple tasks to reside in memory and share CPU concurrently. 
7. **Multitasking OS:** allows multiple tasks to execute simultaneously by switching CPU between them. 

## OS Processing Types
1. **Batch Processing:** jobs are grouped and executed together. There is no interaction during execution. 
2. **Multi-programming:** several programs loaded in memory and CPU switches between programs. 
3. **Multitasking:** one user runs multiple programs at once. 
4. **Time Sharing:** CPU time divided among users. 
5. **Real-time processing:** immediate processing required and no delay allowed. E.g.: missile systems, industrial automation. 

## OS Structures 
1. **Monolithic:** entire OS runs ias a single program. E.g.: MS DOS, Android 
2. **Layered:** OS is divided into layers. E.g.: Windows NT, Linux, Windows 10, etc. 
3. **Microkernel:** services run separately. E.g.: MINIX 
