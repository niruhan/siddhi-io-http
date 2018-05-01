siddhi-io-http
======================================

The **siddhi-io-http extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a> that allows you to receive and publish events via http and https transports. This extension can work with WSO2 Stream Processor. It can also run with standalone Siddhi.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-http">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-http/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-http/issues">Issue tracker</a>

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-http/api/1.0.18">1.0.18</a>.

## How to use 

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension with the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of the <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support. 

* This extension is shipped with WSO2 Stream Processor by default. If you need to use an alternative version of this extension you can replace the component <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-http/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` directory with the component jar of the relevant version.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency to your project together with other Siddhi dependencies.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.io.http</groupId>
        <artifactId>siddhi-io-http</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/view/All%20Builds/job/siddhi/job/siddhi-io-http/badge/icon)](https://wso2.org/jenkins/view/All%20Builds/job/siddhi/job/siddhi-io-http/)|

---

## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-http/api/1.0.18/#http-sink">http</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#sink">(Sink)</a>)*<br><div style="padding-left: 1em;"><p>This extension publishes HTTP events in any HTTP method (i.e., POST, GET, PUT, DELETE)  via HTTP or HTTPS protocols. In addition, this component also provides basic authentication, and allows you to publish events using custom client truststore files when publishing events via the HTTPS protocol. You can also dynamically add any number of headers for each event including the HTTP_METHOD header.</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-http/api/1.0.18/#http-source">http</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source">(Source)</a>)*<br><div style="padding-left: 1em;"><p>The HTTP source receives POST requests via HTTP or HTTPS in format such as <code>text</code>, <code>XML</code> or <code>JSON</code>. If required, you can enable basic authentication to ensure that events are received only from users who are authorized to access the service.</p></div>

## How to Contribute
 
  * Report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-http/issues">GitHub Issue Tracker</a>.
  
  * Send your contributions as pull requests to the <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-http/tree/master">master branch</a>. 
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the following mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to provide support for this extension in production. Our unique approach ensures that all support 
leverages our open development methodology, and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2
.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 

