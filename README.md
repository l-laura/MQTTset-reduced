# Reduced MQTTset PCAP data

Source of original data: [MQTTSet on Kaggle](https://www.kaggle.com/datasets/cnrieiit/mqttset).

These small files of benign and attack data in a MQTT network were created by
extracting the first 1 MB of data from the original MQTTset PCAP files.
The directories contain a train-test split conducted on bidirectional flow basis
with 70% of the flows assigned to test and 30% to training set.

Exceptions:
1. The flood data is split on a packet-basis at 70% due to the data consisting of a single (bidirectional) flow.
2. The `benign-5mb` data has a size of 5 MB, such that it matches the sum of attack traffic volume.

# License

The dataset is licenced under the original MQTTset license: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).