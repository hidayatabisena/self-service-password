# LDAP Tool Box Self Service Password

## Presentation

Self Service Password is a PHP application that allows users to change their password in an LDAP directory.

The application can be used on standard LDAPv3 directories (OpenLDAP, OpenDS, ApacheDS, Sun Oracle DSEE, Novell, etc.) and also on Active Directory.

![Screenshot](http://ltb-project.org/wiki/_media/documentation/self-service-password/0.6/recaptcha.png?w=800&h=529&tok=fda8bb)

It has the following features:
* Samba mode to change Samba passwords
* Active directory mode
* Local password policy:
  * Minimum/maximum length
  * Forbidden characters
  * Upper, Lower, Digit or Special characters counters
  * Reuse old password check
  * Complexity (different class of characters)
* Help messages
* Reset by questions
* Reset by mail challenge (token sent by mail)
* Reset by SMS (trough external Email 2 SMS service)
* reCAPTCHA (Google API)
* Mail notification after password change

## Documentation

Documentation is available on http://ltb-project.org/wiki/documentation/self-service-password
