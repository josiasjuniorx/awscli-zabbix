This awscli (v1.8.6) was modified for Zabbix use.


INSTALL

pip install git+https://github.com/josiasjuniorx/awscli-zabbix.git


USAGE

Command line RDS CPUUtilization Example

AWS_ACCESS_KEY_ID=*** AWS_SECRET_ACCESS_KEY=*** aws cloudwatch get-metric-statistics --region sa-east-1 --namespace AWS/RDS --period 60 --last --statistics Average --dimensions Name=DBInstanceIdentifier,Value=*** --metric-name CPUUtilization --output text











See original README on official project hub -> https://github.com/aws/aws-cli/blob/develop/README.rst
