# leo-events.tk
Ansible Playbook for leo-events.tk website

## Install before you begin
### Install ansbile

<pre><code>
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
</code></pre>

### Install python-pip
<pre><code>
sudo apt-get install python-pip
</code></pre>

### Export locale if ansible is running in AWS
<pre><code>
export LC_ALL=en_US.utf8
</code></pre>

### Install boto using pip

<pre><code>
pip install boto
</code></pre>
