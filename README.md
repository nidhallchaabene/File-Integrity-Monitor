<h1>File Integrity Monitor </h1>



<h2>Description</h2>
The PowerShell File Integrity Monitor (FIM) is a script designed to monitor changes in file integrity within a specified directory. It provides the ability to establish a baseline of file hashes and continuously monitor for new, modified, or deleted files, offering an additional layer of security by detecting potential unauthorized changes.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>

 <h2>Features</h2>
 
- **Baseline Creation:** Easily create a baseline by calculating and storing file hashes in a designated file (`baseline.txt`).<br/>
- **Continuous Monitoring:** Continuously monitors the specified directory for changes, comparing the current state with the established baseline.
- **Real-time Notifications:** Provides real-time console notifications for created, modified, or deleted files.
- **Hash Verification:** Utilizes SHA-512 algorithm for file hashing, ensuring a strong level of integrity verification.
- **User-Friendly Interface:** Simple user interface with options to create a new baseline or begin monitoring files.
  
<h2>Flow Chart</h2>
<img src="https://imgur.com/MUSqOkz.png" height="80%" width="80%" alt="Flowchart"/>

<h2>Baseline</h2>
<img src="https://imgur.com/kolOB2M.png" height="80%" width="80%" alt="baseline"/>



<h2>Screenshots:</h2>

<p align="center">
Checking the existence of the baseline before starting the FIM: <br/>
<img src="https://imgur.com/4ZFia7C.png" height="80%" width="80%" alt="feature"/>
<br />
<br />
Real-time Notification when a new file has been created :  <br/>
<img src="https://imgur.com/R9sEA3u.png" height="80%" width="80%" alt="feature"/>
<br />
<br />
Real-time Notification when a file has been changed : <br/>
<img src="https://imgur.com/EB43JIv.png" height="80%" width="80%" alt="feature"/>
<br />
<br />
Real-time Notification when a file has been deleted:  <br/>
<img src="https://imgur.com/jJ2kRLk.png" height="80%" width="80%" alt="Feature"/>
<br />
<br />

</p>
