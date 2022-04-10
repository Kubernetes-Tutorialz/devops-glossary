## Objective
O objetivo principal desse repositório, é ajudar à todos os profissinais que estejam buscando conhecimentos e aprimorando suas habilidades em torno dos conceitos e das ferramentas de DevOps. Resolvi manter o glossário em português, justamente para ajudar as pessoas que estão começando na [área](https://gomex.me/blog/primeiros_passos_devops/). Fique à vontade para me ajudar a escrever esse projeto, pense nesse repositório como se fosse um glossário comunitário, onde muitas pessoas acessam, escrevem e enviam *PR's* sobre conceitos, experiências e boas práticas de ferramentas que estão conectadas ao mundo DevOps.


## Benefits
A ideia inicial é ter esse glossário como um guia rápido dos principais conceitos que envolvem as ferramentas de DevOps, tudo isso de forma organizada, com conteúdo direto, curto e sem enrolação. Dessa forma, você pode estudar e aprender sobre DevOps seguindo as documentações das ferramentas, bem como, saber o que é cada ferramenta de DevOps, quais são as alternativas, o que elas buscam ajudar e seus principais componentes. Outro benefício legal do glossário, é que você pode contribuir com o projeto enviando sua sugestão/melhoria em forma de *PR*, essa é uma forma de aprender e colaborar juntos.


## Applicability
- Entrevistas de Devops
- Aprendizado de DevOps
- Hands-on de DevOps
- Guia rápido de DevOps


## Table of Contents
1. [Ansible](#Ansible)
2. [Terraform](#Terraform)
3. [DevOps](#DevOps)
4. [GitLab](#GitLab)
5. [Kubernetes](#Kubernetes)
6. [Linux](#Linux)
7. [GitHub](#GitHub)
8. [VIM](#VIM)
9. [Cloud Native](#ClaoudNative)
10. [SRE](#SRE)


## Ansible

#### What is it
[Ansible](https://docs.ansible.com/) é uma ferramenta de automação utilizada para gerência de configuração, deploy de aplicações, e provisionamento de infraestrutura. É extremamente utlizado em ambientes com centenas de servidores. A comunicação é feita através do protocolo `SSH` sem a necessidade de agentes instalados no hosts remotos. Use o Ansible para instalar softwares, automatizar tarefas rotineiras, provisionar infraestrutura, melhorar a segurança dos ativos, aplicar patching em sistemas e compartilhar automação em seu projeto/trabalho/estudos.

#### Main concepts
- [ ] *Ad-hoc*: é um comando fornecido pelo Ansible para gerenciamento de configuração através da CLI.
- [ ] *Playbooks*: é um conjunto de tasks ou tarefas descritas no formato *YML*.
- [ ] *Roles*: é uma estrutura de diretórios organizada de forma lógica para utilização em projetos complexos.
- [ ] *inventory file*: arquivo utilizado para gerenciamento dos hosts do Ansible.
- [ ] *ansible.cfg*: principal arquivo de configuração do Ansible.
- [ ] *modules*: são os métodos escritos em *Python* para realizar tarefas de automação em *ad-hocs*, *playbooks*.

#### Alternatives
- [ ] [Chef](https://www.chef.io/)
- [ ] [Puppet](https://puppet.com/)
- [ ] [CF-Engine](https://cfengine.com/)
- [ ] [Saltstack](https://saltproject.io/)
- [ ] [Bash (Shell)](https://www.youtube.com/watch?v=EOLPUc6oo-w&list=PLucm8g_ezqNrYgjXC8_CgbvHbvI7dDfhs&ab_channel=B%C3%B3sonTreinamentos)

#### How it helps
Basicamente o *Ansible* ajuda a manter todo o gerenciamento de configuração da sua infraestrutura de forma simples e consistente. O gerenciamento de configuração é o processo usado para manter sistemas computacionais, servidores e softwares em um estado desejado, consistentemente. É uma forma de se certificar de que o sistema funciona como o esperado enquanto as mudanças são feitas. Tradicionalmente, isso é feito de forma manual ou por meio de scripts personalizados criados por administradores de sistemas. Quando o Ansible é usado como uma ferramenta de gerenciamento de configuração, ele ajuda a armazenar e auxiliar na manutenção do estado atual dos sistemas. 


## Terraform

#### What is it
[Terraform](https://www.terraform.io/) é uma ferramenta de *Infrastructure as Code (IaC)*, utilizada para provisionamento de infraestrutura em diversos *providers*, como, AWS, Azure, Google Cloud, Kubernetes, GitLab e outros. Essa abordagem de *IaC* vem sendo muito empregada pelo mercado para você manter sua infraestrutura via código, sendo gerenciada e mantida através do *Git*. Sua infraestrutura é escrita via Terraform usando uma linguagem de configuração declarativa conhecida como *HashiCorp Configuration Language* ou *HCL*.

#### Main concepts
- [ ] *providers*: é o bloco onde você declara qual é o seu produto/Cloud para provisionamento da infraestrutura.
- [ ] *resources*: é o bloco onde você declara um ou mais objetos/recuros da infraestrutura, *VPC*, *EC2*, *RDS*, *ELB*.
- [ ] *tfstate*: arquivo usado pelo Terraform para gerenciamento do estado da infraestrutura.
- [ ] *modules*: é o bloco usado para tratar os módulos (organização, menos complexibilidade e menos repetição de código).

#### Alternatives
- [ ] [Pulumi](https://www.pulumi.com/)
- [ ] [AWS CloudFormation](https://aws.amazon.com/pt/cloudformation/)
- [ ] [Azure Resource Manager](https://azure.microsoft.com/pt-br/features/resource-manager/)
- [ ] [GCP Deployment Manager](https://cloud.google.com/deployment-manager/docs)
- [ ] [Ansible](https://github.com/ansible/ansible)
- [ ] [Crossplane](https://crossplane.io/)

#### How it helps
O Terraform ajuda você a manter a infraestrutura de rede de forma segura e eficiente, pois ele consegue gerenciar o estado da mesma, ou seja, ele entende o que você esta aplicando e quando pretender destruir, ele também saberá o que remover. O Terraform é capaz de determinar o que mudou e criar planos de execução incrementais que podem ser aplicados no seu ambiente. O Terraform é desenvolvido e mantido pela empresa Hashicorp. Ele é gratuito com código fonte aberto e você pode efetuar contribuições na comunidade através do GitHub.

## DevOps

#### What is it
Existe uma discussão muito forte no mercado em torno de DevOps, se é cultura e/ou cargo... mimimi! Esquece isso, DevOps é cultura e ainda mais, vai além da implementação de um conjunto de tecnologias e exige uma mudança completa na cultura e nos processos. Sempre digo que os pilares do DevOps parte da colaboração, comunicação (assíncrona) e automação. Voltado agora para a tecnologia, DevOps está associado à todo o processo, desde o desenvolvimento de aplicativos/infraestrutura até a operação/deploy em produção, daí o termo DevOps.

#### Main concepts
- [ ] *IaC*: é a sigla em inglês que define *Infrastructure as Code*, desenvolver sua infraestrutura usando código.
- [ ] *Pipeline*: podemos dizer que é uma esteira de DevOps, que envolve o desenvolvimento até deploy da aplicação.
- [ ] *DevSecOps*: derivado do DevOps, a metodologia de DevSecOps é focada em segurança.
- [ ] *GitOps*: abordagem focada em usar o Git para gerenciamento de infraestrutura e aplicação.
- [ ] *DevOps Engineer*: cargo criado pelo LinkedIn para o profissional que atua diretamente com tecnologias DevOps.
- [ ] *Deploy*: significa você implantar o aplicativo/produto/infraestrutura, pôr em produção, pôr no ar.
- [ ] *Roadmap*: é um roteiro de estudos que envolvem ferramentas, conceitos, tecnologias sobre DevOps.
- [ ] *Dev*: desenvolvimento.
- [ ] *Ops*: operações.

#### How it helps
Se aplicável dentro do seu ambiente/empresa a utilização de ferramentas DevOps, você terá muitas vantagens e ganhos na entrega do seu produto/software. O DevOps ajuda na qualidade do código, diminuição de erros humanos, deploys mais rápidos e consistentes com a utlização de boas práticas de CI/CD. Sem contar nas muitas abordagens que estão envolvidas dentro do ciclo de DevOps, podemos citar *IaC*, *GitOps*, *DevSecOps*, entre outras. Falando da cultura, você terá ganhos voltados em automação, colaboração e comunicação totalmente direta, consistente e objetiva, pois, DevOps foca nessas melhorias e nas pessoas, para que a entrega do software/produto ocorra sem grandes interrupções e bloqueios.

## GitLab

#### What is it
[GitLab](https://about.gitlab.com/) é uma das principais ferramentas de DevOps hoje no mercado de TI, isso devido a toda gama de serviços oferecida, indo desde a parte de pipeline de CI/CD até recursos avançados de segurança.

#### Main concepts
- [ ] *Pipelines*: dentro do GitLab um pipeline é toda a esteira que envolve o processo de CI/CD do software/produto.
- [ ] *Milestones*: uma forma de rastrear problemas para atingir uma meta maior do projeto
- [ ] *Merge Requests*: são sugestões de melhorias que você cria para um determinado projeto/código.
- [ ] *Projects*: é a forma de você organizar seu projeto com issues, merge requests, pipelines de CI/CD.
- [ ] *Continuous Delivery (CD)*: é uma prática na qual as alterações de código são implantadas automaticamente.
- [ ] *Continuous integration (CI)*: é a prática de integrar alterações de código com a maior regularidade possível.

#### Alternatives
- [ ] [GitHub](https://github.com/)
- [ ] [Circle CI](https://circleci.com/)
- [ ] [Jenkins](https://www.jenkins.io/)
- [ ] [Azure DevOps](https://azure.microsoft.com/pt-br/services/devops/#overview)
- [ ] [Drone](https://www.drone.io/)
- [ ] [Travis CI](https://travis-ci.org/)

#### How it helps
O GitLab ajuda na entrega completa de uma esteira de CI/CD para um ambiente de DevOps, seja para desenvolvimento de software/produtos quanto para desenvolvimento de infraestrutura/serviços. Tendo o GitLab implantado no seu ambinente você poderá fazer deploys mais assertivos e de forma mais veloz prezando sempre pela segurança. Outro insight legal da ferramenta é que ela fornece a integração com diversas ferramentas de DevOps como Kubernetes, Terraform, AWS.

## Kubernetes

#### What iS it
[Kubernetes](https://kubernetes.io/pt-br/) é um orquestrador de containers, ele que faz o gerenciamento de PODs, containers dentro do cluster. Podemos dizer que é hoje de longe uma das principais ferramentas dentro do contexto de DevOps, IaC, GitOps pois podemos conectar e integrar o Kubernetes com muitas APIs e ferramentas [Cloud Native](https://www.cncf.io/). 

#### Main concepts
- [ ] *POD*: menor unidade do Kubernetes onde estão armazenados os containers.
- [ ] *etcd*: O *etcd* é um datastore chave-valor distribuído que o k8s utiliza para armazenar as especificações.
- [ ] *Container Runtime*: é o ambiente de execução de contêineres necessário para o funcionamento do k8s. 
- [ ] *kubectl*:
- [ ] *kubelet*:
- [ ] *kubeadm*:

#### Alternatives
- [ ] [OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift/container-platform)
- [ ] [AWS EKS](https://aws.amazon.com/pt/eks/)
- [ ] [GCP GKE](https://cloud.google.com/kubernetes-engine?hl=pt-br)
- [ ] [Azure AKS](https://azure.microsoft.com/pt-br/services/kubernetes-service/)
- [ ] [Nomad](https://www.nomadproject.io/)
- [ ] [Rancher](https://rancher.com/)

#### How it helps
O Kubernetes ajuda na automação de maneira semelhante à infraestrutura tradicional como ferramentas de código, mas tem a vantagem de trabalhar com contêineres que são mais resistentes a desvios de configuração do que máquinas virtuais ou físicas. O Kubernetes usa arquivos no formato `".YML"`, ele também funciona de forma declarativa, e você pode usá-lo em muitos cenários para implantação de aplicativos e infraestruturas.


## Linux

#### What iS it
Linux é um Sistema Operacional, na comunidade open-source você pode encontrar outros tipos de defnições do Linux. mas no geral classificamos como sendo um S.O que possibilita a execução de programas em um computador e outros dispositivos. Voltado para o mercado, hoje o Linux é de longe um dos mais utilizados dentro da comunidade DevOps, isso porque muitas ferramentas de DevOps são baseadas no Linux, como Ansible, Docker entre outras. O Linux pode ser livremente modificado e distribuído.

#### Main concepts
- [ ] *kernel*:
- [ ] *Bash*:
- [ ] *open-source*:
- [ ] *distros*:
- [ ] *Shell Scripts*: 

#### Alternatives
- [ ] [Windows]
- [ ] [MacOS]
- [ ] [FreeBSD]
- [ ] [Solaris]

#### How it helps
O Linux pode ajudar de *N* formas você a manter seus aplicativos. Existem muitas vantagens que o sistema Linux proporciona aos seus usuários e com o Linux é possível fazer uma gama enorme de customizações e personalizações em arquivos do sistema. Gosto de sempre frisar que a CLI *Command Line Interface* do Linux é ideal para começar a aprender os comandos e entender como o sistema funciona. Pelo fato de ser um sistema aberto e ter uma comunidade crescente de desenvolvedores na comunidade, o código está sendo aprimorado e existem *N* cursos, palestras, eventos de Linux hoje disponíveis no mercado.


## GitHub

#### What iS it
[GitHub](https://github.com/) é uma plataforma completa de gerenciamento de repositórios [Git](https://git-scm.com/) para colaboração e controle de versão. O GitHub permite que você (e outras pessoas) trabalhem juntos em projetos de TI. Voltado para o mercado DevOps, o GitHub é disparado uma das ferramentas mais utilizadas por profissionais da área, comunidades, projetos open-source e abriga uma infinidade de projetos de divesos tamanhos e empresas ao redor do mundo. O GitHub foi comprado pela Microsoft e tem recebido muitas melhorias, entre elas *Actions*, *Copilot*, *Pages* e outras features.

#### Main concepts
- [ ] *Branch* - é usada para trabalhar com diferentes versões de um repositório ao mesmo tempo.
- [ ] *Pull request* -  é uma sugestão de melhoria, propondo que suas alterações sejam mescladas com a branch main.
- [ ] *Issues* - é uma ferramenta de rastreamento integrada ao repositório do GitHub para correção de problemas.
- [ ] *GitHub Actions* - conecta todas as ferramentas para automatizar as etapas do fluxo de CI/CD.
- [ ] *Commits* - no GitHub as alterações no código são chamadas de commits.
- [ ] *Repository* - pode ser usado para armazenar um projeto de desenvolvimento contendo arquivos (HTML, CSS, Java).
- [ ] *Git* - é um sistema de controle de versão distribuído gratuito e de código aberto para projetos de TI.
- [ ] *Gists* - uma feature fornecida pelo  GitHub para que você possa compartilhar trechos curtos de código.
- [ ] *Readme.md* - arquivo usado para documentação do projeto/repositório no GitHub.

#### Alternatives
- [ ] [GitLab](https://about.gitlab.com/)
- [ ] [Bitbucket](https://bitbucket.org/)
- [ ] [AWS Code Commit](https://aws.amazon.com/pt/codecommit/)
- [ ] [Google Cloud Source Repositories](https://cloud.google.com/source-repositories/docs)
- [ ] [Gogs](https://gogs.io/)
- [ ] [RhodeCode](https://rhodecode.com/)

#### How it helps
O GitHub ajuda no gerenciamento de projetos focado em *Git* servindo como apoio no controle de versão de projetos, procedimentos, manuais, tecnloogias em geral.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)


