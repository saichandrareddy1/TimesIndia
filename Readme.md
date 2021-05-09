Task: 
Add conversion_fraud column as True for marking a conversion entry as fraud. (As done for the trainig data column conversion_fraud).

Joining with Click log: 
imprId (Click Log) and imprid_cr (Conversion Log - Test and Train Data)

(Use click log data for additional data required for identifying conversion fraud)


Essential Columns:
client id: Advertiser ID
pubclient id: Publisher ID
clickIp: IP Address
clmbuser id : unique user id
impr id: Unique Key for every served impression
site id: Publisher wesite
goal id: Conversion's goal type identification id
City id / State id / CountryDim id: Geo Details
browser id: browser used for accessing publisher on any device on web.
adslot id: slot id where advertisement is displayed on any site (unqiue for all sites)
crtd: timestamp of the action
itmclmb id: Image/Creative shown
ispDimId: Internet Service Provider
devTypeDimId: Device Id
osVerDimId: OS Version

