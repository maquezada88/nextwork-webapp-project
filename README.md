GHub Repo for NextWork AWS DevOp Projects that consisted of the following:

⚙️ Set up a GitHub repository: You created a new repository in AWS GitHub to securely store and manage the source code for your Java web app.
☁️ Configure Git and a local repository: You established your Git identity with your username and email. You also initialized a local repo with your GitHub repo as the remote origin.
🫸 Make Your first commit and push: You added all your files to the staging area, committed them, and pushed these changes to the master branch of your GitHub repository, making your code available in the cloud.

🗂️ Set up and configure AWS CodeArtifact as a private Maven repository for managing dependencies.
🛡️ Use IAM roles and policies to let your EC2 instance access CodeArtifact.
✅ Verify your web app's connection to CodeArtifact and ensure Maven can download dependencies from it.
💎 Create and add your own packages to your CodeArtifact repository!

⚙️ Set up a CodeBuild project and connect it to a GitHub repository.
📝 Define a build process using buildspec.yml.
📦 Store build artifacts in Amazon S3.
🔑 Update CodeBuild's IAM roles to allow permissions to CodeArtifact.
🛠️ Troubleshoot common build errors and ensure successful builds.
💎 Set up CodeBuild to go beyond the build process - and automate testing too!

👏 Launch a deployment architecture using CloudFormation.
✍️ Prepare deployment scripts and an appspec.yml file for CodeDeploy.
⚙️ Configure a CodeDeploy application and deployment group.
🚀 Deploy your web application using CodeDeploy (woah!).
💎 Implement disaster recovery and roll back a deployment!
