# Website-Infra

1. Install the aws-cli
1. Run `aws configure` and input your details
2. Install python3
3. Run `pip install boto3`
4. Download your cookies from porkbun.com using some cookie downloader that uses Netscape format
5. Place that cookies file in this project's directory
6. Run `python setup_aws_resources_and_porkbun_namesevers.py --cookies-file-path <YOUR_COOKIES_FILE_NAME>`