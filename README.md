# Analyzing-Linux-Security-Subsystems

This project's goal is to investigate the security of key Linux kernel security subsystems, such as LSMs 
(e.g., SELinux and Landlock), cgroups, and seccomp. Since each of these features has a different 
security model, design, dependencies, and goals, we need a novel approach to finding vulnerabilities 
and analyzing these subsystems. Particularly with a focus on use cases that utilize multiple of these 
features at the same time. For instance, in container environments, many attack vectors are caused 
by vulnerabilities or logical issues in one of these subsystems, which cause escalated privilege. 

We are looking for new vulnerabilities which are caused by unsafe co-operations or 
conflicting policies when two or multiple Linux security subsystems are involved. In the second phase 
we are looking for implementing new tools or improving existing ones to facilitate analysing such 
issues.

