#Bootstrap: docker
#From: centos

Bootstrap: shub
From: singularityhub/centos

%labels
AUTHOR abhi18av

%help
The cli-tools for day-to-day life of Data Scientist.


%runscript 
echo "cli-tools on Singularity-hub"

%post
echo "Upgrading the centos7 base image"

#yum -y update

#yum install epel-release

#rpm --import http://li.nux.ro/download/nux/RPM-GPG-KEY-nux.ro

#rpm -Uvh http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-5.el7.nux.noarch.rpm

#3echo "<< Powershell >>"


# Install it directly
yum install https://github.com/PowerShell/PowerShell/releases/download/v6.0.2/powershell-6.0.2-1.rhel.7.x86_64.rpm

# Register the Microsoft RedHat repository
# curl https://packages.microsoft.com/config/rhel/7/prod.repo | sudo tee /etc/yum.repos.d/microsoft.repo

 # Install PowerShell
# sudo yum install -y powershell

 # Start PowerShell
# pwsh
