# ansible-conf
Ensemble de playbooks ansible pour la configuration de ma machine linux

# Utilisation
## Debian
sudo apt install ansible
sudo systemctl enable --now sshd

## Fedora
sudo dnf install ansible
sudo systemctl enable --now sshd

## Tous
ansible-playbook -i inventory -K playbook-<fichier>.yml

# Source
## Playbook Gnome
https://gist.github.com/carlwgeorge/c560a532b6929f49d9c0df52f75a68ae