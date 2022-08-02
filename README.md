# Apica ASM results to Webex
A simple Postman script to post the latest results from Apica Synthetic Monitoring to Webex (*formerly called Webex Teams*).

This script can be set up as a postman "test" in ASM and be scheduled to run and given periods. Note that it will use one "check" license in Apica. It can be hosted on any of the repositories Apica is currently supporting.

The script uses three variables that you need to configure in the Apica ASM portal as "Environment variables" when you set up the script:

    apiAddress=api-wpm2,authTicket={auth_ticket},WebexKey={webex_key}
    
The script was originally developed by Christian Backstrøm from Apica Systems AB, then later slightly modified by Gaute Holmin from SuperOffice AS. For more help, look to the Apica documentation on how to set up a Postman check. 
