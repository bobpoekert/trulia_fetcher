trulia_fetcher
==============

Really simple Python library for scraping property information out of Trulia.

Example:
--------

    >> from trulia_fetcher import fetcher
    >> next(fetcher.get_data('San Francisco, CA'))
    {u'_isDefault': False,
     u'addressForDisplay': u'Address Not Disclosed, San Francisco CA',
     u'addressForUrl': u'Apartment-San-Francisco-CA-94110',
     u'blockStreetView': None,
     u'city': u'San Francisco',
     u'claimed': None,
     u'county': u'SAN FRANCISCO',
     u'countyFIPS': u'06075',
     u'dmaId': 37,
     u'hasPhotos': [u'ps.48/d/5/f/7/picture-uh=bca33fb8ceec4fd88efdffef4facbc9-ps=d5f77c7b8965476e35599c6bd52b561.jpg:15'],
     u'hasStreetView': None,
     u'hash': u'd5c8a642345c185e6834aadae8eb31c',
     u'id': u'3096874481',
     u'indexSource': u'For Rent',
     u'isForeclosure': False,
     u'isRentalCommunity': False,
     u'isSrpFeatured': False,
     u'latitude': 37.76359,
     u'listingType': 3,
     u'locationId': None,
     u'longitude': -122.40666,
     u'neighborhood': u'Potrero Hill',
     u'neighborhoodId': 1453,
     u'numBathrooms': 1,
     u'numBedrooms': 1,
     u'numBeds': 1,
     u'price': 2600,
     u'showStreetView': None,
     u'siteId': 11501354,
     u'stateCode': u'CA',
     u'stateName': None,
     u'status': u'For Rent',
     u'test_type': u'A',
     u'type': u'APARTMENT',
     u'typeDisplay': u'Apartment',
     u'urlType': None,
     u'walkScore': None,
     u'zipCode': u'94110'}
