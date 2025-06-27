# Linux-Commands

📂 File & Directory Management

    ls — List files and directories

    pwd — Print working directory

    cd — Change directory

    mkdir — Create a new directory

    rmdir — Remove a directory

    touch — Create empty files

    cp — Copy files or directories

    mv — Move or rename files or directories

    rm — Remove files or directories

    file — Determine file type

    find — Search for files in a directory hierarchy

    stat — Display detailed information about a file

    basename — Strip directory and suffix from filenames

    dirname — Extract directory portion of a path

    tar — Archive files

    gzip / gunzip — Compress/decompress files (gzip format)

    bzip2 / bunzip2 — Compress/decompress files (bzip2 format)

    dd — Low-level data copying tool

    cpio — Copy files to/from archives

🔍 Searching and Filtering

    find — Search for files

    grep — Search file content with patterns

    egrep — Extended grep

    fgrep — Fixed string grep

    locate — Quickly find files by name (uses a database)

    xargs — Build and execute commands from standard input

🖥️ Hardware Information

    lscpu — Display CPU architecture info

    lsblk — List block devices

    lsusb — List USB devices

    lsmod — List loaded kernel modules

    lspci — List PCI devices

    dmidecode — Show hardware info from the BIOS

    free — Display memory usage

    uptime — Show how long the system has been running

📑 Filesystem & Disk Management

    df — Report disk space usage

    du — Estimate file space usage

    mount — Mount a filesystem

    umount — Unmount a filesystem

    blkid — Display block device attributes

    parted — Manage disk partitions interactively

    fdisk — Manage MBR partitions

    mkfs — Create a filesystem

    mkswap — Set up a swap partition

    swapon / swapoff — Enable or disable swap

📡 Networking & Troubleshooting

    ping — Test network connectivity

    traceroute / tracepath — Trace network path to a host

    ifconfig — Configure network interfaces (legacy)

    ip — Modern network configuration tool

    netstat — Network statistics (legacy)

    ss — Socket statistics (replacement for netstat)

    route — Show/manipulate IP routing table

    hostnamectl — Manage hostname settings

    nmcli — NetworkManager CLI

    nmtui — NetworkManager text UI

    dig — DNS queries

    nslookup — Query DNS servers

    tcpdump — Capture network packets

    wireshark — Network protocol analyzer (GUI)

⚙️ Process & System Management

    ps — Show process status

    top — Real-time process monitoring

    htop — Interactive process viewer

    kill — Terminate processes by PID

    killall — Terminate processes by name

    nice / renice — Set process priority

    uptime — Show system uptime

    who — Show who is logged in

    w — Show who is logged in and what they're doing

📑 User & Group Management

    id — Show user/group IDs

    whoami — Show current user

    adduser / useradd — Add a new user

    passwd — Set or change user password

    deluser / userdel — Delete a user

    groupadd — Add a new group

    groups — Show groups a user belongs to

🖨️ Printing

    lp — Submit print jobs

    lpr — Legacy print command

    lpq — Show print queue

    lprm — Remove jobs from print queue

    cancel — Cancel print jobs

    lpstat — Show printer status

    lpadmin — Manage printers

    cupsdisable — Disable printer

    cupsreject — Reject new print jobs

    lpmove — Move print jobs between queues

🖥️ System Boot & Kernel

    uname — Show system information

    dmesg — Show kernel messages

    systemctl — Control systemd services

    journalctl — Query systemd logs

    grub-install — Install GRUB bootloader

    update-grub — Update GRUB configuration

📜 Shell Scripting and Utilities

    echo — Display text

    read — Read user input

    test / [ ] — Evaluate conditional expressions

    for / while / if — Shell control structures

    expr — Evaluate expressions

    source / . — Read and execute a file in current shell

    seq — Generate numeric sequences

    exec — Replace the current process

    alias / unalias — Set or unset command aliases

    printf — Formatted output
