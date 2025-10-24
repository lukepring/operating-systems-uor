# Operating Systems Module at University of Roehampton
By Luke Pring (A00012218)
## System Planning and Distribution Selection 
<sup>(24/10/2025)</sup>
### System Architecture Diagram
<img src="https://raw.githubusercontent.com/lukepring/operating-systems-uor/refs/heads/main/System%20Diagram.png">

### Distribution Selection Justification
I chose to use the ARM64 version of Ubuntu Server. This is widely adopted in enterprise for good reason, as it offers a balance of stability and usability. This is important as it would be my first time configuring a Linux server. Ubuntu server is *easy to use*, offering strong documentation and simple package management for additional software that may be needed for future tasks of the coursework. This is in comparison to CentOS Stream, another server distribution which requires more manual configuration for installing software packages. Another distribution I considered was Debian, a popular and stable operating system. However, I decided against using Debian as it is less up-to-date, as it has a slower release cycle. In addition, Debian requires more configuration for security, while Ubuntu Server is more automated, speeding up the time it will take to set up my VM.

Ubuntu Server is also clearly the best option due to its simple and guided installation process, which is intuitive and requires less manual setup and knowledge to get started. It is designed to be accessible for new Linux users, with beginner-friendly documentation and simple package management. This is in contrast to CentOS Stream or Debian, which require more configuration knowledge with their more complex setup processes. These distributions are more geared towards experienced server administrators, and require more learning than would be possible during the timescale of the coursework.

### Workstation Configuration
My workstation is a Macbook Pro with the macOS Tahoe (version 26) operating system installed. This is my primary device, and is good for virtualisation due to the Apple Silicon ARM architecture and Apple's virtualisation and hypervisor frameworks. Due to said CPU architecture, the version of Ubuntu Server I have to install will have to be the ARM64 build due to the performance issues virtualising another CPU architecture would introduce. macOS is part of the UNIX family of operating systems, which has many similarities with Linux. This reduces compatibility issues as a lot of the kernel level features are the same, meaning the virtualised server will be more stable and performant. UNIX-based hosts such as macOS also come with Linux tools such as built-in SSH via the Terminal, which means connecting to the server will be easier, not requiring the installation of PuTTY like on Windows hosts.

### Network Configuration
TBC

<sup>Cayman Theme by pages-themes used under licence.</sup>
