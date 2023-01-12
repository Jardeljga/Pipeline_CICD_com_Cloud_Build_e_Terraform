# Pipeline_CICD_com_Cloud_Build_e_Terraform
Criação de Pipeline CI/CD utilizando CloudBuild e Terraform

Nesse projeto utilizei o CloudBuild em conjunto com o Terraform no GCP para execução de um Pipeline de implantação. Também foram realizadas as seguintes configurações:

Criação de um Bucket para armazenamentos dos arquivos de estado do Terraform (tfstate);
Criação de um Cloud Source Repositories para armazenamento do código em repositório remoto;
Criação de um gatilho (Triggers) para execução automática do pipeline sempre que um novo “push” seja submetido ao repositório remoto.

