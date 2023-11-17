<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation-Configuaration</h1>
This tutorial outlines the post installation configuaration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Complete osTicket Installaion

<h2>Installation Steps</h2>

<p>
<p>
   <a href="https://drive.google.com/uc?export=view&id=10sKCWFcaDfuoCBnoR4xbKqbYEcHObqLT">
    <img src="https://drive.google.com/uc?export=view&id=10sKCWFcaDfuoCBnoR4xbKqbYEcHObqLT"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>

<p>
Here we login with the help desk login and see the Admin panel, we can go back and forth as admin and agent to see tickets, however we need to do some configurations. Again as a help desk tech you won't have to complete this, but as a good way to see learn installation it would bee to see how to set up and learn steps. 
</p>
<br />

<p>
<p>
   <a href="https://drive.google.com/uc?export=view&id=1fzLkiNbAUhjfqbkvZ4W3aQxNOf6PMHaj">
    <img src="https://drive.google.com/uc?export=view&id=1fzLkiNbAUhjfqbkvZ4W3aQxNOf6PMHaj"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>

</p>
<p>
We need to create a new role here, we go to Agents ->Add New Role ->Supreme Administration->Permissions->Full->Save. This role has full access to osTicket. 
</p>
<br />

<p>
   <a href="https://drive.google.com/uc?export=view&id=18-lThzCaai2tFIJtNY64aUs4NsS34zKj">
    <img src="https://drive.google.com/uc?export=view&id=18-lThzCaai2tFIJtNY64aUs4NsS34zKj"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
 We need to create a new role here, we go to Agents ->Add New Role ->System Administration->Permissions->Full->Save. This role has full access to osTicket, you can also assign agents to this department as well. 
</p>
<br/>

<p>
   <a href="https://drive.google.com/uc?export=view&id=1xaRjlmo0jmkHkjZ5zmNDlsd5OR2IXBQS">
    <img src="https://drive.google.com/uc?export=view&id=1xaRjlmo0jmkHkjZ5zmNDlsd5OR2IXBQS"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
We need to create a team here, we go to Agents->Teams->Add New Team->Level II Support->Permissions->Full->Save. This role has full access to osTicket.
</p>
<p>
   <a href="https://drive.google.com/uc?export=view&id=1FLLRnGj-a0cou6cO84zB9_T-9otOXCOz">
    <img src="https://drive.google.com/uc?export=view&id=1FLLRnGj-a0cou6cO84zB9_T-9otOXCOz"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
Next, we need to create some users. Switch to agent view. Click User->Add New User->Enter Name & Email->Create. I created just 2 for the sake of learning. 
</p>
<p>
   <a href="https://drive.google.com/uc?export=view&id=1Aw4ie-Qofy2VBZUiDzZRraNdsw0-c7Cd">
    <img src="https://drive.google.com/uc?export=view&id=1Aw4ie-Qofy2VBZUiDzZRraNdsw0-c7Cd"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
Switch back to admin view, we need to create SLA's. This is the Service Level Agreement Plans: I set up 3, SEV-A, 1 HR grace period, -B, 4 HR grace period, & -C, 8 HR grace period.
</p>
<p>
   <a href="https://drive.google.com/uc?export=view&id=1VzDt2z4Z1Ar0dPWDwGC4KjP6OQ3PMD5c">
    <img src="https://drive.google.com/uc?export=view&id=1VzDt2z4Z1Ar0dPWDwGC4KjP6OQ3PMD5c"
    style="width: 900px; max-width: 100%; height: auto"
    title="Click for the larger version." /></a>
</p>
<p>
The last part of this is creating Help Topics. I created an aditional four under the Manage tab. I created Business Critical Outage, Equiptment Request, Personal Computer Issue, & Password Reset. 
<br />

