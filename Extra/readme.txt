INSTALLATION

    On Mac OS X, you may optionally install ZOEService.service under your
    home ~/Library/Services directory. This will integrate ZOE with Mac OS
    X system services next time you log in. For the service to work 
    properly, the application itself need to be running.

    Also on Mac OS X, you may optionally install ZOEMail.mailbundle under 
    your home ~/Library/Mail/Bundles directory. This will integrate ZOE 
    with Apple's Mail.app next time you restart Mail.app. For the bundle to 
    work properly, the application itself need to be running and you may 
    need to enable bundles loading in Mail.app. From the command line:
    
    defaults write com.apple.mail EnableBundles YES
    defaults write com.apple.mail PreferPlainText YES

    Also on Mac OS X, you may optionally install ZOEPreference.prefPane 
    under your home ~/Library/PreferencePanes directory. This will 
    integrate ZOE with Mac OS X system preferences.
    
UNINSTALL

    Delete ~/Library/Services/ZOEService.service and
     ~/Library/Mail/Bundles/ZOEMail.mailbundle.


MORE INFORMATION

    http://guests.evectors.it/zoe/


MAILING LIST

    http://sourceforge.net/mail/?group_id=54877
    http://news.gmane.org/gmane.mail.zoe.general


FEEDBACK

    mailto:zoe-general@lists.sourceforge.net


NOTA BENE

    This software is at an early stage of development.
