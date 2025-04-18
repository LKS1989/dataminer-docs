---
uid: Advanced_analytics_trending
---

# Advanced analytics in trend graphs

A number of features in trend graphs make use of the artificial intelligence capabilities provided by DataMiner Analytics.

Most of these features rely on the SLAnalytics process. These require [Storage as a Service](xref:STaaS) (recommended) or a [self-managed Cassandra-compatible database](xref:Supported_system_data_storage_architectures) and can be activated or deactivated in System Center, via *System Center* > *System settings* > *analytics config*:

- [Working with trend predictions](xref:Working_with_trend_predictions)

- [Working with trend icons](xref:Working_with_trend_icons)

- [Working with behavioral anomaly detection](xref:Working_with_behavioral_anomaly_detection)

- [Working with pattern matching](xref:Working_with_pattern_matching)

Other features depend on a connection to dataminer.services. These cannot be activated or deactivated in System Center, and Cassandra is not strictly required for them, although it is recommended. At present, only one such feature is available: [Adding related parameters to a trend graph](xref:Adding_related_parameters_to_a_trend_graph)

For the related feature [Adding time-scoped related parameters to a trend graph](xref:Adding_time_scoped_related_parameters_to_a_trend_graph), no connection to dataminer.services is required, but if you are using self-managed DataMiner storage (not recommended), your system does need to have an [indexing database](xref:Indexing_Database).

From DataMiner 10.3.0 [CU12]/10.4.3 onwards<!--RN 38407-->, trend data pattern records are saved indefinitely in the indexing database. Prior to DataMiner 10.3.0 [CU12]/10.4.3, trend data pattern records are saved for a duration of 10 years.

> [!TIP]
> For more artificial intelligence capabilities, see [Advanced analytics features in the Alarm Console](xref:Advanced_analytics_features_in_the_Alarm_Console).
