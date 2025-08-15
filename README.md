# Ansible

Fallstudie zu Ansible. Systemautomatisierung im Krankenhaus.
Hierfür wird ein Server als Datenbank betrachtet, während die anderen Server die Maschinen des Krankenhauses
darstellen.

Im Verlauf werden sukzessiv Benutzer und sensitive Daten hinzugefügt und entsprechend mit Berechtigungen ausgestattet.
Danach werden auf den Maschinen durch die Playbooks die notwendigen Pakete installiert. Diese werden mit einem zusätzlichen Playbook auf dem neusten Stand gehalten.

Voraussetzungen:
- Es muss Ansible auf dem Kontrollgerät installiert sein
- Auf den Zielsystemen muss Python3 und SSH installiert sein
- Es müssen zur Ausführung der Playbooks Server mit geeigneter IP Adresse zur Verfügung stehen
- Es muss ein SSH key angelegt werden, mit welchem die SSH Verbindung zu den einzelnen Systemen gesichert wird
