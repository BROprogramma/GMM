Aanpassingen in de XSD's:
- brocommon.xsd
  * was:   <import namespace="http://www.opengis.net/gml/3.2" schemaLocation="https://schema.broservices.nl/profile/gml/1.0/gml-profile.xsd"/>
  * wordt: <import namespace="http://www.opengis.net/gml/3.2" schemaLocation="http://schemas.opengis.net/gml/3.2.1/gml.xsd"/>
- Gmm.xsd
  * was:   <xs:import namespace="http://www.broservices.nl/xsd/brocommon/3.0" schemaLocation="https://schema.broservices.nl/xsd/brocommon/3.0/brocommon.xsd"/>
  * wordt: <xs:import namespace="http://www.broservices.nl/xsd/brocommon/3.0" schemaLocation="brocommon.xsd"/>
  * was:   <xs:import namespace="http://standards.iso.org/iso/19115/-3/gex/1.0" schemaLocation="http://standards.iso.org/iso/19115/-3/gex/1.0/gex.xsd"/>
  * wordt: <<verwijderd>>
  * was:   <xs:element name="extent" type="gex:EX_Extent_PropertyType" minOccurs="1" maxOccurs="1">
  * wordt: <xs:element name="extent" type="gml:EnvelopeType" minOccurs="1" maxOccurs="1">
