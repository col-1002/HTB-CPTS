# HTB-CPTS
Most of the notes, resources and scripts I used to prepare for the HTB CPTS and "pass it the 2 time."

## 29-05-2023
HTB Certified Penetration Testing Specialist (HTB CPTS)  [Badge here!](https://www.credly.com/badges/333ada6a-c23e-422c-a34a-109436cbd41c/public_url)   

Giới thiệu về nó 1 chút:      
	*HTB CPTS is a highly hands-on certification that assesses the candidates’ penetration testing skills. HTB Certified Penetration Testing Specialist certification holders will possess technical competency in the ethical hacking and penetration testing domains at an intermediate level. They will be able to spot security issues and identify avenues of exploitation that may not be immediately apparent from searching for CVEs or known exploit PoCs. They can also think outside the box, chain multiple vulnerabilities to showcase maximum impact, and actionably help organizations remediate vulnerabilities through commercial-grade pentesting reports.*

The Exam:    
	*The candidate will have to perform blackbox web, external and internal penetration testing activities against a real-world Active Directory network hosted in HTB’s infrastructure and accessible via VPN (using Pwnbox or their own local VM). Upon starting the examination process, a letter of engagement will be provided that will clearly state all engagement details, requirements, objectives, and scope. All a candidate needs to perform the required penetration testing activities is a stable internet connection and VPN software. HTB Certified Penetration Testing Specialist is the most up-to-date and applicable certification for Penetration Testers that focuses on both penetration testing and professionally communicating findings.*

Tôi copy full từ trang chủ của [Hack The Box - CPTS](https://academy.hackthebox.com/preview/certifications/htb-certified-penetration-testing-specialist/) . Tóm lại, nó giống kiểu kiểm thử 1 hệ thống từ ngoài vào trong, không có máy đơn, sâu chuỗi tấn công, leo thang đặc quyền, Double Pivoting, Active Directory attack, Domain Trust attack,...  Cuối cùng là viết một báo cáo chi tiết step by step.   

Tôi chọn CPTS vì nó rẻ trong [Roadmap](https://pauljerimy.com/security-certification-roadmap/)

Được rồi nói một chút cảm nhận của tôi về nó nhé. Để cho anh em ai muốn thi thì xem xét!
## Được 
- Hack The Box Academy là một nền tảng dạy học offensive tốt và đặc biệt phần Active Directory. Nên tôi muốn thi để trải nghiệm và học thêm về AD. Phần PATH nó cũng cung cấp kiến thức cơ bản và cần thiết.
- Tài liệu và lab học khá ổn. Nếu anh em nào cũng chơi HTB hay THM, PG sẽ biết là cần kết nối VPN để làm lab. Còn HTB Academy có sử dụng Pwnbox, chỉ cần login vào nền tàng web của nó là làm được luôn.
- Tài liệu học giải thích chi tiết, cuối mỗi module còn có lab để thực hành.
## Hạn chế
- Khoá học cung cấp kiến thức không quá sâu
- Discord của HTB nói chỉ cần học trong lộ trình là đủ pass. Tôi thấy nó khá khó, rabit hole không cần thiết và nhiều thứ trong thi cần gg.
- Viết báo khá dài :(( 
- Không có giám sát, 10 ngày mà
## Xàm
Theo lý thuyết thì học và làm lab hết 43 ngày. Nhưng đó nếu ae có base tốt thì phần web sẽ học rất nhanh, chỉ có phần AD, pivot, PE windows thì hơi lâu. Tôi tốn 2,5 tháng để học xong, nhưng tôi ko thi ngay mà lên youtube xem [bmdyy](https://www.youtube.com/watch?v=dRW1Gxmu__Q&ab_channel=bmdyy) và [CryptoCat](https://www.youtube.com/watch?v=UN5fTQtlKCc&ab_channel=CryptoCat) . Thấy ô `bmdyy` offensive expert mất 5 ngày, ô còn lại thì 2 lần mới pass. Thế là tôi mới nghĩ "thi luôn chắc tạch" nên tôi đã học thêm 3 tuần và đợi đến lúc nghỉ lễ 30/4-1/5 để thi :))

Lần 1 tôi trượt, tôi nghĩ nó giống module cuối. Nhưng không, stuck máy trước sao mà sang máy sau. Thế là tôi nộp báo cáo trắng để được thi lại lần 2.     
Lần 2, tôi đã ôn kỹ lại 3 module trên + bloodhound, crackmapexec. Tôi đã hoàn thành lab exam hết hơn 7 ngày và ngồi viết cái báo cáo trong 11-12h. Nộp báo cáo và có thông báo pass trong 4 ngày sau đó.   

Dù sao cũng là một trải nghiệm thú vị.  

Cảm ơn vì đã đọc tới đây!

## Reference link/resource

[🎙️ HTB Stories #10](https://www.youtube.com/watch?v=wwmCHeYd1I4&ab_channel=HackTheBox)    
[My Guide to HTB’s CPTS Course/Exam - bmdyy](https://www.youtube.com/watch?v=dRW1Gxmu__Q&ab_channel=bmdyy)      
[ HTB CPTS - Review + Tips - YouTube - CryptoCat ](https://www.youtube.com/watch?v=UN5fTQtlKCc&ab_channel=CryptoCat)     
#### Tool 
[Edges — BloodHound 4.3.1 documentation](https://bloodhound.readthedocs.io/en/latest/data-analysis/edges.html)    
[Introduction - CrackMapExec doc )](https://wiki.porchetta.industries/)    
[PowerView doc](https://powersploit.readthedocs.io/en/latest/)    
#### Pivoting
[Attacking Enterprise Networks: Double Pivot using Chisel](https://forum.hackthebox.com/t/attacking-enterprise-networks-double-pivot-using-chisel/267043)      
[runas - Running PowerShell as another user, and launching a script - Stack Overflow](https://stackoverflow.com/questions/28989750/running-powershell-as-another-user-and-launching-a-script) 
#### 3 module 

