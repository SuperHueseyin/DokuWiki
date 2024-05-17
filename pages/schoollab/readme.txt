====== SchoolLab Dokumentation ======
Das SchoolLab ist ein von der Rudolf-Diesel-Fachschule entwickelte Web-Anwendung, die virtuellen remote maschinen für Prüfungs- und Laborumgebungen bereitstellt. Die Anwendung läuft innerhalb eines Docker-Containers, die auf die internen [[schoollab:infrastructure|Infrastruktur]] platziert wurde. \\ Das administrieren der Infrastruktur liegt in der Verantwortung der Rudolf-Diesel-Fachschule in Nürnberg.

===== Überlick Infrastruktur ======
{{:schoollab:schoollab2325_infrastructure_topology.png?400|}}


===== Elementare Hosts =====
''SchoolLab Web-App:'' [[https://webapp.schoollab.duckdns.org/login|SchoolLab Web-App]] 
\\
''Apache Guacamole:'' [[http://10.76.16.101:8082/guacamole/#|Apache Guacamole]]
\\
''Proxmox VE:'' [[https://pve.schoollab.duckdns.org|Proxmox VE]]
\\
''Portainer:'' [[https://10.76.16.101:9443|Portainer]]
