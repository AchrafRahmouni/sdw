# Proposed specification for serving the SSN documents

This document defines proposed specifications for serving the ontologies developed by the W3C/OGC Spatial Data on the Web SSN subgroup.


## SOSA

*URI:* http://www.w3.org/ns/sosa/

*Version to use for publication:* http://w3c.github.io/sdw/ssn/integrated/sosa.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/ with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/ with a Accept header that is compatible with `application/rdf+xml`, serve sosa.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/sosa/sosa.rdf
Content-Disposition: filename= sosa.rdf;
```

When operating a GET at http://www.w3.org/ns/sosa/sosa.rdf with a Accept header that is compatible with `application/rdf+xml`, serve sosa.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= sosa.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/sosa/ with a Accept header that is compatible with `text/turtle`, serve sosa.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/sosa/sosa.ttl
Content-Disposition: filename= sosa.ttl;
```

When operating a GET at http://www.w3.org/ns/sosa/sosa.ttl with a Accept header that is compatible with `text/turtle`, serve sosa.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= sosa.ttl;
```

### The ontology resources:


The list of SOSA resource URLs is:

- http://www.w3.org/ns/sosa/ActuatableProperty
- http://www.w3.org/ns/sosa/Actuation
- http://www.w3.org/ns/sosa/Actuator
- http://www.w3.org/ns/sosa/FeatureOfInterest
- http://www.w3.org/ns/sosa/ObservableProperty
- http://www.w3.org/ns/sosa/Observation
- http://www.w3.org/ns/sosa/Platform
- http://www.w3.org/ns/sosa/Procedure
- http://www.w3.org/ns/sosa/Repeatability
- http://www.w3.org/ns/sosa/Result
- http://www.w3.org/ns/sosa/Sample
- http://www.w3.org/ns/sosa/Sampler
- http://www.w3.org/ns/sosa/Sampling
- http://www.w3.org/ns/sosa/Sensor
- http://www.w3.org/ns/sosa/actsOnProperty
- http://www.w3.org/ns/sosa/madeByActuator
- http://www.w3.org/ns/sosa/hasFeatureOfInterest
- http://www.w3.org/ns/sosa/hasResult
- http://www.w3.org/ns/sosa/hasResultingSample
- http://www.w3.org/ns/sosa/hasSample
- http://www.w3.org/ns/sosa/hosts
- http://www.w3.org/ns/sosa/isActedOnBy 
- http://www.w3.org/ns/sosa/isFeatureOfInterestOf
- http://www.w3.org/ns/sosa/isHostedBy
- http://www.w3.org/ns/sosa/isObservedBy
- http://www.w3.org/ns/sosa/isResultOf
- http://www.w3.org/ns/sosa/isSampleOf
- http://www.w3.org/ns/sosa/isSamplingResultOf
- http://www.w3.org/ns/sosa/madeActuation
- http://www.w3.org/ns/sosa/madeBySampler
- http://www.w3.org/ns/sosa/madeBySensor
- http://www.w3.org/ns/sosa/madeObservation
- http://www.w3.org/ns/sosa/madeSampling
- http://www.w3.org/ns/sosa/observedProperty
- http://www.w3.org/ns/sosa/observes
- http://www.w3.org/ns/sosa/phenomenonTime 
- http://www.w3.org/ns/sosa/usedProcedure 
- http://www.w3.org/ns/sosa/hasSimpleResult
- http://www.w3.org/ns/sosa/hasResultTime


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/xyz with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#SOSAxyz


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/xyz with a Accept header that is compatible with `application/rdf+xml`, 303 redirect to http://www.w3.org/ns/sosa/sosa.rdf


*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/sosa/xyz with a Accept header that is compatible with `text/turtle`, 303 redirect to http://www.w3.org/ns/sosa/sosa.ttl






## SSN

*URI:* http://www.w3.org/ns/ssn/

*Version to use for publication:* http://w3c.github.io/sdw/ssn/integrated/ssn.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/ with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/ with a Accept header that is compatible with `application/rdf+xml`, serve ssn.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/ssn/ssn.rdf
Content-Disposition: filename= ssn.rdf;
```

When operating a GET at http://www.w3.org/ns/ssn/ssn.rdf with a Accept header that is compatible with `application/rdf+xml`, serve ssn.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= ssn.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/ssn/ with a Accept header that is compatible with `text/turtle`, serve ssn.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/ssn/ssn.ttl
Content-Disposition: filename= ssn.ttl;
```

When operating a GET at http://www.w3.org/ns/ssn/ssn.ttl with a Accept header that is compatible with `text/turtle`, serve ssn.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= ssn.ttl;
```

### The ontology resources:

The list of SSN resource URLs is:

- http://www.w3.org/ns/ssn/Deployment
- http://www.w3.org/ns/ssn/Input
- http://www.w3.org/ns/ssn/Output
- http://www.w3.org/ns/ssn/Property
- http://www.w3.org/ns/ssn/Stimulus
- http://www.w3.org/ns/ssn/System
- http://www.w3.org/ns/ssn/deployedOnPlatform
- http://www.w3.org/ns/ssn/deployedSystem
- http://www.w3.org/ns/ssn/detects
- http://www.w3.org/ns/ssn/forProperty
- http://www.w3.org/ns/ssn/hasDeployment
- http://www.w3.org/ns/ssn/hasInput
- http://www.w3.org/ns/ssn/hasOutput
- http://www.w3.org/ns/ssn/hasProperty
- http://www.w3.org/ns/ssn/hasSubSystem
- http://www.w3.org/ns/ssn/implementedBy
- http://www.w3.org/ns/ssn/implements
- http://www.w3.org/ns/ssn/inDeployment
- http://www.w3.org/ns/ssn/isPropertyOf
- http://www.w3.org/ns/ssn/isProxyFor
- http://www.w3.org/ns/ssn/wasOriginatedBy


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/xyz with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#SSNxyz


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/xyz with a Accept header that is compatible with `application/rdf+xml`, 303 redirect to http://www.w3.org/ns/ssn/ssn.rdf


*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/ssn/xyz with a Accept header that is compatible with `text/turtle`, 303 redirect to http://www.w3.org/ns/ssn/ssn.ttl


## SSNX

*URI:* http://purl.oclc.org/NET/ssnx/ssn

*URI on the W3C Server:* https://www.w3.org/2017/01/ssn-ssnx/

*Version to use for publication:* http://w3c.github.io/sdw/ssn/integrated/ssnx.ttl


After having it online, need to ask to change the old redirection to the new location of the document, see https://lists.w3.org/Archives/Public/public-sdw-wg/2017Apr/0124.html 


### The ontology document:

Basic hash-based content-negotiation.


## SSN-DUL

*URI:* http://www.w3.org/ns/ssn/dul

*Version to use for publication:* http://w3c.github.io/sdw/ssn/integrated/ssn-dul.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/dul with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#DUL_Alignment


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/dul with a Accept header that is compatible with `application/rdf+xml`, serve ssn-dul.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/ssn/dul/ssn-dul.rdf
Content-Disposition: filename= ssn-dul.rdf;
```

When operating a GET at http://www.w3.org/ns/ssn/dul/ssn-dul.rdf with a Accept header that is compatible with `application/rdf+xml`, serve ssn-dul.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= ssn-dul.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/ssn/dul with a Accept header that is compatible with `text/turtle`, serve ssn-dul.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/ssn/dul/ssn-dul.ttl
Content-Disposition: filename= ssn-dul.ttl;
```

When operating a GET at http://www.w3.org/ns/ssn/dul/ssn-dul.ttl with a Accept header that is compatible with `text/turtle`, serve ssn.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= ssn-dul.ttl;
```




## SOSA-O&M

*URI:* http(s)://www.w3.org/ns/sosa/om

*Version to use for publication:* http://w3c.github.io/sdw/ssn/rdf/sosa-om-mapping.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/om with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#OM_Alignment


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/om with a Accept header that is compatible with `application/rdf+xml`, serve sosa-om-mapping.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/sosa/om.rdf
Content-Disposition: filename= sosa-om.rdf;
```

When operating a GET at http://www.w3.org/ns/sosa/om.rdf with a Accept header that is compatible with `application/rdf+xml`, serve sosa-om-mapping.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= sosa-om.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/sosa/om with a Accept header that is compatible with `text/turtle`, serve sosa-om-mapping.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/sosa/om.ttl
Content-Disposition: filename= sosa-om.ttl;
```

When operating a GET at http://www.w3.org/ns/sosa/om.ttl with a Accept header that is compatible with `text/turtle`, serve sosa-om-mapping.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= sosa-om.ttl;
```


## SOSA-OBOE

*URI:* http(s)://www.w3.org/ns/sosa/oboe

*Version to use for publication:* http://w3c.github.io/sdw/ssn/rdf/sosa-oboe-mapping.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/oboe with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#OBOE_Alignment


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/oboe with a Accept header that is compatible with `application/rdf+xml`, serve sosa-oboe-mapping.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/sosa/oboe.rdf
Content-Disposition: filename= sosa-oboe.rdf;
```

When operating a GET at http://www.w3.org/ns/sosa/oboe.rdf with a Accept header that is compatible with `application/rdf+xml`, serve sosa-oboe-mapping.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= sosa-oboe.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/sosa/oboe with a Accept header that is compatible with `text/turtle`, serve sosa-oboe-mapping.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/sosa/oboe.ttl
Content-Disposition: filename= sosa-oboe.ttl;
```

When operating a GET at http://www.w3.org/ns/sosa/oboe.ttl with a Accept header that is compatible with `text/turtle`, serve sosa-oboe-mapping.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= sosa-oboe.ttl;
```


## SOSA-PROV

*URI:* http://www.w3.org/ns/sosa/prov

*Version to use for publication:* http://w3c.github.io/sdw/ssn/rdf/sosa-prov-mapping.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/prov with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#PROV_Alignment


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/sosa/prov with a Accept header that is compatible with `application/rdf+xml`, serve sosa-prov-mapping.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/sosa/prov.rdf
Content-Disposition: filename= sosa-prov.rdf;
```

When operating a GET at http://www.w3.org/ns/sosa/prov.rdf with a Accept header that is compatible with `application/rdf+xml`, serve sosa-prov-mapping.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= sosa-prov.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/sosa/prov with a Accept header that is compatible with `text/turtle`, serve sosa-prov-mapping.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/sosa/prov.ttl
Content-Disposition: filename= sosa-prov.ttl;
```

When operating a GET at http://www.w3.org/ns/sosa/prov.ttl with a Accept header that is compatible with `text/turtle`, serve sosa-prov-mapping.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= sosa-prov.ttl;
```



## SSN-System

*URI:* http://www.w3.org/ns/ssn/systems

*Version to use for publication:* http://w3c.github.io/sdw/ssn/integrated/ssn-system.ttl


### The ontology document:


*HTML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/systems with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#System-capabilities


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/systems with a Accept header that is compatible with `application/rdf+xml`, serve ssn-system.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Location: http://www.w3.org/ns/ssn/systems.rdf
Content-Disposition: filename= ssn-system.rdf;
```

When operating a GET at http://www.w3.org/ns/ssn/systems.rdf with a Accept header that is compatible with `application/rdf+xml`, serve ssn-system.rdf, with headers:

```
Content-Type: application/rdf+xml
Content-Disposition: filename= ssn-system.rdf;
```

*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/ssn/systems with a Accept header that is compatible with `text/turtle`, serve ssn-system.ttl, with headers:

```
Content-Type: text/turtle
Content-Location: http://www.w3.org/ns/ssn/systems.ttl
Content-Disposition: filename= ssn-system.ttl;
```

When operating a GET at http://www.w3.org/ns/ssn/systems.ttl with a Accept header that is compatible with `text/turtle`, serve ssn-system.ttl, with headers:

```
Content-Type: text/turtle
Content-Disposition: filename= ssn-system.ttl;
```

### The ontology resources:

The list of SSN resource URLs is:


- http://www.w3.org/ns/ssn/systems/Accuracy
- http://www.w3.org/ns/ssn/systems/ActuationRange
- http://www.w3.org/ns/ssn/systems/BatteryLifetime
- http://www.w3.org/ns/ssn/systems/Condition
- http://www.w3.org/ns/ssn/systems/DetectionLimit
- http://www.w3.org/ns/ssn/systems/Drift
- http://www.w3.org/ns/ssn/systems/Frequency
- http://www.w3.org/ns/ssn/systems/inCondition
- http://www.w3.org/ns/ssn/systems/Latency
- http://www.w3.org/ns/ssn/systems/MaintenanceSchedule
- http://www.w3.org/ns/ssn/systems/MeasurementRange
- http://www.w3.org/ns/ssn/systems/OperatingPowerRange
- http://www.w3.org/ns/ssn/systems/OperatingProperty
- http://www.w3.org/ns/ssn/systems/OperatingRange
- http://www.w3.org/ns/ssn/systems/Precision
- http://www.w3.org/ns/ssn/systems/Resolution
- http://www.w3.org/ns/ssn/systems/ResponseTime
- http://www.w3.org/ns/ssn/systems/SystemCapability
- http://www.w3.org/ns/ssn/systems/SystemProperty
- http://www.w3.org/ns/ssn/systems/Selectivity
- http://www.w3.org/ns/ssn/systems/Sensitivity
- http://www.w3.org/ns/ssn/systems/SurvivalProperty
- http://www.w3.org/ns/ssn/systems/SurvivalRange
- http://www.w3.org/ns/ssn/systems/SystemLifetime
- http://www.w3.org/ns/ssn/systems/hasOperatingProperty
- http://www.w3.org/ns/ssn/systems/hasOperatingRange
- http://www.w3.org/ns/ssn/systems/hasSurvivalProperty
- http://www.w3.org/ns/ssn/systems/hasSurvivalRange
- http://www.w3.org/ns/ssn/systems/hasSystemCapability
- http://www.w3.org/ns/ssn/systems/hasSystemProperty
- http://www.w3.org/ns/ssn/systems/qualityOfObservation

*HTML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/systems/xyz with a Accept header that is compatible with `text/html`, 303 redirect to https://www.w3.org/TR/vocab-ssn/#SSNSYSTEMxyz


*RDF/XML representation:* 

When operating a GET at http://www.w3.org/ns/ssn/systems/xyz with a Accept header that is compatible with `application/rdf+xml`, 303 redirect to http://www.w3.org/ns/ssn/systems.rdf


*Turtle representation:* 

When operating a GET at http://www.w3.org/ns/ssn/systems/xyz with a Accept header that is compatible with `text/turtle`, 303 redirect to http://www.w3.org/ns/ssn/systems.ttl

