# RoadMap
<h3>Road Map</h3>

This document will outline where this technology is as of October 2022 and where it needs to go to make it more secure and contemporary.<br/>
<br/>
<table>
<tr><th wrap=nowrap>Component</th><th wrap=nowrap>Update Required</th><th wrap=nowrap>Comments</th></tr>
<tr><td valign=top>IIIKey</td><td valign=top>Replace with current symetric encryption</td><td valign=top>IIIkey Homegrown algorithm of dubious quality.<br/>
                                                                        Was useful to get authorization hash implemented across multiple components.</td></tr>
<tr><td valign=top>Typhoon ESMTP Server</td><td valign=top>New ESMTP Server</td><td valign=top>Should a new Open Source version of Typhoon be created using .NET technology or Java?<br/>
                                     Find an existing Open Source ESMTP server and extend it?<br/>
                                     The original was written in Visual Basic 6.</td></tr>
<tr><td valign=top>OEAG Open Email Address Generator</td><td valign=top>New browser extension.</td><td valign=top>Previously this was the weak link in the process.<br/>
                                                                                 The OEAG a separate program had tp be user to generate the<br/>
                                                                                 auth_hash#myuser@mydomain <br/>
                                                                                 This was a potential source of confusion.</td></tr>
<tr><td valign=top>Sendmail configuration</td><td valign=top>Contemporary mail configurations.</td><td valign=top>A hosted version of this technology 'calicomail.com' did exist.<br/>
                                                                                 The hosted version used sendmail, what mailer daemons are in use now?</td></tr>
</table>
