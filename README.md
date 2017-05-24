# Shibboleth-JMeter-Testing



## Prerequisites.

### Jmeter. Install.
How to installed JMeter [official JMeter](http://jmeter.apache.org/usermanual/get-started.html)

## Modify Parameters:User Defined Variablesi n JMeter Console.
* **CAS_SERVER**
```
 This your CAS Server where Shibboleth Server is pointing : eg: cas.test.com
```

* **IDPS_SERVER**
```
URL of Identity Provider. eg: testidp.test.com
```

* **SP_URL**
```
URL of Service Provider: eg: testsp.somesp.com
```
## User data List.
```
Create a new file in the JMeter\bin\cas-users.csv. having USERNAME,PASSWORD with commma separated.
```

## Sample Setup.
### Sample Setup for JMeter
![SampleSet](/images/setup.jpg?raw=true "Sample Setup")



### Sample User Configuration for JMeter
![Sample User Setup](/images/config.jpg?raw=true "Sample User Configuration")

## Links.

* [Apache JMeter Official Documentation](http://jmeter.apache.org/usermanual/index.html)
* [Apache JMeter Get Started Official Documentation](http://jmeter.apache.org/usermanual/get-started.html)
