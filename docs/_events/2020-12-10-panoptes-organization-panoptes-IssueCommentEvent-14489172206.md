---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-12-10
repo_name: panoptes-organization/panoptes
html_url: https://github.com/panoptes-organization/panoptes/issues/130
repo_url: https://github.com/panoptes-organization/panoptes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/panoptes-organization/panoptes/issues/130' target='_blank'>panoptes-organization/panoptes#130</a>.

<small>I'm creating an interface "Snakemake Interface" == snakeface that serves as a wrapper to snakemake - basically having database models that map to workflows, workflow collections, etc., and I'm creating it so that the user can run it as a notebook and then log in with a token, or it can be deployed on some HPC or cloud environment with a custom configuration of backends. E.g., if an HPC cluster wants to configure a front end for users to log in with LDAP or SAML and then only expose the slurm (cluster) executor, that would work. To have snakemake integrated with the logging I'm basically going to override those endpoints to send updates to the same server that will update the interface - and it's the structure of those messages that I think we could develop a standard for, meaning endpoints and then data. This would mean that any application that implements those endpoints and expects a particular format of data could be plugged into snakemake. I figure since you've already developed something, we maybe could start with that, and then I could take a look, contribute feedback, and implement it for snakeface as well? I'm also happy to do any sort of PRs to snakemake that might be needed. And yes, I'd love to work together! I really love snakemake, so I'm definitely enjoying this little side project <3 ...</small>

<a href='https://github.com/panoptes-organization/panoptes/issues/130' target='_blank'>View Comment</a>