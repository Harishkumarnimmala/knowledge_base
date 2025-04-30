🖥️ VM Setup on Mac M1/M2 Chips

Follow the instructions provided in the PDF guide to complete the setup.

⚙️ Note on Architecture Compatibility

Rosetta is required to run x86 applications on ARM-based CPUs like M1/M2.

🧰 Tools Used

✅ Vagrant

A VM automation tool that simplifies creation, configuration, and management of virtual machines.

✅ VMware Fusion

A hypervisor used to run and manage VMs on macOS.

Needed for compatibility with ARM-based Macs.

🐧 Linux VMs to Set Up

We will configure two virtual machines:

Ubuntu

CentOS

Both will be provisioned and managed using Vagrant and run inside VMware Fusion.

🔑 VMware Access

We need a subscription to Broadcom to access VMware Fusion downloads.

Download it from VMware (https://support.broadcom.com/group/ecx/downloads)

📘 Important Vagrant Commands
<pre> ```
vagrant up
vagrant ssh
sudo -i
ip addr show
exit
exit
vagrant halt
vagrant destroy
 
``` </pre>

