# VMware

Vmware is a hypervisor, also known as a virtual machine monitor (VMM) which is a virtualization and cloud computing software provider that offers a range of products for creating, managing, and optimizing virtualized IT environments. 

## Advantages of using a Hypervisor:

  - Resource Optimization: Hypervisors allow multiple virtual machines to run on a single physical device.
  - Isolation: Each VM operates in its isolated environment improves security and stability, as issues in one VM do not directly impact others.
  - Consolidation and Efficiency: By consolidating multiple servers into virtual machines on a single physical server.
  - Dynamic Resource Allocation: Hypervisors allow for dynamic allocation of resources, enabling to scale up or down based on workload demands without affecting other VMs on the same host.
  - Cost Savings: Using a hypervisor enables organizations to reduce the number of physical servers needed, resulting in cost savings on hardware, power, cooling, and physical space.
  - Operating System Independence: Hypervisors abstract the underlying hardware, allowing different operating systems to run on the same physical machine simultaneously.
  - VM Migration: VM images can be easily migrated between different machines.
  - Snapshot and Cloning: Snapshots allow for the capture of the VM's state at a specific point in time.
  - Isolated Testing Environments: Developers can use hypervisors to create isolated testing environments without affecting the actual machine.

## How To install VMware on your PC, 

You can follow these general steps. Please note that the specific instructions might vary slightly based on the version of VMware and your operating system.

  - Download VMware: Visit the official VMware website to download the latest version of VMware Workstation or VMware Player.

  ![Screenshot (2)](https://github.com/Agnesh-K/VMware/assets/154126091/766e795d-cace-4f64-99aa-e0adcda15430)
  ![Screenshot (4)](https://github.com/Agnesh-K/VMware/assets/154126091/a017e730-8daf-4c60-abbb-272e37df4ebb)
  ![Screenshot (5)](https://github.com/Agnesh-K/VMware/assets/154126091/adaa0c52-395d-4d71-a955-b5a8a64e1a96)
  ![Screenshot (6)](https://github.com/Agnesh-K/VMware/assets/154126091/e9c7ffc9-5e85-4da3-b238-710478295cbf)
  ![Screenshot (7)](https://github.com/Agnesh-K/VMware/assets/154126091/36aa5f50-1336-441e-8d5d-6f0d13d8b38d)
  ![Screenshot (8)](https://github.com/Agnesh-K/VMware/assets/154126091/b7b7c6ed-88ba-4998-8302-f3874af9d420)

  - Installation Steps:
    - Double-click on the downloaded VMware Workstation installer (e.g., VMware-workstation-full-<version>.exe).
    - If prompted by User Account Control, click "Yes" to allow the installation to proceed.
    - Click "Next" to proceed.
    - Accept the license agreement. 
    - Select "Typical" for a standard installation and click "Next."
    - Review the installation settings and click "Install."
    - Wait for the installation to complete.
    - Click "Finish" to complete the installation.
  
    ![Screenshot (9)](https://github.com/Agnesh-K/VMware/assets/154126091/f90a9a1c-2379-424b-a3d5-0c99460d89fc)
    ![Screenshot (10)](https://github.com/Agnesh-K/VMware/assets/154126091/c9984971-6852-4b3f-99ea-124d2154337c)

    - Now, you should have VMware installed on your PC, and you can start creating and managing virtual machines.

## How to setup a virtual machine inside VMware
  - Launch on your computer.
  - Create a New Virtual Machine:
    - Click on "File" in the menu.
    - Select "New Virtual Machine."
      ![Screenshot (11)](https://github.com/Agnesh-K/VMware/assets/154126091/1baf0136-accd-4da7-9058-62d60617deb8)
    - Select the operating system you want to install from list of ISO images available in your device.
      ![Screenshot (13)](https://github.com/Agnesh-K/VMware/assets/154126091/ed805243-5895-4f03-9c6a-e619181a368d)
    - Give a name, username and password to your os.
      ![Screenshot (14)](https://github.com/Agnesh-K/VMware/assets/154126091/181eff9c-844a-460e-9cbb-fa3e615c7615)
    - Enter a name for your virtual machine and choose a location to store the VM files.
      ![Screenshot (15)](https://github.com/Agnesh-K/VMware/assets/154126091/b435bfe1-70b4-4215-8fa5-cca8bb23ba65)
    - Enter disk capacity for your V.M.
      ![Screenshot (16)](https://github.com/Agnesh-K/VMware/assets/154126091/5957596c-6fe4-4755-8043-e82d17f69e11)
    - Click "Customize Hardware" to make additional changes.
      ![Screenshot (17)](https://github.com/Agnesh-K/VMware/assets/154126091/f89e6044-8194-4df8-9ea3-62523a7c4d94)
      - Specify the number of processors for the VM.
        ![Screenshot (19)](https://github.com/Agnesh-K/VMware/assets/154126091/68633391-acb7-4d8a-9f7d-65195a745efa)
      - Set the amount of RAM for the VM.
        ![Screenshot (18)](https://github.com/Agnesh-K/VMware/assets/154126091/1ee84389-4346-4eb2-be16-2b5cdd713933)
      - Choose the network type for the VM.
        ![Screenshot (20)](https://github.com/Agnesh-K/VMware/assets/154126091/cb0fccb7-00c0-4a4c-861a-b87942e2674c)
    - Review your settings and click "Finish".
    - Allow the OS installation process to complete. The VM may restart during this process.
    - Once the OS installation is complete, you can customize VM settings further, install additional software, and start using the virtual machine.
