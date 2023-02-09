# terna_api_connection

Repository to connect via Python with Terna (TSO of Italy)

## Terna interaction

In order to get de CLIENT_ID and CLIENT_SECRET we need to register in Terna Developer website:

https://developer.terna.it/docs/read/Home#en

Once we have not registered, we have to create our application so that Terna provides us with the corresponding client_id and secret_id.

https://developer.terna.it/docs/read/How_to_register_an_application#en

## Functions

get_terna_token() allows to get the token. Every token has a duration of 300 seconds

terna_api(token, ini_date, end_date, type_code) allows to download the data from terna. You may need:

  - token, by using get_terna_token() function
  - ini_date, initial date to download data
  - end_date, end date to download data
  - type_code, Terna has 3 sections in their API: Load, Generation and Transminission.

### Load

### Generation 

### Transmission
  			


