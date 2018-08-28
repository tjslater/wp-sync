---
ID: 75
post_title: Login – MM
author: ideantest
post_excerpt: ""
layout: page
permalink: https://ideantest.com/member-login/
published: true
post_date: 2018-08-23 21:56:35
---
[MM_Member_Decision isMember='true']
You are already logged in! Need to log out? You can do that <a title="Log out" href="[MM_CorePage_Link type='logout']">here</a>.
[/MM_Member_Decision]

[MM_Member_Decision isMember='false']
[MM_Form type='login']
<div class="mm-login">[MM_Form_Message type='error']
[MM_Form_Message type='success']
<h3>Enter your username and password below</h3>
<table>
<tbody>
<tr>
<td class="mm-label-column"><span class="mm-label">Username</span></td>
<td class="mm-field-column">[MM_Form_Field name='username']</td>
</tr>
<tr>
<td class="mm-label-column"><span class="mm-label">Password</span></td>
<td class="mm-field-column">[MM_Form_Field name='password']</td>
</tr>
<tr>
<td class="mm-label-column"></td>
<td class="mm-field-column">[MM_Form_Button type='login' label='Login']
[MM_Form_Field name='rememberMe' label='Remember me']</td>
</tr>
<tr>
<td class="mm-label-column"></td>
<td class="mm-field-column"><a class="mm-forgot-password" href="[MM_CorePage_Link type='forgotPassword']">Forgot Password</a></td>
</tr>
</tbody>
</table>
</div>
[/MM_Form]
[/MM_Member_Decision]