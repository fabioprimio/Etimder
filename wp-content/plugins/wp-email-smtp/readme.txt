=== WP Email SMTP ===
Contributors: pankajagarwal
Tags: add smtp plugin, mail, mail ssl, mail tls, phpmailer, send email via smtp, smtp, smtp plugin, test email, email, mail smtp, outgoing mail, sendmail, ssl, tls, wordpress smtp, wp mail, wp smtp, wp_mail, gmail, google apps, hotmail, Mailer, mandrill api, oauth2, sendgrid api, smtp, sparkpost api, yahoo, mailgun, mailjet, amazon ses, ses
Requires at least: 3.0.1
Tested up to: 4.6.1
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

WP Email SMTP plugin allows you to connect any SMTP for sending emails from your WordPress site.
It bypasses the normal WP mail function and sends emails using the smtp protocol of your choice. 
You can connect any SMTP service like Amazon SES, MailGun, SendGrid, MailJet, MailGet to send emails using them.

###Below are the list of settings that you can set with this plugin:

1. From Email
2. From Name
3. Mailer
4. Return Path
5. Host
6. Port
7. Encryption
8. Authentication
9. Username
10. Password

You can also try sending a test email with the plugin to check whether all your configurations are working correctly.


###Details of different SMTP services like Hostname, Port number are given below.
------------------------------------------------------------------------------

###Default SMTP Ports & Settings
SMTP Server - Non-Encrypted - Port 25 ( or 587 )
SMTP Server - Secure (TLS) - Port 587
SMTP Server - Secure (SSL) - Port 465

1. Amazon SES SMTP Ports & Settings
Depending upon your region of SES activation. Host name can vary.
Host for US East 1 region is given below.
SMTP Server - Host : email-smtp.us-east-1.amazonaws.com - Secure (TLS) - Port 587

2. SendGrid SMTP Ports & Settings
SMTP Server - Host : smtp.sendgrid.net
Use ports 25 or 587 for plain/TLS connections and port 465 for SSL connections

3. MailGun SMTP Ports & Settings
SMTP Server - Host : smtp.mailgun.org - Secure (TLS) - Port 587

4. Googlemail - Gmail SMTP Ports & Settings
SMTP Server - Host : smtp.gmail.com - Secure (SSL) - Port 465
SMTP Server - Host : smtp.gmail.com - Secure (TLS) - Port 587

5. Outlook.com SMTP Ports & Settings
SMTP Server - Host : smtp.live.com - Secure (TLS) - Port 587

6. Office365.com SMTP Ports & Settings
SMTP Server - Host : smtp.office365.com - Secure (TLS) - Port 587

7. Yahoo Mail SMTP Ports & Settings
SMTP Server - Host : smtp.mail.yahoo.com - Secure (SSL) - Port 465

8. Hotmail SMTP Ports & Settings
SMTP Server - Host : smtp.live.com - Secure (SSL) - Port 465

9. Zoho Mail SMTP Ports & Settings
SMTP Server - Host : smtp.zoho.com - Secure (SSL) - Port 465

10. Mail.com SMTP Ports & Settings
SMTP Server - Host : smtp.mail.com - Secure (SSL) - Port 465

11. Gmx.com SMTP Ports & Settings
SMTP Server - Host : smtp.gmx.com - Secure (SSL) - Port 465


== Installation ==

1. Upload the plugin to your WordPress site.
2. Activate the plugin.
3. Set the options like Host settings, Username, Password and port number inside the plugin options by going to Settings -> WP Email SMTP
4. Send a test email to check everything is working properly.
5. Enjoy


== Screenshots ==
1. Screenshot of Email and SMTP options.
2. Screenshot of test email option.

== Changelog ==
= 1.0.0 =
* Initial Release
