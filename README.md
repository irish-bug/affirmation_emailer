# affirmation_emailer (and joke_emailer)
A simple emailer script that sends a daily affirmation.

This script was written for Linux by @bust3r_byt3s. It requires msmtp to be installed and configured.
 Directions for this can be found here: https://wiki.archlinux.org/index.php/Msmtp
 To add or remove affirmations, edit file "affirmations_list.txt" ("jokes_list.txt")
 To add or remove recipients, edit /etc/aliases as follows:
   See man 5 aliases for format
        
    affirmations: <mail_recipient1>, <mail_recipient2>, <mail_recipient3>
    (jokes: <mail_recipient1>, <mail_recipient2>, <mail_recipient3>)

 You will also need to add the line 
  aliases /etc/aliases
 to your .msmtprc file. 
 For best results run this script daily from cron
