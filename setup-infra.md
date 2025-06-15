AWS EKS Cluster Configuration, Setup & App Deployment
This documentation provides detailed instructions for setting up and configuring an Amazon Elastic Kubernetes Service (EKS) cluster in the ap-south-1 region. The steps include installing AWS CLI, setting up the EKS cluster, updating kubeconfig, installing kubectl, installing eksctl, associating IAM OIDC provider, creating a service account with required permissions, deploying the AWS EBS CSI Driver, and applying a custom manifest file.

Step 1: Install AWS CLI
Follow these steps to install the AWS Command Line Interface (CLI):
    1. Download the AWS CLI installer:
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
    2. Install the unzip utility (if not already installed):
sudo apt install unzip
    3. Unzip the installer:
unzip awscliv2.zip
    4. Run the installer:
sudo ./aws/install
    5. Configure AWS CLI:
aws configure
