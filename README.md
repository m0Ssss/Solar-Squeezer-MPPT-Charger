# MPPT-solar-charger---simple
Simple solar charger using the spv1040 MPPT IC and a DIO6605B 5v out step up. 

0.3-4.2V in, single cell charger with USB out. 

SPV1040 - CC CV charging; over voltage in protection, reverse polarity protection. 

DIO6605B - IC disabled at Lithium battery overdischarge threshold using 2.4v zener diode. 

Thermistor to disable charging at over temperature. 

Using 2x 0.5v solar cells in series: we bought these from Aliexpress (https://www.aliexpress.com/item/1005004078313193.html?spm=a2g0o.productlist.main.1.a8662c1fw73vHF&algo_pvid=46a3f4ab-7525-4bb2-89c4-726baa17c553&algo_exp_id=46a3f4ab-7525-4bb2-89c4-726baa17c553-0&pdp_npi=4%40dis%21SEK%2171.32%2171.32%21%21%216.78%216.78%21%40211b813b17257091241408812e044c%2112000027967400926%21sea%21SE%21929281192%21X&curPageLogUid=nNXq3YYhi0kG&utparam-url=scene%3Asearch%7Cquery_from%3A)
