### Export users from your directory

#### First, connect to your directory using the Connect-AzureAD cmdlet

PS C:\Users\rodejo> connect-azureadAccount                       

#### Next, execute the GetAzureADUser cmdlet and export the output to a csv file

C:\Users\rodejo> get-azureaduser | export-csv "c:\data\allusers.csv"

## end of script ##
##  demostrate push ##
