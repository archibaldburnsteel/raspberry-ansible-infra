# raspberry-ansible-infra
## Goals
### Automate Everything
	From flashing SD cards to installing Folding@home clients, the cluster setup is powered by reproducible, modular Ansible playbooks.
### Keep It Consistent
	Every Pi follows the same initial blueprint—hostnames, SSH config, timezone—so scaling up feels like pressing "clone," not starting over.
### Run Folding@home Reliably
	Deploy and monitor work units with maximum uptime, optimizing each Pi's computational contribution based on its hardware capabilities.
### Stay Reproducible & Documented
	Every playbook, config file, and setup nuance lives in this repo and companion OneNote. It's your future-proof strategy manual.
### Enable Maintenance Without Drama
	Node down? No problem. Playbooks support fast reprovisioning and swap-outs. Alerting and logging help detect issues before they become headaches.
### Grow & Evolve
	Designed to scale, this system welcomes additional Pis or even other Linux nodes. Want to build in rolling updates, hybrid clusters, or containerization later? You’re 	covered.
 
## Technologies
Component	Role
Raspberry Pi	Physical nodes running Folding@home client
Ansible	Orchestrates setup, provisioning, and maintenance
Folding@home	Biomedical research via distributed computing
OneNote + Git	Documentation and version control
SSH	Secure remote access and command execution
Monitoring Tools	Optional: glances, node-exporter, or custom scripts
Bonus Perks
	• Gives retired Pis a second life with purpose
	• Ideal for home labs, STEM outreach, or "cool sysadmin flex" moments
	• Contributes directly to Alzheimer’s, cancer, and COVID-19 research
