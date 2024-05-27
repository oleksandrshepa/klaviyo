# Klaviyo


## Get last data from Trigger.

![image](https://github.com/oleksandrshepa/klaviyo/assets/8615134/a795c95e-9af1-482b-b898-d96f2ee5b863)

Make sure to add this condition before the email send.


## Add abandoned cart link 

`?wck_rebuild_cart={{ event.extra.CartRebuildKey }}`

example: 
`https://digilab.org/demo/tts/basket/?wck_rebuild_cart={{ event.extra.CartRebuildKey }}`




## Useful links
Variable and Filter - https://developers.klaviyo.com/en/docs/glossary_of_variable_filters
