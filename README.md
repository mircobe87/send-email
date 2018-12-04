# send-email
*A bash script based on SENDGRID (https://sendgrid.com/)
that notifyes you via e-mail*.

This application is based on *SENDGRID*, so you have to provide a valid
*API KEY* to be able to use *SENDGRID*'s REST API. Before calling this script
make sure you have exported the environment variable **SENDGRID_API_KEY**.

To obtain a valid *API KEY* please visit the related documentation on *SENDGRID*
web site at https://sendgrid.com.

## Usage

    send-email [OPTIONS]...

### Options

+ __-f, --from-addr__:  Set the e-mail address for the sender. The default value
                        is `send-email@script.bash`.
+ __-F, --from-name__:  Set the name for the sender. The default value is
                        `Send EMail`.
+ __-h, --help__:       Shot this help.
+ __-m, --message__:    Set the e-mail body messate. An empty string is the
                        default value.
+ __-r, --recipients__: A comma separated list of e-mail addresses used as
                        recipients. This value is mandatory.
+ __-s, --subject__:    Set the e-mail subject. If omitted the default value
                        `An e-mail for you` is used.
+ __-v, --version__:    Show version info.
