#Finding: Suspicious User Account Creation (Event ID 4720)**

##index=* event_id=4720 status=Suspicious destination_ip=172.16.1.53 source_ip=156.34.23.112

A new user account was created on internal host **172.16.1.53** 
(Event ID 4720). The activity originated from external IP **156.34.23.112**, 
which is not part of the trusted network. 
This behavior is considered suspicious as it may indicate unauthorized access and potential persistence attempt by an attacker.
