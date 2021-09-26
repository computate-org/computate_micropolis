
# Install the micropolis ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_micropolis

# Clone the micropolis ansible role. 
git clone git@github.com:computate-org/computate_micropolis.git ~/.ansible/roles/computate.computate_micropolis
cd ~/.ansible/roles/computate.computate_micropolis
```

# Run the micropolis ansible playbook to install micropolis locally (requires sudo privileges with -K). 

```bash
ansible-playbook -K install.yml
```

