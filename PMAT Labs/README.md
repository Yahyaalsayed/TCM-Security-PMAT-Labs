# Basic Static Analysis : 

## Lab Malware.NotPacked.exe : 

File Hash : 
> 3b4773db51a514ef19515b0323fb46691176be163f2a6a71c643f65d9a211867

VirusTotal results 
 ![](Images/NOT%20PACKED%20FILE/VT.png)
![](Images/NOT%20PACKED%20FILE/VT%202.png)

* 61 security vendors and 1 sandbox flagged this file as malicious
* File type : Win32 EXE 
* File size : 72.07 KB (73802 bytes)
*  ![](Images/NOT%20PACKED%20FILE/History.png)
* ![](Images/NOT%20PACKED%20FILE/VT%20Imports.png)

### Static Analysis : 

File Not Packed 
![](Images/NOT%20PACKED%20FILE/DIE.png)

Compilation time is 2009/08/30 sun 18:41:44 UTC
![](Images/NOT%20PACKED%20FILE/TD%20Stamp.png)

There is Important things after extracting strings 
![](Images/NOT%20PACKED%20FILE/Strings.png)
![](Images/NOT%20PACKED%20FILE/strings%202.png)

Imports Table
![](Images/NOT%20PACKED%20FILE/Imports.png)
 * KERNEL32.DLL

 Sample manipulate files (CreateFile , OpenFile ,WriteFile , ReadFile )
 * ADVAPI32.DLL 

 The AllocateAndInitializeSid function allocates and initializes a security identifier (SID) with up to eight subauthorities.


* WSOCK32.DLL 

 creates a socket that is bound to a specific transport service provider.



---------------------

## Lab Malware.Packed.exe :

 Packed file on DIE
 ![](Images/Packed%20file/DIE.png)

 Sections 
 ![](Images/Packed%20file/packed%20file.png)

 Unpacking UPX Packed file 
 ![](Images/Packed%20file/Unpacking.png)

 DIE after Unpacking 
 ![](Images/Packed%20file/DIE%20After.png)

Sections 
![](Images/Packed%20file/unpacked%20file.png)

Imports 
![](Images/Packed%20file/IMP%20Table.png)

PEStudio
![](Images/Packed%20file/Imports.png)


----------------------


## Lab Malware.Unknown.exe : 


 File hash 
 > 92730427321a1c4ccfc0d0580834daef98121efa9bb8963da332bfd6cf1fda8a

 Online Scanning 
 ![](Images%202/VT.png)
 ![](Images%202/VT%202.png)

 Not Packed
 ![](Images%202/EXEinfo.png)

 Imports
 ![](Images%202/Functions.png)
 ![](Images%202/Imports%201.png)




