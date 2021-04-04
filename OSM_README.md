# udacity-OpenStreetMap
Data Wrangling: Open Street Map
#
#
## Introduction:
The open street map area selected is within the city of Accra in Ghana, West Africa, my place of birth. I'm eager to find out if the street names are properly labeled and record lapses if any are found. The finding can be used by the authorities to adopt a standard street naming convention.
## Problems encountered in the map:
It is revealed that some of the Streets are mislabelled or are not following a conventional namimg method. For example "Mallam Kamaludeen St"and "Mallam Kamka St", "Hilla Limann Hwy" and "Al-Waleed Bin-Tala HW" need to be updated to reflect the correct fully written out street_types. Some street names do not have street_types. It is not unusual to find streets with no street types in Accra, Ghana as shown in the above output. "Odoitso","Ndabaningi sithole", and "Obaakrowaa" Streets are not labelled with the street types in some areas and i know that for a fact because, my grandma lived on "Obaakrowaaa Street". However, I'm going to update these streets by appending "Street" to their street types for the purpose of this project. The local authorities will be notified to fix these lapses and apply the correct street types. See audit output below;

{'441': set(['441']),
 'Borla': set(['Nima Borla']),
 'HW': set(['Al-Waleed Bin-Talal HW']),
 'Hwy': set(['Hilla Limann Hwy', 'Kanda Hwy']),
 'Mayaki': set(['Alhaji Mayaki']),
 'Obaakrowaa': set(['Obaakrowaa']),
 'Odoisto': set(['Odoisto']),
 'Odoitso': set(['Odoitso']),
 'Sithole': set(['Ndabaningi Sithole']),
 'Sreet': set(['Asafoanye Amarkai Sreet']),
 'St': set(['Mallam Kamaludeen St']),
 'St.': set(['Mallam Kamka St.']),
 'Town': set(['New Town']),
 'close': set(['Ajakroba close', 'Obaakrowa close']),
 'highway': set(['Kanda highway']),
 'link': set(['Josiah Tongogaari link', 'Josiah Tongoogari link']),
 'odoitso': set(['odoitso']),
 'street': set(['Adenkum street',
                'Alhaji Mayaki street',
                'Chief Tobloo street',
                'E. A Kotey street',
                'E.A Kotey street',
                'E.A Kottey street',
                'E.A kotey street',
                'Edward Akuffo Addo street',
                'Odoitso street',
                'chief Ali kado street'])}

## Overview of the Data:
It is noted that the individual users who contributed to the population of the accra.osm dataset by count of the uid are 604
## Other ideas about the datasets
