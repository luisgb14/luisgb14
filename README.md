<div align="center">

# Hi, I'm Luis Benavides 👋

**Lead DevOps Engineer @ tpng.inc** · Assigned to [CarNow](https://www.carnow.com) ([@nowinc](https://github.com/nowinc) · [@cneng](https://github.com/cneng))

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luisgb14)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/luisgb14)

</div>

I'm a systems engineer with 18+ years in IT and 10+ years focused on cloud and DevOps, helping teams build reliable platforms and ship with confidence.

Here's my manifest:

```yaml
apiVersion: 43
kind: Human
metadata:
  name: Luis Benavides
  labels:
    origin: venezuela 🇻🇪
    location: colombia 🇨🇴
spec:
  purpose: Help organizations achieve excellence in DevOps and Cloud Infrastructure
  currentRole:
    company: tpng.inc
    position: Lead DevOps Engineer
    assignment:
      client: CarNow 🚗
      githubOrgs: [nowinc, cneng]
  technicalSkills:
    programming:
      - bash
      - python
      - typescript
    devops:
      - docker
      - kubernetes
      - helm
      - argo cd
      - ansible
      - terraform
      - packer
      - pulumi
      - vault
    clouds:
      - aws
      - azure
    cicd:
      - aws code pipeline
      - github-actions
      - gitlab-ci
      - azure-devops
    databases:
      - postgresql
      - mysql
      - mongodb
    operatingSystems:
      - ubuntu
      - red hat
      - amazon linux
      - bottlerocket
  softSkills:
    - leadership
    - communication
    - problem-solving
    - team-building
    - adaptability
  methodologies:
    - agile
    - scrum
  favorites:
    number: 14
    animal: 🐶
    emoji: 👍
    food: 🍔
    drink: 🍺
```

And here's how `spec.technicalSkills` looks once applied:

```console
$ kubectl apply -f luis-benavides.yaml
human.people.io/luis-benavides created

$ kubectl get human luis-benavides -o custom-columns-file=technical-skills.txt
```

| `NAME` | `READY` | `STATUS` | `TOOLS` |
| :-- | :-: | :-- | :-- |
| `programming` | `3/3` | `Running` | <img src="https://skillicons.dev/icons?i=bash,py,ts" height="28" alt="bash, python, typescript" /> |
| `devops` | `9/9` | `Running` | <img src="https://skillicons.dev/icons?i=docker,kubernetes" height="28" alt="docker, kubernetes" /> <img src="https://cdn.simpleicons.org/helm/277A9F" height="28" alt="helm" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/argocd/argocd-original.svg" height="28" alt="argo cd" /> <img src="https://skillicons.dev/icons?i=ansible,terraform" height="28" alt="ansible, terraform" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/packer/packer-original.svg" height="28" alt="packer" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pulumi/pulumi-original.svg" height="28" alt="pulumi" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vault/vault-original.svg" height="28" alt="vault" /> |
| `clouds` | `2/2` | `Running` | <img src="https://skillicons.dev/icons?i=aws,azure" height="28" alt="aws, azure" /> |
| `cicd` | `4/4` | `Running` | <img src="https://skillicons.dev/icons?i=githubactions,gitlab" height="28" alt="github-actions, gitlab-ci" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuredevops/azuredevops-original.svg" height="28" alt="azure-devops" /> |
| `databases` | `3/3` | `Running` | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb" height="28" alt="postgresql, mysql, mongodb" /> |
| `operatingSystems` | `4/4` | `Running` | <img src="https://skillicons.dev/icons?i=ubuntu,redhat,linux" height="28" alt="ubuntu, red hat, linux" /> |
