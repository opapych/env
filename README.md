# Env for opapy.ch
## Setup AWS
### Configure IAM

See: http://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started.html

1. Create 'Administrators' group and attach 'AdministratorAccess' policy
2. Create 'admin' user and add to 'Administrators' group

### Run aws.yml playbook to configure AWS

1. Install required libs via `pip install -U -r requirements.txt`
2. Create `.vault_pass` file and put the vault password
3. Run ansible `ansible-playbook aws.yml`
