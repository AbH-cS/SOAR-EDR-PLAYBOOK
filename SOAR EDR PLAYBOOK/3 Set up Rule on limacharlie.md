
<img width="938" alt="Pasted image 20241202145147" src="https://github.com/user-attachments/assets/adabfc2c-c4d6-4d5e-9681-376c6168582d">

I select D&R rule inside automation to create rule.

<img width="942" alt="Pasted image 20241202145242" src="https://github.com/user-attachments/assets/7e130664-0926-45f7-b994-1ab990791a53">

Click on new rule.

<img width="410" alt="Pasted image 20241202145524" src="https://github.com/user-attachments/assets/2f9335a7-c486-47e4-b7b4-a7a266a97b1f">

We run lazagne on our machine.

<img width="960" alt="Pasted image 20241202150020" src="https://github.com/user-attachments/assets/c856e04a-ef86-46b3-9447-f927ba91165d">

We get that lazagne is running on NEW_PROCESS section and when we click event appears which contains path,hash,command_line etc....


<img width="944" alt="Pasted image 20241202150216" src="https://github.com/user-attachments/assets/fe93d2ca-765a-4cc8-a3f4-8a3086885721">

We got the format of a rule depend on NEW_PROCESS.

<img width="674" alt="Pasted image 20241202150452" src="https://github.com/user-attachments/assets/4002c513-f998-4824-89a5-a4536ecb4520">

We paste them in their respective fields


<img width="416" alt="Pasted image 20241202151115" src="https://github.com/user-attachments/assets/05a8411c-211e-4df8-a5ba-f265def8a22a">]

We run lazagne with "all" option.

<img width="926" alt="Pasted image 20241202152452" src="https://github.com/user-attachments/assets/b191c9da-4902-4f6b-8ff9-ded529290581">

We created a rule to detect lazagne execution.(Hack Tool - Lazagne (SOAR-EDR)) 


<img width="519" alt="Pasted image 20241202153017" src="https://github.com/user-attachments/assets/22aa3bdc-fb55-451e-b7cc-668bb82450b4">

Click the test event to test it to check whether our rule applies or not.

<img width="545" alt="Pasted image 20241202153106" src="https://github.com/user-attachments/assets/5156faec-e8cd-4a0b-b1a1-4ff82772446f">

Yes.Our rule worked.

<img width="949" alt="Pasted image 20241202153332" src="https://github.com/user-attachments/assets/8721a918-742a-4edd-9691-0210092e353f">

When we go to detection tool our rule detects and forward that report to detection tab.

