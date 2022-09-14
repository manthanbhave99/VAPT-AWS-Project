# VAPT-AWS-Project

Finding Known Vulnerabilities using various scanning tools. We perform Reconnaissance Enumeration and Scanning on user defined Vulnerable domains. We use AWS EC2 instance as a Platform and Lambda Functions to execute the programs. By using Docker image we build an image for each process. We monitors whole process by Cloud-Watch monitoring tool. by finding known vulnerabilities we provide a patch as a workaround to end user.
# Installation of Tools 
Subfinder :- go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@lastest
Httpx :- go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
Nuclei :- go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
