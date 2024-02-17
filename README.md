<H1> Wireshark Project Capturing Packets </H1>

<h2>Scenario</h2>

<br>You are working for a company that wants to detect certain TCP/LP network traffic on their server, specifically website traffic. 
My task is to set up and demonstrate Wireshark’s packet capture capabilities.</br>

<h2>Task 1</h2>
<Br> Objective:

Install and setup wireshark for users belonging to the wireshark group</br>



<br>I added Sudo usermod- aG wireshark $USER. Wireshark was not run as a superuser for security reasons.</br>


<img src="https://github.com/JustinMills2024/WireShark-Capture-Packets/assets/159082478/9fdcf4da-73fa-44fb-a4ac-678b4eb518e7" alt="1708116058341">

<h2>Task 2 </h2>

<br> Objective: Start a packet capture on an ethernet port and save it to a file.


I first clicked on Ens5 the ethernet port file. I then stopped the capturing packets and clicked the red square. 

A capture can only be saved once the capture is stopped. Once that was done I clicked on Save this capture file. </br>

<img src="https://github.com/JustinMills2024/WireShark-Capture-Packets/assets/159082478/d5824908-58bf-4eff-b557-d78dcb3a5cd6" alt="1708116420712">

<br>  Then saved the file as task 2.</br>

<img src="https://github.com/JustinMills2024/WireShark-Capture-Packets/assets/159082478/7337cc4e-1722-4cf9-8a3c-ab6d970b98f5" alt="1708116623396">


<h2>Task 3 </h2>

<br> Objective: Use a display filter to detect HTTPS packets

I first went to Duckduckgo then went to Wireshark. Clicked stop the capturing packets. Then I saved this capture file. I saved it as task 3. 

After that was done I  went to the display filter and typed tcp.port==443. Then clicked apply display filter. This displayed only HTTPS traffic by using a filter on TCP port 443.tcp.port==443 </br>

<img src="https://github.com/JustinMills2024/WireShark-Capture-Packets/assets/159082478/b3a62f9a-5131-41d4-ad42-0ab2a88a67aa" alt="1708119346521">


<br> I then scrolled down to Client Hello </br>




