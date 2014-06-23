 Ops Test

* Requirements

	1 Virtual Box https://www.virtualbox.org/

	- Virtualbox -> Preferências -> Rede -> "Redes exclusivas de hospedeiros"
		- Add vboxnet0
			- Endereço IPv4: 192.168.56.1
			- Máscara de rede IPv4: 255.255.255.0

	2 Vagrant http://www.vagrantup.com/

	3 Ansible http://www.ansible.com/

* Run

 git clone https://github.com/lborguetti/ops-test

 cd ops-test

 vagrant up 

 vagrant ssh

* Test

 - nginx
 
 http://192.168.56.10

 https://192.168.56.10

 - tomcat
 
 http://192.168.56.10/sample

 https://192.168.56.10/sample
