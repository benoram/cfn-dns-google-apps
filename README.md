# cfn-dns-google-apps
CloudFormation scripts to setup Google App records for a given Route53 Zone, or to setup an entirely new zone with Google Apps records and Amazon CAA records.


## cfn-dns.yaml
This template creates everything

### Parameters

#### DomainName
The domain name for the zone


## cfn-dns-google-apps.yaml
This template creates just the DNS records for Google Apps in an existing Route53 zone

### Parameters

#### ZoneId
The Route53 Zone to write records to

#### DomainName
The domain name for the zone