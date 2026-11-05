<div align="center">
  
# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
</p>
<p align="center"> <a href="https://lnkd.in/p/d65XMnmS"> Click here for LinkedIn Post</a></p>

<h3>Downloading Virtual Box And Kali Linux ISO file </h3>
<p>To get started,VIrtual box must be downloaded from its official website and installed on your machine. As it installs you can attempt to download the official Kali Linux iso file. Now there is an option to either download the file and set it up yourself which can take hours or you can download a version that has already been set up. All you have to do is to extract the file -because it will be compressed- and import it with Virtual box (username and password is "kali").
If not then after downloading it you can install the raw iso file and customize it however you prefer.  </p>

![](Screenshot(241).png)


<h3>Runnining The VM. But Something Was Off</h3>
<p>After runnimg the VM everything seemed to be okay but the issue is I wasn't getting internet connection. So I navigated to "Tools" under the "File menu and clicked on Network.</p>

![](Screenshot(247).png)
![](Screenshot(237).png)

<p>After that I clicked on the "NatNetwork" tab at the top and clicked on create and then I typed the IP "10.0.0.0/24" and Saved it by clicking apply. Actually in my case I just changed the figures there but its still the same thing </p>

![](Screenshot(238).png)

<p align="center"><b>Before</b> </p>

![](Screenshot(239).png)

<p align="center"><b> After </b> </p>


<h3>What Did I Do Next?</h3>
<p>After I saved the configurations I just made, I went back to my list of Vms and selected Kali and then clicked on Its Settings. Then I clicked on the "Network" lab at the left and changed "Attached to" and "Name" to "NATNetwork" and "NatNetwork" respectively. I wouldnt have been able to do so If I didnt do the step before After that I clicked "OK"</p>

![](Screenshot(235).png)

<p align="center"><b> Before </b> </p>

![](Screenshot(240).png)
![](Screenshot(242).png)
<p align="center"><b> After </b> </p>



<h3>Almost Done!!!</h3>
<p>After doing this I navigated to my network settings on my Kali VM and made the changes you see below. Because the adapter has been changed we need to change the IP and DNS so that I can point to the IP we typed earlier so it can access the Internet. After changes had been made I saved it by clicking the "save button"
NB: With this aspect is it adviseable to leave a snapshot in case something goes wrong </p>

![](Screenshot(245).png)
 
<p align="center"><b> Before </b> </p>

![](Screenshot(246).png)

<p align="center"><b> After </b> </p>


<h3>Addig The Final Touch</h3>
<p> Now that the settings have been saved you think that would mean you can access the internet, But that's not the case. This is because the system hasn't updated itself so you'll have to do so manually. In order to do so you'll have to type the codes in the pictures below.This will force the adapter to restart itself so the configurations done earlier will take effect.</p>

![](Screenshot(247).png)

![](Screenshot(249).png)

![](Screenshot(248).png)



<h2>This Marks The End Of The Labwork. Thank You For Reading 😊 </h2>
