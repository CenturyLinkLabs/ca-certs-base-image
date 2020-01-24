# ca-certs
## NOTE

This repo is no longer being maintained. Users are welcome to fork it, but we make no warranty of its functionality.


[![](https://badge.imagelayers.io/centurylink/ca-certs.svg)](https://imagelayers.io/?images=centurylink/ca-certs:latest 'Get your own badge on imagelayers.io')

`FROM centurylink/ca-certs`

This is a Docker base image which builds off of the [scratch](https://registry.hub.docker.com/u/library/scratch/) image and adds the root certificates for all of the standard certificate authorities. 

This image is useful for building small images that still require certificate verification for out-bound SSL connections. See the [golang-builder](https://registry.hub.docker.com/u/centurylink/golang-builder/) for more information about creating minimal Docker images with statically-linked Go binaries.

The certificate bundle included in this image contains 165 CA certificates. The subject line for each included certificate is shown below.

```
CN=A-Trust-nQual-03
OU=A-Trust-nQual-03
O=A-Trust Ges. f. Sicherheitssysteme im elektr. Datenverkehr GmbH
C=AT

CN=ACCVRAIZ1
OU=PKIACCV
O=ACCV
C=ES

CN=ACEDICOM Root
OU=PKI
O=EDICOM
C=ES

CN=AC RaÃ­z CerticÃ¡mara S.A.
O=Sociedad Cameral de CertificaciÃ³n Digital - CerticÃ¡mara S.A.
C=CO

CN=Actalis Authentication Root CA
O=Actalis S.p.A.
C=IT

CN=AddTrust External CA Root
OU=AddTrust External TTP Network
O=AddTrust AB
C=SE

CN=AddTrust Class 1 CA Root
OU=AddTrust TTP Network
O=AddTrust AB
C=SE

CN=AddTrust Public CA Root
OU=AddTrust TTP Network
O=AddTrust AB
C=SE

CN=AddTrust Qualified CA Root
OU=AddTrust TTP Network
O=AddTrust AB
C=SE

CN=AffirmTrust Commercial
O=AffirmTrust
C=US

CN=AffirmTrust Networking
O=AffirmTrust
C=US

CN=AffirmTrust Premium
O=AffirmTrust
C=US

CN=AffirmTrust Premium ECC
O=AffirmTrust
C=US

CN=America Online Root Certification Authority 1
O=America Online Inc.
C=US

CN=America Online Root Certification Authority 2
O=America Online Inc.
C=US

OU=ApplicationCA
O=Japanese Government
C=JP

CN=Atos TrustedRoot 2011
O=Atos
C=DE

CN=Autoridad de Certificacion Firmaprofesional CIF A62634068
C=ES

CN=Baltimore CyberTrust Root
OU=CyberTrust
O=Baltimore
C=IE

CN=Buypass Class 2 CA 1
O=Buypass AS-983163327
C=NO

CN=Buypass Class 2 Root CA
O=Buypass AS-983163327
C=NO

CN=Buypass Class 3 CA 1
O=Buypass AS-983163327
C=NO

CN=Buypass Class 3 Root CA
O=Buypass AS-983163327
C=NO

CN=CA Disig
O=Disig a.s.
C=SK

CN=CA Disig Root R1
O=Disig a.s.
C=SK

CN=CA Disig Root R2
O=Disig a.s.
C=SK

CN=CNNIC ROOT
O=CNNIC
C=CN

CN=COMODO Certification Authority
O=COMODO CA Limited
C=GB

CN=COMODO ECC Certification Authority
O=COMODO CA Limited
C=GB

CN=Chambers of Commerce Root
OU=http://www.chambersign.org
O=AC Camerfirma SA CIF A82743287
C=EU

CN=Global Chambersign Root
OU=http://www.chambersign.org
O=AC Camerfirma SA CIF A82743287
C=EU

CN=Certigna
O=Dhimyotis
C=FR

CN=Certinomis - AutoritÃ© Racine
OU=0002 433998903
O=Certinomis
C=FR

CN=Class 2 Primary CA
O=Certplus
C=FR

CN=Certum CA
O=Unizeto Sp. z o.o.
C=PL

CN=Certum Trusted Network CA
OU=Certum Certification Authority
O=Unizeto Technologies S.A.
C=PL

CN=Chambers of Commerce Root - 2008
O=AC Camerfirma S.A.
C=EU

CN=China Internet Network Information Center EV Certificates Root
O=China Internet Network Information Center
C=CN

CN=ComSign CA
O=ComSign
C=IL

CN=ComSign Secured CA
O=ComSign
C=IL

CN=AAA Certificate Services
O=Comodo CA Limited
C=GB

CN=Secure Certificate Services
O=Comodo CA Limited
C=GB

CN=Trusted Certificate Services
O=Comodo CA Limited
C=GB

CN=Cybertrust Global Root
O=Cybertrust, Inc

CN=D-TRUST Root Class 3 CA 2 2009
O=D-Trust GmbH
C=DE

CN=D-TRUST Root Class 3 CA 2 EV 2009
O=D-Trust GmbH
C=DE

CN=DST ACES CA X6
OU=DST ACES
O=Digital Signature Trust
C=US

CN=DST Root CA X3
O=Digital Signature Trust Co.

CN=Deutsche Telekom Root CA 2
OU=T-TeleSec Trust Center
O=Deutsche Telekom AG
C=DE

CN=DigiCert Assured ID Root CA
OU=www.digicert.com
O=DigiCert Inc
C=US

CN=DigiCert Global Root CA
OU=www.digicert.com
O=DigiCert Inc
C=US

CN=DigiCert High Assurance EV Root CA
OU=www.digicert.com
O=DigiCert Inc
C=US

OU=DSTCA E1
O=Digital Signature Trust Co.
C=US

OU=DSTCA E2
O=Digital Signature Trust Co.
C=US

CN=e-Guven Kok Elektronik Sertifika Hizmet Saglayicisi
O=Elektronik Bilgi Guvenligi A.S.
C=TR

CN=E-Tugra Certification Authority
OU=E-Tugra Sertifikasyon Merkezi
O=E-TuÄra EBG BiliÅim Teknolojileri ve Hizmetleri A.Å.
C=TR

CN=EBG Elektronik Sertifika Hizmet SaÄlayÄ±cÄ±sÄ±
O=EBG BiliÅim Teknolojileri ve Hizmetleri A.Å.
C=TR

CN=EC-ACC
OU=Serveis Publics de Certificacio Vegeu https://www.catcert.net/verarrel (c)03 Jerarquia Entitats de Certificacio 
O=Agencia Catalana de Certificacio (NIF Q-0801176-I)
C=ES

CN=EE Certification Centre Root CA
O=AS Sertifitseerimiskeskus
C=EE

CN=Entrust.net Certification Authority (2048)
OU=www.entrust.net (c) 1999 Entrust.net Limited
O=Entrust.net

CN=Entrust.net Secure Server Certification Authority
OU=www.entrust.net (c) 1999 Entrust.net Limited
O=Entrust.net
C=US

CN=Entrust Root Certification Authority
OU=www.entrust.net (c) 2006 Entrust, Inc.
O=Entrust, Inc.
C=US

OU=Equifax Secure Certificate Authority
O=Equifax
C=US

CN=Equifax Secure Global eBusiness CA-1
O=Equifax Secure Inc.
C=US

CN=Equifax Secure eBusiness CA-1
O=Equifax Secure Inc.
C=US

CN=GTE CyberTrust Global Root
OU=GTE CyberTrust Solutions, Inc.
O=GTE Corporation
C=US

CN=GeoTrust Global CA
O=GeoTrust Inc.
C=US

CN=GeoTrust Global CA 2
O=GeoTrust Inc.
C=US

CN=GeoTrust Primary Certification Authority
O=GeoTrust Inc.
C=US

CN=GeoTrust Primary Certification Authority - G2
OU=(c) 2007 GeoTrust Inc. - For authorized use only
O=GeoTrust Inc.
C=US

CN=GeoTrust Primary Certification Authority - G3
OU=(c) 2008 GeoTrust Inc. - For authorized use only
O=GeoTrust Inc.
C=US

CN=GeoTrust Universal CA
O=GeoTrust Inc.
C=US

CN=GeoTrust Universal CA 2
O=GeoTrust Inc.
C=US

CN=GlobalSign Root CA
OU=Root CA
O=GlobalSign nv-sa
C=BE

CN=GlobalSign
OU=GlobalSign Root CA - R2
O=GlobalSign

CN=GlobalSign
OU=GlobalSign Root CA - R3
O=GlobalSign

CN=Global Chambersign Root - 2008
O=AC Camerfirma S.A.
C=EU

OU=Go Daddy Class 2 Certification Authority
O=The Go Daddy Group, Inc.
C=US

CN=Go Daddy Root Certificate Authority - G2
O=GoDaddy.com, Inc.
C=US

CN=Hellenic Academic and Research Institutions RootCA 2011
O=Hellenic Academic and Research Institutions Cert. Authority
C=GR

CN=Hongkong Post Root CA 1
O=Hongkong Post
C=HK

CN=IGC
OU=DCSSI
O=PM
C=FR

CN=Izenpe.com
O=IZENPE S.A.
C=ES

CN=Juur-SK
O=AS Sertifitseerimiskeskus
C=EE

CN=Microsec e-Szigno Root CA
OU=e-Szigno CA
O=Microsec Ltd.
C=HU

CN=Microsec e-Szigno Root CA 2009
O=Microsec Ltd.
C=HU

CN=NetLock Arany (Class Gold) FÅtanÃºsÃ­tvÃ¡ny
OU=TanÃºsÃ­tvÃ¡nykiadÃ³k (Certification Services)
O=NetLock Kft.
C=HU

CN=NetLock Uzleti (Class B) Tanusitvanykiado
OU=Tanusitvanykiadok
O=NetLock Halozatbiztonsagi Kft.
C=HU

CN=NetLock Expressz (Class C) Tanusitvanykiado
OU=Tanusitvanykiadok
O=NetLock Halozatbiztonsagi Kft.
C=HU

CN=NetLock Kozjegyzoi (Class A) Tanusitvanykiado
OU=Tanusitvanykiadok
O=NetLock Halozatbiztonsagi Kft.
C=HU

CN=NetLock Minositett Kozjegyzoi (Class QA) Tanusitvanykiado
OU=Tanusitvanykiadok
O=NetLock Halozatbiztonsagi Kft.
C=HU

CN=Network Solutions Certificate Authority
O=Network Solutions L.L.C.
C=US

CN=OISTE WISeKey Global Root GA CA
OU=Copyright (c) 2005 OISTE Foundation Endorsed
O=WISeKey
C=CH

CN=PSCProcert
OU=Proveedor de Certificados PROCERT
O=Sistema Nacional de Certificacion Electronica
C=VE

CN=QuoVadis Root Certification Authority
OU=Root Certification Authority
O=QuoVadis Limited
C=BM

CN=QuoVadis Root CA 2
O=QuoVadis Limited
C=BM

CN=QuoVadis Root CA 3
O=QuoVadis Limited
C=BM

CN=http://www.valicert.com//emailAddress=info@valicert.com
OU=ValiCert Class 3 Policy Validation Authority
O=ValiCert, Inc.

OU=RSA Security 2048 V3
O=RSA Security Inc

CN=Root CA Generalitat Valenciana
OU=PKIGVA
O=Generalitat Valenciana
C=ES

CN=S-TRUST Authentication and Encryption Root CA 2005:PN
O=Deutscher Sparkassen Verlag GmbH
C=DE

CN=SG TRUST SERVICES RACINE
OU=0002 43525289500022
O=SG TRUST SERVICES
C=FR

CN=SecureSign RootCA11
O=Japan Certification Services, Inc.
C=JP

CN=SecureTrust CA
O=SecureTrust Corporation
C=US

CN=Secure Global CA
O=SecureTrust Corporation
C=US

OU=Security Communication EV RootCA1
O=SECOM Trust Systems CO.,LTD.
C=JP

OU=Security Communication RootCA2
O=SECOM Trust Systems CO.,LTD.
C=JP

OU=Security Communication RootCA1
O=SECOM Trust.net
C=JP

CN=Sonera Class1 CA
O=Sonera
C=FI

CN=Sonera Class2 CA
O=Sonera
C=FI

CN=Staat der Nederlanden Root CA
O=Staat der Nederlanden
C=NL

CN=Staat der Nederlanden Root CA - G2
O=Staat der Nederlanden
C=NL

OU=Starfield Class 2 Certification Authority
O=Starfield Technologies, Inc.
C=US

CN=Starfield Root Certificate Authority - G2
O=Starfield Technologies, Inc.
C=US

CN=Starfield Services Root Certificate Authority - G2
O=Starfield Technologies, Inc.
C=US

CN=StartCom Certification Authority
OU=Secure Digital Certificate Signing
O=StartCom Ltd.
C=IL

CN=StartCom Certification Authority G2
O=StartCom Ltd.
C=IL

CN=SwissSign Gold CA - G2
O=SwissSign AG
C=CH

CN=SwissSign Platinum CA - G2
O=SwissSign AG
C=CH

CN=SwissSign Silver CA - G2
O=SwissSign AG
C=CH

CN=Swisscom Root CA 1
OU=Digital Certificate Services
O=Swisscom
C=ch

CN=Swisscom Root CA 2
OU=Digital Certificate Services
O=Swisscom
C=ch

CN=Swisscom Root EV CA 2
OU=Digital Certificate Services
O=Swisscom
C=ch

CN=T-TeleSec GlobalRoot Class 2
OU=T-Systems Trust Center
O=T-Systems Enterprise Services GmbH
C=DE

CN=T-TeleSec GlobalRoot Class 3
OU=T-Systems Trust Center
O=T-Systems Enterprise Services GmbH
C=DE

CN=TC TrustCenter Class 2 CA II
OU=TC TrustCenter Class 2 CA
O=TC TrustCenter GmbH
C=DE

CN=TC TrustCenter Class 3 CA II
OU=TC TrustCenter Class 3 CA
O=TC TrustCenter GmbH
C=DE

CN=TC TrustCenter Universal CA I
OU=TC TrustCenter Universal CA
O=TC TrustCenter GmbH
C=DE

OU=TDC Internet Root CA
O=TDC Internet
C=DK

CN=TÃRKTRUST Elektronik Sertifika Hizmet SaÄlayÄ±cÄ±sÄ±
O=(c) 2005 TÃRKTRUST Bilgi Ä°letiÅim ve BiliÅim GÃ¼venliÄi Hizmetleri A.Å.
C=TR

CN=TÃRKTRUST Elektronik Sertifika Hizmet SaÄlayÄ±cÄ±sÄ±
O=TÃRKTRUST Bilgi Ä°letiÅim ve BiliÅim GÃ¼venliÄi Hizmetleri A.Å. (c) KasÄ±m 2005
C=TR

CN=TÃRKTRUST Elektronik Sertifika Hizmet SaÄlayÄ±cÄ±sÄ±
O=TÃRKTRUST Bilgi Ä°letiÅim ve BiliÅim GÃ¼venliÄi Hizmetleri A.Å. (c) AralÄ±k 2007
C=TR

CN=TWCA Global Root CA
OU=Root CA
O=TAIWAN-CA
C=TW

CN=TWCA Root Certification Authority
OU=Root CA
O=TAIWAN-CA
C=TW

O=Government Root Certification Authority
C=TW

CN=TeliaSonera Root CA v1
O=TeliaSonera

CN=Thawte Premium Server CA
OU=Certification Services Division
O=Thawte Consulting cc
C=ZA

CN=Thawte Server CA
OU=Certification Services Division
O=Thawte Consulting cc
C=ZA

OU=Trustis FPS Root CA
O=Trustis Limited
C=GB

CN=TÃBÄ°TAK  Sertifika Hizmet SaÄlayÄ±cÄ±sÄ± - SÃ¼rÃ¼m 3
OU=Ulusal Elektronik ve Kriptoloji AraÅtÄ±rma EnstitÃ¼sÃ¼ - UEKAE Kamu Sertifikasyon Merkezi
O=TÃ¼rkiye Bilimsel ve Teknolojik AraÅtÄ±rma Kurumu - TÃBÄ°TAK
C=TR

CN=UTN - DATACorp SGC
OU=http://www.usertrust.com
O=The USERTRUST Network
C=US

CN=UTN-USERFirst-Client Authentication and Email
OU=http://www.usertrust.com
O=The USERTRUST Network
C=US

CN=UTN-USERFirst-Hardware
OU=http://www.usertrust.com
O=The USERTRUST Network
C=US

CN=http://www.valicert.com//emailAddress=info@valicert.com
OU=ValiCert Class 1 Policy Validation Authority
O=ValiCert, Inc.

CN=http://www.valicert.com//emailAddress=info@valicert.com
OU=ValiCert Class 2 Policy Validation Authority
O=ValiCert, Inc.

CN=VeriSign Class 3 Public Primary Certification Authority - G4
OU=VeriSign Trust Network (c) 2007 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

CN=VeriSign Class 3 Public Primary Certification Authority - G5
OU=VeriSign Trust Network (c) 2006 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

CN=VeriSign Universal Root Certification Authority
OU=VeriSign Trust Network (c) 2008 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

OU=Class 1 Public Primary Certification Authority
O=VeriSign, Inc.
C=US

OU=Class 1 Public Primary Certification Authority - G2 (c) 1998 VeriSign, Inc. - For authorized use only VeriSign Trust Network
O=VeriSign, Inc.
C=US

CN=VeriSign Class 1 Public Primary Certification Authority - G3
OU=VeriSign Trust Network (c) 1999 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

OU=Class 2 Public Primary Certification Authority - G2 (c) 1998 VeriSign, Inc. - For authorized use only VeriSign Trust Network
O=VeriSign, Inc.
C=US

CN=VeriSign Class 2 Public Primary Certification Authority - G3
OU=VeriSign Trust Network (c) 1999 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

OU=Class 3 Public Primary Certification Authority
O=VeriSign, Inc.
C=US

OU=Class 3 Public Primary Certification Authority - G2 (c) 1998 VeriSign, Inc. - For authorized use only VeriSign Trust Network
O=VeriSign, Inc.
C=US

CN=VeriSign Class 3 Public Primary Certification Authority - G3
OU=VeriSign Trust Network (c) 1999 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

CN=VeriSign Class 4 Public Primary Certification Authority - G3
OU=VeriSign Trust Network (c) 1999 VeriSign, Inc. - For authorized use only
O=VeriSign, Inc.
C=US

CN=Visa eCommerce Root
OU=Visa International Service Association
O=VISA
C=US

CN=WellsSecure Public Root Certificate Authority
OU=Wells Fargo Bank NA
O=Wells Fargo WellsSecure
C=US

CN=XRamp Global Certification Authority
OU=www.xrampsecurity.com
O=XRamp Security Services Inc
C=US

OU=certSIGN ROOT CA
O=certSIGN
C=RO

OU=ePKI Root Certification Authority
O=Chunghwa Telecom Co., Ltd.
C=TW

CN=thawte Primary Root CA
OU=Certification Services Division (c) 2006 thawte, Inc. - For authorized use only
O=thawte, Inc.
C=US

CN=thawte Primary Root CA - G2
OU=(c) 2007 thawte, Inc. - For authorized use only
O=thawte, Inc.
C=US

CN=thawte Primary Root CA - G3
OU=Certification Services Division (c) 2008 thawte, Inc. - For authorized use only
O=thawte, Inc.
C=US
```
