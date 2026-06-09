# Finding: Suspicious User Account Creation (Event ID 4720)

```SPL Query
index=* event_id=4720 status=Suspicious destination_ip=172.16.1.53 source_ip=156.34.23.112
```
## Description 
A user account creation event (Event ID 4720) was detected on the internal host 172.16.1.53. The activity originated from an external IP address 156.34.23.112, which is not part of the trusted network range. This activity is considered suspicious as it may indicate unauthorized access and a potential attempt to establish persistence on the system.
The thing that we can demonstrate here is that we can search by specifying the IP and status and other specific required attributes in order to get to the final output that we want
