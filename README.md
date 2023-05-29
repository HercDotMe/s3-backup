# S3 Backup

A simple Bash script to put things into an S3 bucket. This will automatically archive the given directory, upload it to
S3 specified bucket then remove the local ZIP archive to reduce disk space usage.

### Requirements

- Linux environment
- ZIP/UnZIP utilities installed
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html) installed and logged in

### Installation

- Clone this repository in home directory

### Usage

`s3-backup <local_directory> <bucket_name> <bucket_path>`

`dir-backup <local_directory> <bucket_name>`