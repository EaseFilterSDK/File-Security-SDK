# FileSecuritySDK
[File security filter driver SDK](https://www.easefilter.com/Forums_Files/Comprehensive-file-security-sdk.htm)
 
EaseFilter Comprehensive File Security SDK is a set of file system filter driver software development kit which includes file monitor filter driver, file access control filter driver, transparent file encryption filter driver, process filter driver and registry filter driver. In a single solution, EaseFilter Comprehensive File Security SDK encompasses file security, digital rights management, encryption, file monitoring, file auditing, file tracking, data loss prevention, process monitoring and protection, and system configuration protection. 

![File protector](https://www.easefilter.com/Images/ControlFilter.png)

EaseFilter file system filter driver is a kernel-mode component that runs as part of the Windows executive above the file system. The EaseFilter file system filter driver can intercept requests targeted at a file system or another file system filter driver. By intercepting the request before it reaches its intended target, the filter driver can extend or replace functionality provided by the original target of the request. The EaseFilter file system filter driver can log, observe, modify, or even prevent the I/O operations for one or more file systems or file system volumes.
 
1. File System Monitor Filter Driver. 

File System Monitor Filter Driver can proactively track, audit, report, alert on and respond to, all access to files and folders on Windows systems in real time. With the real-time notifications of the file access, it can help you to detect and stop advanced persistent security threats to your sensitive files. File System Monitor Filter Driver SDK can monitor the file system I/O activities on the fly. With file system monitor filter you can monitor the file activities on file system level, capture file open, create, overwrite, read, write, query file information, set file information, query security information, set security information, file rename, file delete, directory browsing and file close I/O requests. Create your own Continuous Data Protection (CDP) software to log the file update information, write information with offset and length in real time. Audit your file content, you can intercept any file system call, analyze the content and log it. Create Access Logs, you will know who, when, what files were accessed. Journal the file update information. This control may be based on any file parameters, such as its location, type, size, etc.
 
2. File System Control Filter Driver.

EaseFilter File System Control Filter Driver provides you with an easy way to develop the Windows application which can implement software for file protection, file access control and security control. Your application can allow or deny the request, modify the request with your own data, or post-process the request. Your application can fully control file open/create/overwrite, read/write, query/set file attribute/size/time security information, rename/delete, directory browsing these I/O requests.

3. Transparent File Encryption Filter Driver.

Transparent Encryption File System Filter Driver allows you to develop transparent on-access, per-file encryption Windows application without the driver encryption knowledge. EaseFilter encryption library can help you to handle most of the complexity in encryption operations.EaseFilter Encryption SDK was implemented with Isolation Mini Filter Driver. The well-designed EaseFilter Isolation Minifilter could allow both views, the decrypted view of the file’s contents and the encrypted view of the file’s contents, to different applications reading the file simultaneously. It can automatically decrypt data from an encrypted document when accessed by authorized application likes Microsoft Word.  However, when that same encrypted document is accessed from an unauthorized application, for example a backup application, the Isolation Minifilter could provide the raw, encrypted contents of the file.

4. Process Filter Driver

Process Filter Driver is a kernel-mode driver that filters process/thread creation and termination, it provides you an easy way to develop Windows application for the Windows process monitoring and protection. With the EaseFilter Process Filter Driver, it enables your application to prevent the untrusted executable binaries ( malwares) from being launched, protect your data being damaged by the untrusted processes. It also enables your application to get the callback notification for the process/thread creation or termination, from the new process information you can get the parent process Id and thread Id of the new created process, you also can get the exact file name that is used to open the executable file and the command line that is used to execute the process if it is available.

5. Registry Filter Driver

Registry Filter Driver is a kernel-mode driver that filters registry calls, it provides you an easy way to develop Windows application for registry monitoring and protection, track the registry change and prevent the registry from being changed by unauthorized processes or users. With the EaseFilter Registry Filter Driver, it enables your application to protect Windows core registry keys and values and to prevent potentially damaging system configuration changes, besides operating system files. By registering a RegistryCallback routine in the registry filter driver, it can receive notifications of each registry operation before the configuration manager processes the operation.

[Read more about EaseFilter Comprehensive File Security SDK Solution](https://www.easefilter.com/Forums_Files/Comprehensive-file-security-sdk.htm)
