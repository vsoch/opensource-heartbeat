---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-08-27
repo_name: eksctl-io/eksctl
html_url: https://github.com/eksctl-io/eksctl/issues/7949
repo_url: https://github.com/eksctl-io/eksctl
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/eksctl-io/eksctl/issues/7949' target='_blank'>eksctl-io/eksctl#7949</a>.

<p>[Bug] placement group should be optional for capacity reservations</p><small>When we create a cluster with a capacity reservation (e.g., with GPUs) it's often the case that EFA comes with the set. However, setting a placement group can actually limit the instances you get in the reservation. We had a reservation for 16, but because eksctl sneakily added a default placement group, we only were able to get 11. I was unable to set the groupName to null and had to comment out this block https://github.com/eksctl-io/eksctl/blob/fc24e94034492faeda18c43e17fade077c2ff090/pkg/cfn/builder/managed_launch_template.go#L80-L87 with a custom build of eksctl to create out cluster with a full 16. My suggestion would be to either add an explicit flag that says "don't make a placement group with eFa" or allow the user to create a cluster with efa, but give red warnings about needing the group....</small><a href='https://github.com/eksctl-io/eksctl/issues/7949' target='_blank'>View Comment</a>