---
ID: 73
post_title: Cancel Membership
author: ideantest
post_excerpt: ""
layout: page
permalink: https://ideantest.com/cancel__trashed/
published: true
post_date: 2018-08-23 21:56:35
---
[MM_Member_Decision isMember='true' status='active|overdue']
Click the link below to cancel your membership:
<a href="[MM_Member_Link type='cancelMembership']">Cancel Membership</a>
[/MM_Member_Decision]

[MM_Member_Decision isMember='true' status='pending_cancel']
Your subscription has been canceled and you will no longer be billed.
Your account will remain active until [MM_Member_Data name='cancellationDate' dateFormat='M j, Y'].
[/MM_Member_Decision]

[MM_Member_Decision status='canceled']
Your account is now canceled.
[/MM_Member_Decision]

[MM_Member_Decision isMember='false']
Your account is canceled.
[/MM_Member_Decision]