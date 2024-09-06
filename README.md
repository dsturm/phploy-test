# Test repository for PHPloy testing on issue #5

This repository is used to test the [PHPloy issue #5](https://github.com/dreadnaut/PHPloy/issues/5), which is related to a "Segmentation fault" error when running PHPloy.

## How to reproduce the issue

1. Install / use [Laravel Herd](https://herd.laravel.com/) to install PHP
1. Clone this repository
1. Create a temporary SFTP server to test the PHPloy deployment, i.e. on [sftpcloud.io](https://sftpcloud.io/tools/free-sftp-server)
1. Configurate the PHPloy deployment settings in the `phploy.ini` file
1. Commit the changes to the repository
1. Run any PHPloy command, for example: `phploy --force --dryrun`
1. The "Segmentation fault" error should appear
