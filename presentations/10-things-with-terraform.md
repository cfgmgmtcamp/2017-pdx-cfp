## 10 Inspiring Things About Terraform


## Abstract

Terraform is one of the best Infrastructure as Code tool out there. There are
lots of decisions made around it that are really inspiring and that could be
adopted by lots of other cfgmgmt softwares ; this talk will focus on 10 of those
subjects and present how they could be useful for other cfgmgmtconfig
communities.


## Julien Pivotto


## Additional info

Not in the abstract because I do not want to spoil the talk too much, but here
are briefly the 10 inspiring things I would present:

1. Terrafom is configured with play file ; everything. No WebUi, or anything
   like that. Really everything is code.
1. Terraform is fully declarative. Almost no need to specify dependencies.
1. Terraform uses a acyclic graph, enables parallelism
1. Terraform splits the plan for the application
1. Terraform maintains a state file; enabling people to review the current state
   of the infra
1. Terraform takes its data from multiple sources ; files but also state files,
   cloud providers...
1. Terraform is distributed as a single binary ; still with plenty of providers
   included
1. Terraform knows how to create resources but also how to destroy them
1. Terraform has one goal ; does not do everything ; for the rest they rely on
   the hashicorp suite
1. Terraform clearly defines what is community supported and hashicorp supported
1. it's easy to contribute; no CLA ; small PR are merged fast
