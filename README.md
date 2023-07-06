# Enable MDC and Configure Log Collection for Virtual Machines

![pt 1](https://github.com/garrick8jackson/Lab-2/assets/38325200/8ed95b89-44ea-4828-af04-086f651ee88f)

Created Windows and Linux virtual machines to run the lab on.

![pt 2](https://github.com/garrick8jackson/Lab-2/assets/38325200/ccc182ee-d2f7-4fbd-9203-dd12af206845)

Created Flow logs for both our windows and linux virtual machines to log information about IP traffic flowing through our network security groups.

![pt 3](https://github.com/garrick8jackson/Lab-2/assets/38325200/4ac8a8fa-1265-4fa0-b45d-0074607c74ae)

Edited diagnostic settings on both virtual machines to define the metric and log data sent to the defined destinations.

![pt 4](https://github.com/garrick8jackson/Lab-2/assets/38325200/3a110d9d-d2a5-42c6-b3ae-89fbe6752f7e)

Created data collection rules for both virtual machines to specify what data should be collected and where it should be sent.

![pt 5](https://github.com/garrick8jackson/Lab-2/assets/38325200/518d81cb-f012-42af-a7e6-99aa1155154a)

Added Queries to check logs for the Windows and Linux virtual machines.

![pt 6](https://github.com/garrick8jackson/Lab-2/assets/38325200/c95fca35-f18d-489b-8186-8644478be779)

Logged into our attacker virtual machine we tried to remote log into our windows virtual machine to add data to our logs to observe.

![pt 7](https://github.com/garrick8jackson/Lab-2/assets/38325200/3e2c192e-665d-454a-b37d-5ca1686611eb)

Using ‘Syslog’ I checked the logs of my Linux virtual machine to make sure the invalid login I did on the attacker virtual machine was logged correctly. 

![pt 8](https://github.com/garrick8jackson/Lab-2/assets/38325200/e05f2544-3cac-4785-bd99-e268c74d9dff)

Using ‘SecurityEvent’ I checked the logs of my Windows virtual machine to see who,where, and when somebody tried to log in using invalid credentials. 







