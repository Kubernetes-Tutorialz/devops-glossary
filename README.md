## Objective
O objetivo principal desse repositório é ajudar você a se desenvolver mais em torno dos conceitos e das ferramentas de DevOps. Resolvi manter o glossário em português, justamente para ajudar as pessoas que estão começando na [área](https://gomex.me/blog/primeiros_passos_devops/). Fique a vontade para me ajudar a escrever esse documento, pense nesse repositório como se fosse um glossário comunitário, onde MUITAS pessoas acessam e escrevem sobre os conceitos e ferramentas, baseadas em suas experiências com DevOps.


## Benefits
Use esse glossário para você entender sobre as [ferramentas](https://4linux.com.br/ferramentas-do-mundo-devops/) de DevOps e os principais conceitos que envolvem o processo de esteira do [DevOps](https://aws.amazon.com/pt/devops/what-is-devops/). Também recomendo fortemente que você use esse glossário para entrevistas de DevOps, estudos e projetos. A parte bacana é, SEMPRE [compartilhe](https://amauryborgesouza.medium.com/) o que você aprender, quando você compartilha e ensina outra pessoa, você aprende DUAS vezes e todos ganham.


## Table of Contents
1. [Ansible](#Ansible)
2. [Terraform](#Terraform)
3. [GitLab](#GitLab)
4. [Kubernetes](#Kubernetes)
5. [DevOps](#DevOps)


## Ansible

#### What is it
[Ansible](https://docs.ansible.com/) é uma ferramenta de automação utilizada para gerência de configuração, deploy de aplicações, e provisionamento de infraestrutura. É extremamente utlizado em ambientes com centenas de servidores. A comunicação é feita através do protocolo `SSH` sem a necessidade de agentes instalados no hosts remotos. Use o Ansible para instalar softwares, automatizar tarefas rotineiras, provisionar infraestrutura, melhorar a segurança dos ativos, aplicar patching em sistemas e compartilhar automação em seu projeto/trabalho/estudos.

#### Main concepts
- [ ] *Ad-hoc*: é um comando ou automação fornecida pelo Ansible para gerenciamento de configuração através da CLI do LINUX.
- [ ] *Playbooks*: é um conjunto de tasks ou tarefas descritas no formato *YML*.
- [ ] *Roles*: é uma estrutura de diretórios organizada de forma lógica para utilização em projetos complexos.
- [ ] *inventory file*: arquivo utilizado para gerenciamento dos hosts que o Ansible vai afetar.
- [ ] *ansible.cfg*: principal arquivo de configuração do Ansible para gerenciar o modo de uso da ferramenta.
- [ ] *modules*: são os métodos escritos em *Python* que o Ansible usa para abstração de comandos (são usados para realizar tarefas de automação).

#### How it helps
Basicamente o *Ansible* ajuda a manter todo o gerenciamento de configuração da sua infraestrutura de forma simples e consistente. O gerenciamento de configuração é o processo usado para manter sistemas computacionais, servidores e softwares em um estado desejado, consistentemente. É uma forma de se certificar de que o sistema funciona como o esperado enquanto as mudanças são feitas. Tradicionalmente, isso é feito de forma manual ou por meio de scripts personalizados criados por administradores de sistemas. Quando o Ansible é usado como uma ferramenta de gerenciamento de configuração, ele ajuda a armazenar e auxiliar na manutenção do estado atual dos sistemas. 


## Terraform

#### What is it
[Terraform](https://www.terraform.io/) é uma ferramenta de *Infrastructure as Code (IaC)*, utilizada para provisionamento de infraestrutura em diversos *providers*, como, AWS, Azure, Google Cloud, Kubernetes, GitLab e outros. Essa abordagem de *IaC* vem sendo muito empregada pelo mercado para você manter sua infraestrutura via código, sendo gerenciada e mantida através do *Git*. Sua infraestrutura é escrita via Terraform usando uma linguagem de configuração declarativa conhecida como *HashiCorp Configuration Language* ou *HCL*.

#### Main concepts
- [ ] *providers*: é o bloco onde você declara qual é o seu *provider* ou produto que você pretende provisionar a infraestrutura ou serviços.
- [ ] *resources*: é o bloco onde você declara um ou mais objetos/recuros da infraestrutura, como exemplo, redes virtuais, instâncias de computação e/ou componentes de armazenamento.
- [ ] *tfstate*: arquivo usado pelo Terraform para gerenciamento do estado da infraestrutura, aqui nesse arquivo que o Terraform sabe o que foi aplicado ou destruído da infraestrutura.
- [ ] *modules*: é o bloco usado para você declarar módulos para o Terraform, os módulos ajudam a deixar seu projeto de Terraform mais organizado, menos complexo e menos repetição de código.

#### How it helps
O Terraform ajuda você a manter a infraestrutura de rede de forma segura e eficiente, pois ele consegue gerenciar o estado da mesma, ou seja, ele entende o que você esta aplicando e quando pretender destruir, ele também saberá o que remover. O Terraform é capaz de determinar o que mudou e criar planos de execução incrementais que podem ser aplicados no seu ambiente. O Terraform é desenvolvido e mantido pela empresa Hashicorp. Ele é gratuito com código fonte aberto e você pode efetuar contribuições na comunidade através do GitHub.

## DevOps

#### What is it
Existe uma discussão muito forte no mercado em torno de DevOps, se é cultura e/ou cargo... mimimi! Esquece isso, DevOps é cultura e ainda mais, vai além da implementação de um conjunto de tecnologias e exige uma mudança completa na cultura e nos processos. Sempre digo que os pilares do DevOps parte da colaboração, comunicação (assíncrona) e automação. Voltado agora para o mercado de trabalho, DevOps está associado à todo o processo, desde o desenvolvimento de aplicativos/infraestrutura até a operação/deploy em produção, daí o termo DevOps.

#### Main concepts
- [ ] *IaC*: é a sigla em inglês que define *Infrastructure as Code*. Significa usar a abordagem de *IaC* para desenvolver sua infraestrutura.
- [ ] *Pipeline*: é o que dizem por esteira de DevOps, ou seja, todo o processo que envolve o desenvolvimento até deploy da aplicação.
- [ ] *DevSecOps*: focado na segurançaem em uma equipe de DevOps, usamos esse termo que está voltado à segurança.
- [ ] *GitOps*: abordagem focada em usar o Git para gerenciamento de infraestrutura e aplicação.
- [ ] *DevOps Engineer*: cargo criado pelo LinkedIn para o profissional que atua diretamente com tecnologias DevOps e sua cultura.
- [ ] *Dev*: desenvolvimento.
- [ ] *Ops*: operações.

#### How it helps
Se aplicável dentro do seu ambiente/empresa a utulização de ferramentas DevOps, você terá muitas vantagens e ganhos na entrega do seu produto/software. O DevOps ajuda na qualidade do código, diminuição de erros humanos, deploys mais rápidos e consistentes com a utlização de boas práticas de CI/CD. Sem contar nas muitas abordagens que estão envolvidas dentro do ciclo de DevOps, podemos citar *IaC*, *GitOps*, *DevSecOps*, entre outras.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)


