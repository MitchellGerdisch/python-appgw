# appgateway v2

The standard model for V2 of the app gateway is that it must use a public IP.

The branch, `mitch/working-public-ip`, has that version of the code.

HOWEVER, as per https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-private-deployment?tabs=portal one can enable a preview feature where this Public IP is not needed.

The branch, `mitch/working-private-ip` is a WORK IN PROGRESS to get that preview feature to work.