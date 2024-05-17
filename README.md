# es-68-helm-patched
## How-To
- create GitHub repository
- create GitHub page from it
- clone this repo
- put packaged helm chart (.tgz)
- create index.yaml: helm repo index --url https:<github page url>/<path-to-charts-folder> .
- push changes to git repo
- helm repo add <repo-name> <github page url>/<path-to-charts-folder>
- helm repo udpate <repo-name>

## Links
https://www.opcito.com/blogs/creating-helm-repository-using-github-pages
