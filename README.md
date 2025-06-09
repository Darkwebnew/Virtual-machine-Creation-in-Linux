# EX - 3 VIRTUAL MACHINE CREATION IN LINUX

## 🧪 AIM
To install and configure a Linux virtual machine using CentOS on VirtualBox, providing a secure environment for learning and testing Linux-based applications.

---

## 📝 PROCEDURE

### Step 1: Open VirtualBox or VMware Workstation
- Launch **Oracle VirtualBox** or **VMware Workstation** on your host system.

### Step 2: Create a New Virtual Machine
- Go to **File > New**.
- Select **Linux** as the OS type and **CentOS** as the version.

### Step 3: Configure Virtual Machine Details
- Select the downloaded **CentOS ISO** file.
- Allocate the following resources:
  - **Base Memory**: 1024 MB (1 GB)
  - **Processor Core(s)**: 1
  - **Hard Disk Size**: At least 20 GB
- Complete setup by clicking **Finish**.

### Step 4: Configure Network Settings
- Select the newly created VM → **Settings > Network**.
- Under **Adapter 1**, choose **NAT** for internet access through host.
- Click **OK** to save the configuration.

### Step 5: Start the Virtual Machine and Install CentOS
- Click **Start** to launch the VM.
- Follow CentOS installation steps:
  - Select disk partitioning
  - Set root password
  - Complete installation
- After installation, **log in to CentOS**.

---

## 💻 BASIC LINUX COMMANDS USED

```bash
# Switch to a user
su username

# View IP address
ip a

# Create a directory
mkdir <directory_name>

# Navigate to the directory
cd <directory_name>

# Edit hostname file
vi /etc/hostname

# View hostname file contents
cat /etc/hostname
```

## 📸 OUTPUT

![image](https://github.com/user-attachments/assets/a8fb51ea-f2eb-4caa-8e9e-0440c75ead41)

## ✅ RESULT
The Linux virtual machine (CentOS) was successfully created, configured, and tested using VirtualBox. Basic Linux operations were verified, demonstrating the ability to use Linux in a virtualized environment for learning and development.
