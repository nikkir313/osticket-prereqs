# osticket-prereqs <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h2>Environments and Technologies Used</h2>
- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop**
- **Internet Information Services (IIS)**

## **Operating Systems Used**
- **Windows 10 (21H2)**

## **List of Prerequisites**
Before installing OS-Ticket, ensure you have the following:
1. **A Virtual Machine (VM)** running Windows 10 or Windows Server.
2. **Remote Desktop Access** enabled on your machine.
3. **IIS (Internet Information Services)** installed.
4. **PHP and MySQL** installed for OS-Ticket compatibility.
5. **OS-Ticket Installation Files** downloaded from the official website.

## **Installation Steps**
### **Step 1: Set Up the Virtual Machine**
- Launch **Microsoft Azure** and create a **Windows 10 (21H2) Virtual Machine**.
- Ensure that **Remote Desktop is enabled** for remote access.

![VM Setup]

### **Step 2: Install IIS (Internet Information Services)**
- Open the **Control Panel**, go to **Programs & Features**, and enable **IIS**.
- Install necessary **IIS components** for running OS-Ticket.

![IIS Installation]

### **Step 3: Install PHP and MySQL**
- Download and install **PHP (version 7.4 or later)**.
- Install **MySQL** and create a **new database** for OS-Ticket.

![PHP and MySQL Setup]

### **Step 4: Download and Configure OS-Ticket**(![os instal](https://github.com/user-attachments/assets/79ffcfa7-a10c-4372-85b1-4f58e04fcda1)

- Download the **OS-Ticket installation package** from the [official website](https://osticket.com/download/).
- Extract the files and place them in the IIS web root directory (`C:\inetpub\wwwroot`).

![OS-Ticket Configuration]

### **Step 5: Final Setup and Testing**
- Open a **web browser** and navigate to `http://localhost/osTicket/` to begin the installation.
- Complete the setup by entering the **database details and administrator credentials**.

![Final Installation]

## **Conclusion**
After completing these steps, OS-Ticket should be successfully installed and running on your Windows 10 VM. If you encounter any issues, refer to the [official documentation](https://docs.osticket.com/) or seek help from the OS-Ticket community.

---

### **Code Snippet for Images**
Replace `placeholder-image-link-X.jpg` with the actual image URLs or paths.

---


