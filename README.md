"Still need to document it, but briefly, commits on master in the main repository will build and push a Docker image tagged with that commit's SHA to ECR. Then to deploy, bump the SHA in the deployment repository's docker-compose.yml (in this repo), and commit (to either development or master), which will trigger a rolling update on all instances." (Slack)

Trying to update permissions in ECR to allow EC2 stuff to access the private repo: (Athens)