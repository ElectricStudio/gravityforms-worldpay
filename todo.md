# todo:
what is the "sack" script?

# Worldpay fields
## Mandatory
instId = 300003
cartId = arbitrary, what am I selling?
amount = float, 400.00, the price
currency = GBP
[testMode = 100, if this is testmode, this needs to be in there]

## Optional
desc (255) = string, description of what it is
email (80) = string, shopper's email address
name (40) = string, the shopper's name [in case of test, AUTHORIZED would work, can be either of AUTHORISED, REFUSED, ERROR, CAPTURED]
address1 (84)
address2 (84)
address3 (84)
town (30)
region (30)
postcode (12)
country (2)
tel
hideCurrency



Card Type			/	Card Number
Airplus					122000000000003

American Express		34343434343434

Cartebleue				5555555555554444

Dankort					5019717010103742

Diners					36700102000000
						36148900647913

Discover card			6011000400000000

JCB						3528000700000000

Laser					630495060000000000
						630490017740292441

Maestro					6759649826438453
						6799990100000000019

Mastercard				5555555555554444
						5454545454545454

Visa					4444333322221111
						4911830000000
						4917610000000000

Visa Debit				4462 0300 0000 0000
						4917 6100 0000 0000 003

Visa Electron (UK only)	4917 3008 0000 0000

Visa Purchasing			4484 0700 0000 0000





Transaction results
successful - transaction id, email sent, pn sent
declined - transaction id, email NOT sent, pn NOT sent
cancelled - no transaction id, email NOT sent, pn sent
browser close, etc - no transaction id, email NOT sent, pn NOT sent





Bookmark on line 1443
