---
ID: 78
post_title: Reset Password
author: ideantest
post_excerpt: ""
layout: page
permalink: https://ideantest.com/reset-password/
published: true
post_date: 2018-08-23 21:56:35
---
[MM_Member_Decision isMember='true']
You are already logged in! Need to log out? You can do that <a href="[MM_CorePage_Link type='logout']" title="Log out">here</a>.
[/MM_Member_Decision]

[MM_Member_Decision isMember='false']
[MM_Form type='resetPassword']
<div class="mm-resetpassword">
[MM_Form_Message type='error']

<h3>Reset your password</h3>

<table>
    <tr>
      	<td class="mm-label-column">
      		<span class='mm-label'>Password</span>
      	</td>
      	<td class="mm-field-column">
      		[MM_Form_Field name='password']
      	</td>
    </tr>
    <tr>
      	<td class="mm-label-column">
      		<span class='mm-label'>Confirm Password</span>
      	</td>
      	<td class="mm-field-column">
      		[MM_Form_Field name='password-confirm']
      	</td>
    </tr>
    <tr>
      	<td class="mm-label-column"></td>
      	<td class="mm-field-column">
      		[MM_Form_Button type='submit' label='Submit']
      	</td>
    </tr>
</table>
</div>
[/MM_Form]
[/MM_Member_Decision]