# PROJECT FOR DEMONSTRATION
## YUM - JOB TEMPLATES & WORKFLOW

<br>


### Para executar este job é necessário criar primeiramente:
- Organization
- Project
- Machine Credential
- Ansible Tower Credential
- Inventory

<br> 

### Crie um job template utilizando o playbook: 
- tower_create_job_template.yaml

<br>

### Conforme exemplo abaixo, defina as seguintes extra_vars no job_template:

```
PROJECT: "PROJECT NAME"
CREDENTIAL: "SSH OAUTH"
INVENTORY: "INVENTORY NAME"
ORGANIZATION: "DEFAULT"
```

<br>

### Apos execucao teremos: 
- YUM - Update All Packages
- YUM - Update Bugfix Packages
- YUM - Update Security Packages
- YUM - Install Packages (com survey)
- YUM - Update Workflow



