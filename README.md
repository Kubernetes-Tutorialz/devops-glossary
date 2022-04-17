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
9. [Cloud Computing](#Cloud-Computing)
10. [SRE](#SRE)
11. [DevOps Engineer](#DevOps-Engineer)
12. [Continuous Delivery](#Continuous-Delivery)
13. [Continuous Integration](#Continuous-Integration)
14. [Continuous Deployment](#Continuous-Deployment)
15. [Cloud Native Apps](#Cloud-Native-Apps)
16. [Jenkins](#Jenkins)
17. [AWS](#AWS)


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
- [ ] *harmony between Dev and Ops Teams*: através do DevOps é possível que haja essa união mais amigável.
- [ ] *Logging and monitoring*: monitoramento através de logs e métricas no processo de que envolve DevOps.

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

#### What is it
[GitHub](https://github.com/) é uma plataforma completa de gerenciamento de repositórios [Git](https://git-scm.com/) para colaboração e controle de versão. O GitHub permite que você (e outras pessoas) trabalhem juntos em projetos de TI. Voltado para o mercado DevOps, o GitHub é disparado uma das ferramentas mais utilizadas por profissionais da área, comunidades, projetos open-source e abriga uma infinidade de projetos de divesos tamanhos e empresas ao redor do mundo. O GitHub foi comprado pela Microsoft e tem recebido muitas melhorias, entre elas *Actions*, *Copilot*, *Pages* e outras features.

#### Main concepts
- [ ] *Branch*: é usada para trabalhar com diferentes versões de um repositório ao mesmo tempo.
- [ ] *Pull request*:  é uma sugestão de melhoria, propondo que suas alterações sejam mescladas com a branch main.
- [ ] *Issues*: é uma ferramenta de rastreamento integrada ao repositório do GitHub para correção de problemas.
- [ ] *GitHub Actions*: conecta todas as ferramentas para automatizar as etapas do fluxo de CI/CD.
- [ ] *Commits*: no GitHub as alterações no código são chamadas de commits.
- [ ] *Repository*: usado para armazenar um projeto de desenvolvimento contendo arquivos (HTML, CSS, Java).
- [ ] *Git*: é um sistema de controle de versão distribuído gratuito e de código aberto para projetos de TI.
- [ ] *Gists*: uma feature fornecida pelo  GitHub para que você possa compartilhar trechos curtos de código.
- [ ] *Readme.md*: arquivo usado para documentação do projeto/repositório no GitHub.

#### Alternatives
- [ ] [GitLab](https://about.gitlab.com/)
- [ ] [Bitbucket](https://bitbucket.org/)
- [ ] [AWS Code Commit](https://aws.amazon.com/pt/codecommit/)
- [ ] [Google Cloud Source Repositories](https://cloud.google.com/source-repositories/docs)
- [ ] [Gogs](https://gogs.io/)
- [ ] [RhodeCode](https://rhodecode.com/)

#### How it helps
O GitHub ajuda no gerenciamento de projetos focado em colaboração e nas melhores práticas de desenvolvimento de software/produto, pois, possui um portfólio gigantesco de features e componentes como as *Actions* que lhes permite conectar e entregar software de forma mais rápida e assertiva, focando em todas as etapas do ciclo de desenvolvimento até o ponto de deploy do aplicativo. O GitHub também ajuda a organizar melhor seus projetos/documentações, é muito usado pela comunidade e com baixa curva de aprendizado, visto que, sua documentação é direta ao ponto, bem exemplificada e possui muito conteúdo pela web.


## VIM

#### What is it
O [VIM](https://www.vim.org/) é o editor nativo do Linux em muitas distribuições existentes hoje no mercado, como Ubuntu, Debian, CentOS, Fedora. É a melhoria da antigo *Vi* usado por muito tempo em sistemas Linux. Com novas funcionalidades implementadas, o *VIM* se tornou popular e muito usado em todo o mundo, é bem simples, possui modos de edição e modos de comandos que facilita o trabalho do Administrador de Sistemas a trabalhar com arquivos do sistema via linha de comando.

#### Main commands
- [ ] `:w` comando usado para salvar o conteúdo sem sair do editor.
- [ ] `:wq`  comando usado para salvar o conteúdo e sair do editor.
- [ ] `h` Move o cursor pra esquerda
- [ ] `j` Move o cursor pra baixo
- [ ] `k` Move o cursor pra cima
- [ ] `l` Move o cursor pra direita
- [ ] `H` Move o cursor para o topo da tela
- [ ] `M` Move o cursor para o meio da tela

#### Alternatives
 - [ ] [Nano](https://www.nano-editor.org/)
 - [ ] [Gedit](https://wiki.gnome.org/Apps/Gedit)
 - [ ] [Neovim](https://neovim.io/)
 - [ ] [Notepad++](https://notepad-plus-plus.org/)
 - [ ] [Sublime](https://www.sublimetext.com/)
 - [ ] [Emacs](https://www.gnu.org/software/emacs/)

#### How it helps
O *VIM* se diferencia dos demais editores de texto do Linux, devido à gama de funcionalidades adotadas e seu alto nível de uso pela comunidade, o que fez se tornar padrão em muitas distribuições Linux. Por ser simples, ele ajuda e facilita qualquer edição de arquivo, você pode usar modos de comandos, modos de visualização e desempenhar rapidamente suas tarefas com *VIM*. Outro ponto importante é que ele pode ser usado facilmente como editor de ferramentas DevOps, como o próprio *Ansible*, bastando setar apenas alguns parâmetros e você já tem identação, tabulação e espaçamento configurados.


## Cloud Computing

#### What is it
É um modelo que oferece recursos de computação como recursos de CPU, rede e disco sob demanda pela internet. A computação em nuvem oferece aos usuários a capacidade de acessar e usar o poder de computação em um local físico remoto. Para o serviço de Computação em Nuvem, existem grandes provedores de Nuvem no mercado de TI, como, AWS, Azure, IBM Cloud, GCP, Digital Ocean, que oferecem uma extensa gama de serviços e produtos para empresas com foco para muitos serviços do mercado.

#### Main concepts
- [ ] *Elasticity*: capacidade de dimensionar e reduzir quando necessário.
- [ ] *Agility*: desenvolver, testar e lançar rapidamente aplicativos de software.
- [ ] *Scalability*: acomodar cargas maiores tornando o hardware mais forte ou adicionando nós adicionais.
- [ ] *Flexibility*: alterar os tipos de recursos quando necessário.
- [ ] *IaaS*: infraestrutura como serviço, o IaaS oferece acesso a recursos de rede, computadores (virtuais ou em hardware
dedicado) e espaço de armazenamento de dados.
- [ ] *SaaS*: software como serviço, é fornecida o produto/aplicativo completo, executado e gerenciado pelo provedor de
serviços.
- [ ] *PaaS*: plataforma como serviço, o provedor oferece uma plataforma com foco na implantação e no gerenciamento de aplicativos, sem a necessidade de gerenciar infraestrutura como (SO e hardware).

#### How it helps
Os provedores de nuvem como AWS, Azure, GCP, oferecem às empresas a capacidade de alugar/testar recursos de computação sob demanda e pagar pelo uso. Isso permite muitas vantagens como, as empresas podem experimentar coisas sem perder tempo planejando e gastando dinheiro ou recursos em nova infraestrutura física e podem escalar conforme necessário e sob demanda. 


## SRE

#### What is it

#### What is it

#### Main commands


## DevOps Engineer

#### What is it
Profissional de TI que introduz processos, ferramentas e metodologias para equilibrar as necessidades ao longo de todo o ciclo de desenvolvimento de software/produto, desde a parte de codificação do software até o deploy em produção do aplicativo.

#### Main concepts
- [ ] *DevSecOps*: É uma abordagem à cultura DevOps que tem como foco manter a segurança em todos as etapas.
- [ ] *communication*: é você saber passar uma informação de forma assertiva, direta e objetiva de forma assíncrona.
- [ ] *contribution*: é você colaborar com os times internos e com a comunidade buscando sempre agregar valor e conhecimento.
- [ ] *automation*: mindset focado em aplicar melhorias no ambiente, sair do modo manual de fazer as coisas.

##### How it helps
A cultura DevOps tem como ponto principal a unificação e a automação de processos. Portanto, DevOps Engineers são muito importantes na combinação de códigos e no gerenciamento de aplicações/infraestrutura. Para a realização de todas essas tarefas, o profissional precisa compreender não somente os ciclos de vida de desenvolvimento de software, mas também a cultura DevOps, incluindo filosofia, práticas e ferramentas. Ser um DevOps Engineer vai além de conhecer produtos ou tecnologias específicas, até porque isso muda com o avanço da tecnologia, você precisa ser um profissional que possui *mindset* de automação, de colaboração e com vontade de ajudar as pessoas no time, sentar do lado do colega, explicar o que for preciso, é uma mudança completa na cultura e nos processos do ambiente de trabalho.


## Continuous Delivery

#### What is it
A entrega contínua (CD) é um conjunto de práticas em que as alterações de código são implantadas automaticamente em um ambiente de aceitação (ou, no caso de implantação contínua, em produção). O CD inclui procedimentos cruciais para garantir que o software seja testado adequadamente antes da implantação e fornece uma maneira de reverter as alterações, se necessário. A integração contínua (CI) é o primeiro passo para a entrega contínua (ou seja, as alterações precisam ser mescladas de forma limpa antes de serem testadas e implantadas).

#### Main concepts
- [ ] *Version control*: permite que uma equipe de desenvolvedores colabore com eficiência em uma base de código compartilhada.
- [ ] *Git*: ferramenta utilizada para gerenciar e versionar todo o processo de desenvolvimento de software.
- [ ] *Automation*: é o uso de softwares para criar processos que substitui ou reduz a interação humana com os sistemas de TI. 
- [ ] *DevOps tools*: stack de ferramentas/tecnologias de DevOps que suporta o processo de CI/CD e outras etapas.
- [ ] *GitLab*: ferramenta completa com foco em pipelines de CI/CD.
- [ ] *Jenkins*: ferramenta focada em CI/CD que permite aos profissionais criarem, testarem e implantarem software.
- [ ] *pipeline*: uma sequência de etapas para fazer o correto deploy em um ambiente de produção.
- [ ] *agile development*: processo que visa facilitar o desenvolvimento (entregas pequenas e mais rápidas).

#### How it helps
As estratégias de CD criam um caminho totalmente automatizado para a produção que testa e implanta o software usando várias estratégias de implantação. Isso permite que os desenvolvedores implantem código com frequência, dando a eles a tranquilidade de saber que a nova revisão foi testada.


## Continuous Integration

#### What is it
A integração contínua, é a prática de integrar as alterações de código com a maior regularidade possível. CI é um pré-requisito para entrega contínua (CD). Tradicionalmente, o processo de CI começa quando as alterações de código são confirmadas em um sistema de controle de origem (Git, Mercurial ou Subversion) e termina com um artefato testado pronto para ser consumido por um sistema de CD. Basicamnete, dentro de Ci você permite que os desenvolvedores mesclem com frequência as alterações de código em um repositório central (projeto) onde builds e testes são executados

#### Main concepts
- [ ] *CircleCI*: ferramenta usada no processo de CI para suportar a etapa de continuous Integration.
- [ ] *AWS Code Pipeline*: ferramenta de CI da AWS que permite  integração com outros serviços da AWS.
- [ ] *Azure Pipelines*: ferramenta de CI que se integra ao conjunto de serviços do Azure.
- [ ] *artifact*: é um subproduto do desenvolvimento de software que auxili no desenvolvimento.
- [ ] *continuous*: manter a regularidade de *commits* no projeto para tornar o processo mais simples.
- [ ] *Git*: usado em muitos projetos para suportar o controle de versão.
- [ ] *build automation*: a cada nova versão do aplicativo, focar no build com ferramentas e automação.
- [ ] *daily integration*: fundamental para reduzir os custos do projetos e ajudar nos prazos do projeto.
- [ ] *Jenkins*: ferramenta que suporta esse processo, usa plugins (+900), adorada pelo mundo DevOps.
- [ ] *Travis*: ferramenta usada para esse processo também de CI.

#### How it helps
É uma prática recomendada primária de DevOps, permitindo que os desenvolvedores mesclem com frequência as alterações de código em um repositório central onde builds e testes são executados.

## Continuous Deployment

#### What is it
A implantação contínua vai um passo além da entrega contínua, implantando o software finalizado diretamente na produção. A implantação contínua (CD) anda de mãos dadas com a integração contínua (CI) e é frequentemente chamada de CI/CD. O processo de CI testa se as alterações em um determinado aplicativo são válidas e o processo de CD implanta automaticamente as alterações de código em ambientes de produção/desenvolvimento.

#### Main concepts
- [ ] *artifact*:


#### How it helps
Ao automatizar o ciclo de lançamento e forçar as organizações a lançar para produção com mais frequência, a CD faz o que a CI fez pelas equipes de desenvolvimento para as equipes de operações. Especificamente, ele força as equipes de operações a automatizar as partes dolorosas e propensas a erros das implantações de produção, reduzindo o risco geral. Também torna as organizações melhores em aceitar e se adaptar às mudanças de produção, o que leva a uma maior estabilidade.


## Cloud Native Apps

#### What is it
Cloud Native ou [CNCF](https://www.cncf.io/) (Cloud Native Computing Foundation) faz parte da [Linux Foundation](https://linuxfoundation.org/) e tem propósito criar, manter e ajudar toda a comunidade em torno de projetos, conferências e eventos focados em nuvem. São milhares de desenvolvedores, Cloud Engineers, DevOps Engineers atuando em conjunto suportando todo o leque de projetos da CNCF. Os aplicativos nativos em nuvem são criados para fornecer e entregar todos os benefícios da computação em nuvem. Esses aplicativos estão integrados com diversos provedores de nuvem do mundo como (AWS, GCP, Azure) e podem com isso aproveitar todas as vantagens de cada produto forcendo mais agilidade, inovação para o escopo de uma infraestrutura/produto.

#### Main concepts
- [ ] *Cloud Computing*: termo que se refere à computação em nuvem.
- [ ] *CNCF*: sigla que corresponde à Cloud Native Computing Foundation.
- [ ] *Cloud Native Trail Map*:
- [ ] *Cloud Native landscape*:
- [ ] *GitOpCon*: 
- [ ] *Prometheus Day*:
- [ ] *ServiceMeshCon*: 
- [ ] *ArgoCon*: 
- [ ] *KubeCon*:

#### How it helps
Os aplicativos em nuvem entregam inovação, agilidade, rapidez para infraestruturas baseadas em nuvem, uma vez que, como avanço da cultura DevOps e das tecnologias, os aplicativos nativos em nuvem se aderiram à este cenário e a premissa da automação, colaboração trazendo mais resiliência e flexibilidade para serviços e produtos focados em nuvem. Existem uma gama enorme de aplicativos mantidos pela CNCF, que com seu uso trará muitas vantagens, como a parte de containers, provisonamento de infraestrutura e aplicativos focados em CI/CD para gerenciar todo o ciclo de desenvolvimento até o deploy do aplicativo.


## Jenkins

#### What is it
Jenkins é uma ferramenta completa de CI, open-source, totalmente extensível, você pode usar plugins de diversas outras ferramentas que permite integração. O Jenkins fornece uma interface de gerenciamento e possui suporte para diversos modelos de SCMs do mercado e ainda pode ser usado em muitos provedores de nuvem como AWS, Azure, GCP e outros.

#### Main concepts
- [ ] *Plugins*: 

#### Alternatives
- [ ] [GitLab](https://about.gitlab.com/)
- [ ] [CircleCI](https://circleci.com/)
- [ ] [Bamboo](https://www.atlassian.com/br/software/bamboo)

#### How it helps

## AWS

#### What is it
[AWS](https://aws.amazon.com/pt/) é um provedor de nuvem, o mais utilizado hoje no mercado de nuvem do mundo de acordo com o quadrante do Gartner. A AWS é uma plataforma completa que fornece um imenso portfolio de serviços e produtos para diferentes serviços do mercado, tecnologia, games, desenvolvimento de softwaree mais.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)


