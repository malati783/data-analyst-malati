The screenshots show the process of uploading a file to an Amazon S3 bucket using both the AWS Management Console and PowerShell. In the AWS Console, a general-purpose S3 bucket named academics-raw-mal has been created in the US East (N. Virginia) region to store academic-related data. In the PowerShell window, the write-S3Object command is used to upload a local CSV file (Application-list.csv) into this bucket. The file is organized under a specific folder path or “key” in S3: ethics/application-list/year=2025/quarter=01/server=AGVS-Mal/, which simulates a structured directory for better data management. This setup demonstrates how users can combine AWS’s web interface and command-line tools to efficiently store and manage files in the cloud using structured key naming within an S3 bucket. <imgsrc="Picture1.Png"
