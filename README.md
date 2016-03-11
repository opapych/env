# Env for opapy.ch
## Setup AWS
### Configure IAM

See: http://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started.html

1. Create the 'administrators' group and attach the 'AdministratorAccess' policy
2. Create the 'admin' user and add to the 'administrators' group

### Run aws.yml playbook to configure AWS

1. Install required libs via `pip install -U -r requirements.txt`
2. Copy a `.vault_pass` file from Dropbox to project root
3. Let's run `ansible-playbook aws.yml`

## Will you join us?

Opapy is best lol player ever :)
