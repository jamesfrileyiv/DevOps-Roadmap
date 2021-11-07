# DevOps-Roadmap
https://roadmap.sh/devops

To Track Progress of Learning DevOps/SRE/Platform Engineering concepts and tooling.



<h1>Dev</h1>
<h2>1. Learn a Programming Language</h2>
  
  * Python
  * Go
  * C/C++
  * Ruby
  * Node.js

For Python, I have the following two repositories that I work on: 
  * https://github.com/jamesfrileyiv/100-Days-of-Python
  * https://github.com/jamesfrileyiv/Reading-List-Generator

I did quite a bit of C++ coding while attending FSU as it was the language CS courses were taught in. Likewise for Java when I later took some classes at Montgomery County Community College while job searching.

Go is a language I would like to learn better due to it's rising popularity and devops tools like Kubernetes, Docker, and Terraform being written in Go.

<h1>Traditional Operations</h1>
<h2>1. Understand different OS Concepts</h2>
  
  * Process Management
  * Threads and Concurrency
  * Sockets
  * POSIX Basics
  * Networking Concepts
  * Startup Management (init.d)
  * Service Management (systemd)
  * I/O Management
  * Virtualization
  * Memory/Storage
  * File Systems

<h2>2. Learn about managing Servers</h2>
<h3>2.1. Operating Systems</h3>
  <ul>
    <li>Linux</li>
      <ul>
        <li>Ubuntu</li>
        <li>CentOS</li>
        <li>RHEL</li>
        <li>Debian</li>
        <li>Fedora</li>
        <li>SUSE Linux</li>
      </ul>
    <li>Unix</li>
      <ul>
        <li>FreeBSD</li>
        <li>OpenBSD</li>
        <li>NetBSD</li>
      </ul>
    <li>Windows</li>
  </ul>

My current job is mainly focused around Windows server administration. However, our monitoring software runs off Ubuntu VMs, so as I get more involved in administering our monitoring, I am having to do more sysadmin things for these Ubuntu VMs.
Currently gravitating towards Ubuntu and CentOS 7 when I learn Linux or create a proof of concept for myself. 

<h3>2.2. Learn to Live in Terminal</h3>
  
  * Text Manipulation Tools
    * awk
    * sed
    * grep
    * sort
    * uniq
    * cat
    * cut
    * echo
    * fmt
    * tr
    * nl
    * egrep
    * fgrec
    * wc
  * Process Monitoring
    * ps
    * top
    * htop
    * atop
    * lsof
  * Network
    * nmap
    * tcpdump
    * ping
    * mtr
    * traceroute
    * dig
    * airmon
    * airodump
    * dig
    * iptables
    * netstat
  * System Performance
    * nmon
    * iostat
    * sar
    * vmstat
  * Others
    * strace
    * dtrace
    * systemtap
    * uname
    * df
    * history
  * Bash Scripting
  * Vim/Nano/Emacs/Powershell
  * Compiling apps from source
    * gcc
    * make
    * other related stuff

Since I work at a Windows shop, I'm already pretty familiar with powershell and frequently write powershell scripts for work or run one off commands
Using Linux more at work as a VM for testing bash scripts for API testing using curl commands. Typically using nano to make quick edits. 

<h2>3. Networking, Security, and Protocols</h2>
  
  * HTTP
  * HTTPS
  * FTP
  * SSL/TLS
  * SSH
  * Port Forwarding
  * Emails
    * White/Grey Listing
    * SMTP
    * IMAPS
    * POP3S
    * DMARC
    * SPF
    * Domain Keys

Regarding emails, I've troubleshot issues regarding most of these in the context of Microsoft Exchange and Mimecast, but haven't really deep dived into the theory behind them.

<h2>4. What is and how to setup a X</h2>

  * Reverse Proxy
  * Forward Proxy
  * Caching Server
  * Load Balancer
  * Firewall
  * Web Server
    * Nginx
    * Apache
    * Tomcat
    * IIS
    * Caddy
 
<h1>Infrastructure as Code</h1>
<h2>1. CI/CD Tool</h2>

  * Jenkins
  * Gitlab CI
  * GitHub Actions
  * Circle CI
  * Travis CI
  * Bamboo
  * TeamCity
  * Azure DevOps

<h2>2. Containers</h2>

  * Docker
  * LXC

Already using Docker, mainly Docker Compose for testing some applications. Will upload to github and link here later
**Update:** https://github.com/jamesfrileyiv/DockerSandbox

<h2>3. Configuration Management</h2>

  * Ansible
  * Salt
  * Chef
  * Puppet

<h2>4. Container Orchestration</h2>

  * Kubernetes
  * Mesos
  * Docker Swarm
  * Nomad

<h2>5. Infrastructure Provisioning</h2>

  * Terraform
  * CloudFormation
  * Pulumi

<h2>6. Service Mesh</h2>

  * Istio
  * Consul
  * Envoy
  * Linkerd

<h1>Monitoring Software and Infrastructure</h1>
<h2>1. Infrastructure Monitoring</h2>

  * Prometheus
  * Grafana
  * Nagios
  * Zabbix
  * Monit
  * Datadog

For my current job, I do a lot with infrastructure monitoring, but the platform is OpsRamp. As far as I can tell, OpsRamp is based around Prometheus/Cortex. 

<h2>2. Application Monitoring</h2>

  * Jaeger
  * New Relic
  * AppDynamics
  * Instana
  * OpenTracing

<h2>3. Log Management</h2>

  * Elastic Stack
  * Graylog
  * Splunk
  * Papertrail

I have the start to an Elastic Stack already set up in my docker sandbox, using docker compose. I will upload this to github later when I upload my docker sandbox work.
**Update:** https://github.com/jamesfrileyiv/DockerSandbox/tree/master/Docker-Compose/ELK

<h1>Cloud Providers</h1>

  * AWS
  * Azure
  * Google Cloud
  * Digital Ocean
  * Heroku
  * Linode
  * Vultr

When I practice terraform it's in AWS. I've completed an Azure Administrator course on Udemy, but not yet taken the exam yet since I didn't think having a cloud cert before being very comfortable with Linux administration was all that useful. Also do some minor Azure and Azure AD administration for my current job. 

Although these are public clouds, I also have experience with private clouds like VMware and Hyper-V

<h1>Cloud Design Patterns</h1>

  * Availability
  * Data Management
  * Design and Implementation
  * Management and Monitoring

Here is a great resource for learning design patterns: https://docs.microsoft.com/en-us/azure/architecture/patterns/

<h1>Other Stuff that's Good to Know</h1>
<h2>1. Git</h2>

  * If you commit a file or folder that you'd like to remove from the repository, add it to your .gitignore file. Additionally, cd into your local copy of the repo and run the command: "git rm --cached $file" or "git rm -r --cached $folder". Then commit your changes.
