## Quick Start
You'll need to get an ssh key into your new Linux environment. Afterwards, run the following:

```bash
# Clone to your home directory
git clone git@github.com:jasonwc/setup.git

# (Required) Set your username in playbook.yaml. While you're at it, check out the roles and vars_files too.
# (Required) Set your username, repo directory, and repos in user_environment.yml (or clone my repos, what do I care!)

# Installs ansible and dependencies
sudo sh bootstrap.sh

# Run the playbook
ansible-playbook -K playbook.yaml
```