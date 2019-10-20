siddhi-map-keyvalue
======================================

The **siddhi-map-keyvalue extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a>
that supports mapping incoming events with Key-Value map format to a stream at the source, and mapping a stream to Key-Value map events at the sink.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-keyvalue">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-keyvalue/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-keyvalue/issues">Issue tracker</a>

## Latest API Docs

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-map-keyvalue/api/1.1.3">1.1.3</a>.

## How to use

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support.

* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this extension you can replace the component <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-keyvalue/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.map.keyvalue</groupId>
        <artifactId>siddhi-map-keyvalue</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ |
| master  | [![Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-map-keyvalue/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-map-keyvalue/) |

---

## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-map-keyvalue/api/1.1.3/#keyvalue-sink-mapper">keyvalue</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#sink-mapper">(Sink Mapper)</a>*<br><div style="padding-left: 1em;"><p>The <code>Event to Key-Value Map</code> output mapper extension allows you to convert Siddhi events processed by WSO2 SP to key-value map events before publishing them. You can either use pre-defined keys where conversion takes place without extra configurations, or use custom keys with which the messages can be published.</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-map-keyvalue/api/1.1.3/#keyvalue-source-mapper">keyvalue</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source-mapper">(Source Mapper)</a>*<br><div style="padding-left: 1em;"><p><code>Key-Value Map to Event</code> input mapper extension allows transports that accept events as key value maps to convert those events to Siddhi events. You can either receive pre-defined keys where conversion takes place without extra configurations, or use custom keys to map from the message.</p></div>

## How to Contribute

  * Please report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-keyvalue/issues">GitHub Issue Tracker</a>.

  * Send your contributions as pull requests to <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-keyvalue/tree/master">master branch</a>.

## Contact us

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>.

 * Siddhi developers can be contacted via the mailing lists:

    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)

    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)

## Support

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology.

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>.
