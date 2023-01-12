# Desafio Pipeline CICD Cloud Build + Terraform.

1. Utilize o git https://github.com/digitalinnovationone/terraform-gcp/tree/main/terraform-exemplo2 para configurar a trigger do Cloud Build.
- Criando repositório do Google Cloud Storage
![Creating Repo](/images/create-cloud-source-repo.png?raw=true "Cloud Source Repo")
- Creating Build Trigger
![Build Trigger](/images/cloud-build-trigger.png?raw=true "Build Trigger")
- Trigger Worked!
![Build Working](/images/cloudbuildterraform-working.png?raw=true "Build Working")

2. Edite o script para trocar o nome da máquina para cloudbbuildterraform.
- Git Diff
![Git Diff](/images/git-diff-name.png?raw=true "Git Diff")

3. Salve os arquivos do Estado no Google Cloud Storage.
- Creating Bucket
![Creating Storage](/images/create-bucket-cloud-storage.png?raw=true "Creating Storage")
- State saved on created Bucket
![Saved State](/images/saved-state.png?raw=true "Saved State")

Submeta o print de cada etapa de configuração do Pipeline .
