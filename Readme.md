# Router Jelszó
Left és Right router jelszó: test


# Ping Tesztek

## Network1 PC0-ról elküldött adatcsomagok:

### Network1 PC0 -> Network2  Server0
---

Pinging 192.168.2.2 with 32 bytes of data:

Reply from 192.168.2.2: bytes=32 time=40ms TTL=126
Reply from 192.168.2.2: bytes=32 time=31ms TTL=126
Reply from 192.168.2.2: bytes=32 time=33ms TTL=126
Reply from 192.168.2.2: bytes=32 time=31ms TTL=126

Ping statistics for 192.168.2.2:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 31ms, Maximum = 40ms, Average = 33ms

### Network1 PC0 -> Network2  PC1
---

Pinging 192.168.2.9 with 32 bytes of data:

Reply from 192.168.2.9: bytes=32 time=26ms TTL=126
Reply from 192.168.2.9: bytes=32 time=29ms TTL=126
Reply from 192.168.2.9: bytes=32 time=39ms TTL=126
Reply from 192.168.2.9: bytes=32 time=42ms TTL=126

Ping statistics for 192.168.2.9:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 26ms, Maximum = 42ms, Average = 34ms

## Network2 PC1-ről elküldött adatcsomagok:
### Network2 PC1 -> Network1  PC0
---

Pinging 192.168.1.9 with 32 bytes of data:

Reply from 192.168.1.9: bytes=32 time=16ms TTL=126
Reply from 192.168.1.9: bytes=32 time=22ms TTL=126
Reply from 192.168.1.9: bytes=32 time=1ms TTL=126
Reply from 192.168.1.9: bytes=32 time=22ms TTL=126

Ping statistics for 192.168.1.9:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 1ms, Maximum = 22ms, Average = 15ms