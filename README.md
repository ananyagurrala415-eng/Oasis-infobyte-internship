# Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap and identify open ports and services running on the local machine.

---

## Tool Used
- Nmap

---

## Command Used

```bash
nmap localhost
```

---

## Scan Results

| Port | State | Service |
|------|--------|----------|
| 135/tcp | Open | msrpc |
| 445/tcp | Open | microsoft-ds |
| 1028/tcp | Open | unknown |
| 3306/tcp | Open | mysql |

---

## Explanation of Open Ports

### Port 135 (MSRPC)
Used by Microsoft Windows for Remote Procedure Call services and system communication.

### Port 445 (Microsoft-DS)
Used for SMB file sharing and printer sharing in Windows systems.

### Port 1028 (Unknown)
An unidentified service running on the system. It may be a temporary or dynamic service port.

### Port 3306 (MySQL)
Default port used by MySQL database server for database communication.

---

## Conclusion

The Nmap scan successfully identified open ports and services running on the local machine.
