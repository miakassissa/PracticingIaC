# PracticingIaC
Terraformiser WordPress sur AWS.

(1) Utilisation

**Provisionnement:**
git clone https://github.com/miakassissa/PracticingIaC.git
cd PracticingIaC
terraform init
terraform plan
terraform apply -auto-approve

**Destruction de l'infra:**
cd PracticingIaC (se trouver dans le dossier du repo)
terraform destroy -auto-approve

**Change:** (latest detail from top)

**Versions:**
Terraform v1.8

provider.aws v4.65.0
