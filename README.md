# Temporary File Upload to Filebin Using `curl`

This tutorial explains how to upload files temporarily to [Filebin](https://filebin.net) using the `curl` command.

## Steps

1. Ensure you have `curl` installed on your system and access to the terminal.

2. Prepare the file you want to upload. For example, let’s assume the file is located at: /home/rajexploit404/test.txt
   ![image](https://github.com/user-attachments/assets/10f33a94-e444-4503-80a3-3ffbeb1c1a99)

3. Use the following `curl` command to upload your file to Filebin:

<code> curl --data-binary "@/home/rajexploit404/test.txt" -H "filename: test.txt" https://filebin.net/</code>

Like This: <br>
![image](https://github.com/user-attachments/assets/2e576020-034d-4ed0-b186-c5a2b8741e5a)

*Explanation of the command:

->    --data-binary "@/path/to/file": Where you saved the file in the path.<br>
->   -H "filename: desired_name": Specifies the name of the file when uploaded to Filebin.<br>
->    https://filebin.net/: The URL endpoint where the file will be uploaded.<br>

Once the command is executed, you will receive a response containing the URL to access your uploaded file. For example:

https://filebin.net/diwusoxjie5i6u2t

Copy this URL to share or access the file.

![image](https://github.com/user-attachments/assets/837ca964-8cc8-4a14-814f-c35edfd04cbe)

Notes

 -   Files uploaded to Filebin are temporary and will be deleted according to their retention policy.
 -   Avoid uploading senstive or confidential information.



