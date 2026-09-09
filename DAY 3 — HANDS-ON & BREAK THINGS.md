3 Nmap Scanning Scenarios

[ทำสำเร็จอะไร]
- Scan specific ports ได้
- เข้าใจ open/closed/filtered
- Save output to file ได้

[Error ที่เจอ]
1. Forgot comma between ports
   → Error: "old nmap format"
   → Fix: Use -p 22,80,443
   
2. Invalid IP address format
   → Error: "not a valid IPv4"
   → Fix: Check octets ≤ 255

3. File path permission
   → Error: "Permission denied"
   → Fix: Use current directory

[ติดขัดตรงไหน]
- ไม่รู้ว่า -sV ต้องใช้หรือไม่
- เมื่อไหร่ใช้ -sV เมื่อไหร่ไม่ใช้

[ทำความเข้าใจใหม่]
- -sV = อยากรู้ version → slow
- ไม่ใส่ -sV = รู้แค่ port open/close → fast