# Házi feladat: Konfigurációs menedzsment 1

Ez a repository egy Ansible példa, mely nginx-et telepít és módosítja a kezdőoldalt.

## Használata

ansible-playbook -i *inventoryfile_hivatkozás* ./nginx_install.yml

Az inventoryfile-ban kell legyen egy host, ami "m-web" néven érhető el, mivel a playbook csak ezen a host-on fut alapból.
