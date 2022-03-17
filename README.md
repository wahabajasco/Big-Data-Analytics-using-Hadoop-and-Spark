# Bigdata
Module 3: Big Data Analytics Final Project

Tasks 1:
(1) Understanding Dataset: UNSW-NB15
------------------

In 2015, the UNSW-NB15 computer network security dataset was released (Moustafa & Slay, 2015). This dataset contains 2,540,044 realistic modern normal and abnormal (attack) network activities. IXIA traffic generator used three virtual servers to collect these records. Two servers were set up to distribute normal network traffic, while the third was set up to generate abnormal network traffic. The Argus and Bro-IDS tools extracted 49 features from raw network packets, including packet-based and flow-based features. The packet header and payload are used to extract packet-based features (also called packet data). Flow-based features, on the other hand, are created by sequencing packets as they travel through the network from a source to a destination (Zoghi & Serpen, 2020). 

The most important properties in the flow-based feature formulation are the direction, inter-packet length, and inter-arrival times: Flow-based features include total duration (dur) and destination-to-source-time-to-live (dttl). The features are divided into three categories: basic (6–18), content (19–26), and time (27 to 35). Features 36 to 40 are labelled as general-purpose features, while features 41 to 47 are labelled as connection features. 

The category of general-purpose features includes those features that are intended to explain the purpose of an individual record, whereas the category of connection features includes two features that depict the character of the connection among a hundred sequentially ordered records. Attack categories and labels are the final two features. 

The UNSW-NB15 dataset contains nine types of attacks: Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode, and Worms and their signatures are represented by 24246, 2677, 2329, 16535, 44525, 215481, 13987, 1511, and 174 records, respectively. The Argus and Bro-IDS tools are used, and twelve algorithms are developed to generate a total of 49 features with the class label. Consequently, there is a significant lack of balance in the dataset, with Normal records accounting for 87% of the dataset and Worms records accounting for only 0.007% (Zoghi & Serpen, 2020). 
