
![[Pasted image 20241202145147.png]]
I select D&R rule inside automation to create rule.

![[Pasted image 20241202145242.png]]
Click on new rule.

![[Pasted image 20241202145524.png]]
We run lazagne on our machine.

![[Pasted image 20241202150020.png]]
We get that lazagne is running on NEW_PROCESS section and when we click event appears which contains path,hash,command_line etc....

![[Pasted image 20241202150216.png]]
We got the format of a rule depend on NEW_PROCESS.

![[Pasted image 20241202150452.png]]
We paste them in their respective fields

![[Pasted image 20241202151115.png]]
We run lazagne with "all" option.

![[Pasted image 20241202152452.png]]
We created a rule to detect lazagne execution.(Hack Tool - Lazagne (SOAR-EDR)) 

![[Pasted image 20241202153017.png]]
Click the test event to test it to check whether our rule applies or not.

![[Pasted image 20241202153106.png]]
Yes.Our rule worked.

![[Pasted image 20241202153332.png]]
When we go to detection tool our rule detects and forward that report to detection tab.

