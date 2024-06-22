# Docker-ECR-ECR-repo-with-Terraform
# task 1

Task:

1. Create a Git folder in $HOME
2. Open it with VSCode
3. Clone the repo into VSCode
4. Create a DockerFile with Ngnix and Html
5. Install hadolint VSCode extention (you'll need to run `brew install hadolint` after installing the extension) and test it
6. Make sure your image is buildable: `docker build .`
7. Make sure you can start a container:

run
docker build .
docker images
docker run -d -p (port 8080)(image ID)

```
localhost:80
```

, the default nginx page should show up

1. Create an ECR repo manually in AWS
2. Create an ECR repo with Terraform in a new Git repo (ex. tf-ecr)
