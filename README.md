# FOSS4G-2019-Presentation
Designing a Land Administration System with Blockchain Elements using Open Source Geospatial Software

Elevator Pitch
The Blockchain technology is going to revolutionize the geospatial industry. In this talk, we will present the application of Blockchain in designing a land administration system using open source geospatial software.
Description
Lack of formal property rights is a significant issue in the world. About 70 to 80% of the land parcels worldwide have not been formally registered, resulting in land insecurity for many. Traditional land administration systems for recording property right through deeds or title are not built for inexpensive, efficient, and transparent recording of property rights. We propose a land administration data model based on the Land Administration Domain Model (LADM) concepts of party, spatial unit, and tenure to be used in an open, decentralized, and censorship-resistant blockchain. The elements of a blockchain-based land administration system are presented to see how an immutable trustless registry of land is recorded in an open distributed network of computers.
We will present how the spatial unit is designed based on open source geospatial software, with parcel boundaries generated from drone imagery using QGIS. Drone imagery and parcel data are formatted as GeoPackage and GeoJSON, respectively. Geospatial data is recorded in GeoServer, and is transferred to Postgres and PostGIS to be used in a mobile land titling application. Google map APIs are used to locate the parcels and imagery in the mobile application. The open source geospatial software is installed on the Google cloud platform. 
This system has been implemented in the country of Zambia to record 50,000 land claims. The current land administration system of Zambia is abundant with corruption and inefficiencies. We present that how the blockchain technology can offer a solution to many of these problems by providing a secure land ownership and an immutable history of land transactions. The biggest challenge is the lack of digitized land records. We illustrate that who geospatial data is gathered, serialized, converted into hash and imported into blockchain.

