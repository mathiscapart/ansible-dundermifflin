echo 'mathi ALL=(ALL) NOPASSWD:ALL' | sudo tee /etc/sudoers.d/mathi

 ansible-playbook -i inventory.yml tasks/wordpress.yml 