# Plugins by engine version<a name="supported-plugins"></a>

Amazon OpenSearch Service domains come prepackaged with plugins from the OpenSearch community\. The service automatically deploys and manages plugins for you, but it deploys different plugins depending on the version of OpenSearch or legacy Elasticsearch OSS you choose for your domain\.

The following table lists plugins by OpenSearch version, as well as compatible versions of legacy Elasticsearch OSS\. It only includes plugins that you might interact with—it’s not comprehensive\. OpenSearch Service uses additional plugins to enable core service functionality, such as the S3 Repository plugin for snapshots and the [Open Distro for Elasticsearch Performance Analyzer](https://opendistro.github.io/for-elasticsearch-docs/docs/pa/) plugin for optimization and monitoring\. For a complete list of all plugins running on your domain, make the following request:

```
GET _cat/plugins?v
```


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-plugins.html)