---
layout: page
title: Interoperability and Semantic Technologies 2015-16

img: assets/img/12.jpg
category: 
    - semantic web
related_publications: true
year: 2015
---

#### Syllabus

The course starts arguing about the difference between pair-wise system integration and multi-later system interoperability. It introduces the levels at which the interoperability problem has to be attacked using the HL7 ( specifically, the Reference Information Model \[1\] and the Clinical Document Architcture \[2\]) as a case study. It discusses the two ways interoperability can be achieved: standards and translations. It shows how semantic technologies allowed translation-based interoperability on the Web.

Then, it presents semantic technologies for interoperability. These technologies are very important nowadays because the allow to treat the “variety” dimension of Big Data. It introduces [](http://www.w3.org/RDF/)[RDF](http://www.w3.org/RDF/) \[3\] – a flexible data model to (virtually) represent heterogenous data. It describes [](http://www.w3.org/TR/owl-overview/)[OWL](http://www.w3.org/TR/owl-overview/) \[4\] – a flexible ontological language to model heterogenous data sources in an open world where information cannot be assumed to be complete. It illustrates [](http://www.w3.org/TR/sparql11-overview/)[SPARQL](http://www.w3.org/TR/sparql11-overview/) \[5\] – a query language for RDF. It shows how to put all the pieces together in order to achieve interoperability among heterogenous information systems using principles from [](https://en.wikipedia.org/wiki/Ontology-based_data_integration)[ontology-based data integration](https://en.wikipedia.org/wiki/Ontology-based_data_integration) \[6\]. To close this part, R \[7\] is introduced as a flexible language/environment for statistical computing and the integration with SPARQL is illustrated.

The second part of the course covers the realm of interoperability among systems that process streaming data. These systems are very important nowadays because the allow to treat the “velocity” dimension of Big Data. It motivates the problem statement showing the importance for many Big Data analysis to process data stream from Sensor Networks and Social Media sources. It illustrates how to practically deal with data streams using [](http://www.espertech.com/esper/release-5.2.0/esper-reference/html/index.html)[Esper and the Event Processing Language](http://www.espertech.com/esper/release-5.2.0/esper-reference/html/index.html) (EPL) \[8\] and two solutions for real-time Big Data processing (spark \[9\] and flink \[10\]). Finally, it goes through the concepts illustrated in the first part of the course showing how semantic technologies can be extended to cope with the streaming nature of those data sources. It shows how to extend [](http://streamreasoning.org/)[RDF to model RDF streams, how to extend SPARQL to continuously process RDF streams and how to reason on those RDF Streams](http://streamreasoning.org/) \[11\]. Last, but not least, it illustrates with [](http://jol.telecomitalia.com/jolskil/tag/city-sensing/)[CitySensing](http://jol.telecomitalia.com/jolskil/tag/city-sensing/) \[12\] how to use all those ingredients together to fuse city data streams from multiple sensor and social sources.

#### Exam

The exam consist in a practical part (40% of the grade) and a theoretical part (60% of the grade) \[[tmp dropbox link](https://www.dropbox.com/s/53su85irfukjqk8/IST16-22_exam-preview.ppt?dl%3D0)\]

##### Theoretical part

The theoretical part will be evaluated with a written and (optionally) an oral test. The written test is composed of questions to be answered in free text, regarding any of the course subjects, and excercises, regarding the more technical content. The oral test consists of a discussion about the written test and the practical part of the exam. It can include also questions on any subject of the course.

##### Practical part

The practical part consist in solving a realistic interoperability problem. The students will be given real heterogeneous datasets (i.e., those released open by the [](https://dandelion.eu/datamine/open-big-data/)[Telecom Italia Big Data Challenge 2014](https://dandelion.eu/datamine/open-big-data/) \[13\] and others of their choice), they will have to define a continuous information need and use the technologies illustrated in the course (see hereafter) to satisfy such a need executing queries that span the datasets.

###### How to open your project

Before starting the project you should make sure that it is approved.

To do so, please,

1.  use the following form to propose your information need and name the components of your group: [](http://bit.ly/IST-FORM)[http://bit.ly/IST-FORM](http://bit.ly/IST-FORM)
2.  Notify the submission to riccardo -dot – tommasini @ polimi -dot- it
3.  wait for his comments
4.  interact with him until you get the project approved

###### How to submit your project for the exam

7 days before the exam you have to submit your project work using [](https://docs.google.com/forms/d/1bfybE57KRxq2l0ZJq0M2ccjmMjKGhVgjVvQw-kXi96w/edit?usp%3Ddrive_web)[this form](https://docs.google.com/forms/d/1bfybE57KRxq2l0ZJq0M2ccjmMjKGhVgjVvQw-kXi96w/edit?usp%3Ddrive_web). After the submission each member of the group has to provide feedbacks using [](https://docs.google.com/forms/d/1JeFVMy44V-rua3AOlnPOSRaQSMC3bWDNKP_DJ3joD6U/edit?usp%3Dsharing)[the other form](https://docs.google.com/forms/d/1JeFVMy44V-rua3AOlnPOSRaQSMC3bWDNKP_DJ3joD6U/edit?usp%3Dsharing). The feedback provided is not part of the evaluation, but it is required to obtain the final grade.

###### Tools to use

-   a database to store the data (students’ choice)
-   [protege Desktop v5](http://protege.stanford.edu/products.php) to model/extend an ontology
-   ontop protege plug-in 1.18 to model mappings and issues SPARQL queries to the database where the data are stored
-   [Triplewave](https://github.com/streamreasoning/TripleWave) to create RDF streams
-   [RSP-services for C-SPARQL 0.5](https://github.com/streamreasoning/rsp-services-csparql) to register C-SPARQL queries and oberve their results

###### Optional tools

-   [Frappe-Lite ontology](http://streamreasoning.org/ontologies/frappe-lite.rdf)
-   [ontop 1.18 stand alone](https://github.com/ontop/ontop/wiki/ObdalibSPARQLendpoint)

###### Frequently Asked Questions

Q: shall I use all the data ?  
A: no, I can use subsets of the data, especially during the design and testing phase.

Q: do I have to reuse an existing ontology?  
A: no, but I appreciate if you do (e.g., FraPPE-Lite or SIOC)

Q: shall I model a comprehensive ontology for the data I choose?  
A: no, you can model in the ontology just the terms you need to satisfy the information need you choose.

Q: shall I build mappings for every single data item in the data source or term in the ontology?  
A: no you can build just the mappings you need to satisfy the information need you choose.

Q: some data sources are accessible using APIs, shall I integrate the APIs?  
A: no, you can just download some data and treat them as a file

Q: some data are in JSON, what shall I do?  
A: you may want to cover them in CSV or TSV e.g., using a command line tool as [](https://github.com/zemirco/json2csv%23command-line-interface)[json2csv](https://github.com/zemirco/json2csv%23command-line-interface)

Q: I have latitude and longitude of a geo-point, how can I obtain the ID of the cell of the grid?  
A: you can use the following code

```
<span>minLat=45.356686</span>
<span>minLon=9.011491</span>
<span>cellHeight=0.00211101</span>
<span>cellWidth=0.00301197</span>
<span>verticalIndex = (int)((lat - minLat) / cellHeight);</span>
<span>horizontalIndex = (int)((lon - minLon) / cellWidth);</span>
<span>cell_ID = (int)(((verticalIndex * 100) + horizontalIndex) + 1);</span>
```

#### Lectures

Hereafter, you find the tentative calendar of the course. The material presented in class will be linked here and posted on twitter on [](https://twitter.com/manudellavalle)[@manudellavalle](https://twitter.com/manudellavalle).

-   7.3.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Introduction \[[slideshare](http://www.slideshare.net/emanueledellavalle/ist1601-introduction-to-interoperability-and-semantic-technologies)\]
-   14.3.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – HL7 from syntax (v2.x) to semantics (v3.x) \[[slideshare](http://www.slideshare.net/emanueledellavalle/ist16-02-ahl7fromv2syntaxtov3semantics)\], the Reference Information Model (RIM) \[[pdf](http://emanueledellavalle.org/slides/IST16-02_b_HL7-RIM.pdf) (to study), [](http://www.slideshare.net/AShakir/hl7-v3-reference-models-20091123)[slideshare](http://www.slideshare.net/AShakir/hl7-v3-reference-models-20091123) (original extended version)\] and the Clinical Document Architecture (CDA) \[[pdf](http://emanueledellavalle.org/slides/IST16-02_c_HL7-RIM-and-CDA.pdf) (to study), [](http://www.slideshare.net/nzhug/fundamentals-of-hl7-cda-implementing-hl7-cda)[slideshare](http://www.slideshare.net/nzhug/fundamentals-of-hl7-cda-implementing-hl7-cda) (original extended version)\] ascases of semantic interoperability
-   21.3.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Semantic Web technologies \[[slideshare](http://www.slideshare.net/emanueledellavalle/ist1603-an-introduction-to-the-semantic-web)\]
-   23.3.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – RDF \[[slideshare](http://www.slideshare.net/emanueledellavalle/ist1604-an-introduction-to-rdf)\] and solution of the exercise proposed in class \[[whiteboard](http://emanueledellavalle.org/slides/IST16-04_b_RDF-exercize-solutions.JPG),[txt](http://emanueledellavalle.org/slides/IST16-04_c_RDF-exercize-solutions.txt)\]
-   30.3.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – OWL \[[tmp dropbox link](https://www.dropbox.com/s/8zpivep4gl453zh/IST16-05_a_RDFS-OWL.ppt?dl%3D0)\] and Protégé \[[link](http://protege.stanford.edu/products.php%23desktop-protege) \] practice session \[[tmp dropbox link](https://www.dropbox.com/s/08j84zp2mt6bf7a/IST16-05_b_RDFS-OWL-practice.ppt?dl%3D0)\]
-   4.4.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – SPARQL basics \[[tmp dropbox link](https://www.dropbox.com/s/llfjz133eb7eoy9/IST16-07_sparql-101.ppt?dl%3D0)\]
-   11.4.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – SPARQL in class exercise solutions \[[tmp dropbox link](https://www.dropbox.com/s/75u145zz8xxwsrc/IST16-07-SPARQL-solutions-to-inclass-exercises.txt?dl%3D0)\]
-   20.4.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Semantic annotation of HTML pages and Schema.org \[[tmp dropbox link](https://www.dropbox.com/s/5141ap242tbsl7p/IST16-08_annotations.ppt?dl%3D0)\]
-   27.4.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – R2RML \[[tmp dropbox link](https://www.dropbox.com/s/77zxsb4appngdg1/IST16-09_R2RML.ppt?dl%3D0)\]
-   2.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Putting it all together (please download and install [](http://protege.stanford.edu/products.php%23desktop-protege)[protege 5.0](http://protege.stanford.edu/products.php%23desktop-protege) beta and [](http://h2database.com/html/download.html)[H2](http://h2database.com/html/download.html)) \[[tmp dropbox link](https://www.dropbox.com/s/zfrh5l744zir0ts/IST2016_10_putting-it-all-together.ppt?dl%3D0)\]
-   4.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – finishing the lesson on putting it all together and Q/A
-   9.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – It’s a streaming world \[[tmp dropbox link](https://www.dropbox.com/s/jnx1dw7j1xfp9bf/IST16-11_a_it-a-streaming-world.pptx?dl%3D0)\] Stream and Complex Event Processing \[[tmp dropbox link](https://www.dropbox.com/s/s38lqz0jef779lu/IST16-11_Taming-velocity.pptx?dl%3D0)\]
-   11.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Event Processing Language \[[tmp dropbox link](https://www.dropbox.com/s/c6qfm512me55jro/IST16-12_a_Walk-through-esper.pptx?dl%3D0)\]
-   16.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Real-time Big Data \[[map-reduce explained visually](https://twitter.com/manudellavalle/status/691628048010104832)\] with Spark and its applications \[[slideshare](http://www.slideshare.net/pacoid/spark-streaming-case-studies) (slides 1-35 only), [](https://databricks-training.s3.amazonaws.com/slides/Spark%2520Summit%25202014%2520-%2520Spark%2520Streaming.pdf)[pdf](https://databricks-training.s3.amazonaws.com/slides/Spark%2520Summit%25202014%2520-%2520Spark%2520Streaming.pdf) (slides 12-22), [](https://databricks-training.s3.amazonaws.com/realtime-processing-with-spark-streaming.html)[example application using Twitter](https://databricks-training.s3.amazonaws.com/realtime-processing-with-spark-streaming.html), [](https://www.dropbox.com/s/4winyooiwopwjkl/spark-summit-usb-stick.zip?dl%3D0)[usb stick with the code (2.2GB)](https://www.dropbox.com/s/4winyooiwopwjkl/spark-summit-usb-stick.zip?dl%3D0), [](https://databricks-training.s3.amazonaws.com/training-downloads.zip)[tutorial material](https://databricks-training.s3.amazonaws.com/training-downloads.zip) \]
-   23.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Real-time Big Data with Flink and its applications \[[tmp dropbox link](https://www.dropbox.com/s/d51q5th2dndtfb5/IST16-14_flink.pdf?dl%3D0), [](https://github.com/riccardotommasini/flink-exercises)[code examples](https://github.com/riccardotommasini/flink-exercises)\]
-   25.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Taming Velocity and variety simultaneously with Stream Reasoning \[[tmp dropbox link](https://www.dropbox.com/s/0ou328mu3ok8ahn/IST16-15_Stream-Reasoning_.pptx?dl%3D0)\]
-   30.5.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – City Sensing use case \[[BIS keynote on slideshare](http://www.slideshare.net/emanueledellavalle/listening-to-the-pulse-of-our-cities-fusing-social-media-streams-and-call-data-records)\]
-   6.6.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – RDF Stream Processing practice: C-SPARQL \[[tmp dropbox link](https://www.dropbox.com/s/omf4p80wne60e8l/IST16-16_a_C-SPARQL.pptx?dl%3D0)\], Triplewave and RSP services \[[tmp dropbox link](https://www.dropbox.com/s/n225h5xt8rq5oc0/IST16-16_b_Triplewave%252BRSP%2520Services.pptx?dl%3D0)\], setup guide \[[tmp dropbox link](https://www.dropbox.com/s/0g362camgpwah42/IST2016_16_d_SystemSetup-StepByStep.pdf?dl%3D0)\]
-   8.6.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – Exam preview and project work presentation \[[tmp dropbox link](https://www.dropbox.com/s/53su85irfukjqk8/IST16-22_exam-preview.ppt?dl%3D0)\] overview on Semantic Web techs \[[tmp dropbox link](https://www.dropbox.com/s/cegjsxo54180e80/IST16-16_c_An-Overview-on-SWT.pptx?dl%3D0)\]
-   13-15-20-22.6.2016 – [](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT)[V.S8-B](https://aunicalogin.polimi.it/aunicalogin/getservizio.xml?id_servizio%3D343%26idaula%3D4730%26lang%3DIT) – 8 hours of supported project work

Please check here the dates before coming to the lecture room. Any change will be communicated using the maling/SMS system of PoliMI. Please, make sure your email/phone is present.

#### References

\[1\] h[ttp://www.hl7.org/implement/standards/product\_brief.cfm?product\_id=77](http://www.hl7.org/implement/standards/product_brief.cfm?product_id%3D77)  
\[2\] [](http://www.hl7.org/implement/standards/product_brief.cfm?product_id%3D7)[http://www.hl7.org/implement/standards/product\_brief.cfm?product\_id=7](http://www.hl7.org/implement/standards/product_brief.cfm?product_id%3D7)  
\[3\] [](http://www.w3.org/RDF/)[http://www.w3.org/RDF/](http://www.w3.org/RDF/)  
\[4\] [](http://www.w3.org/TR/owl-overview/)[http://www.w3.org/TR/owl-overview/](http://www.w3.org/TR/owl-overview/)  
\[5\] [](http://www.w3.org/TR/sparql11-overview/)[http://www.w3.org/TR/sparql11-overview/](http://www.w3.org/TR/sparql11-overview/)  
\[6\] [](https://en.wikipedia.org/wiki/Ontology-based_data_integration)[https://en.wikipedia.org/wiki/Ontology-based\_data\_integration](https://en.wikipedia.org/wiki/Ontology-based_data_integration)  
\[7\] [](https://www.r-project.org/)[https://www.r-project.org/](https://www.r-project.org/)  
\[8\] [](http://www.espertech.com/esper/release-5.2.0/esper-reference/html/index.html)[http://www.espertech.com/esper/release-5.2.0/esper-reference/html/index.html](http://www.espertech.com/esper/release-5.2.0/esper-reference/html/index.html)  
\[9\] [](http://spark.apache.org/streaming/)[http://spark.apache.org/streaming/](http://spark.apache.org/streaming/)  
\[10\] [](https://flink.apache.org/)[https://flink.apache.org/](https://flink.apache.org/)  
\[11\] [](http://streamreasoning.org/)[http://streamreasoning.org/](http://streamreasoning.org/)  
\[12\] [](http://jol.telecomitalia.com/jolskil/tag/city-sensing/)[http://jol.telecomitalia.com/jolskil/tag/city-sensing/](http://jol.telecomitalia.com/jolskil/tag/city-sensing/)  
\[13\] [](https://dandelion.eu/datamine/open-big-data/)[https://dandelion.eu/datamine/open-big-data/](https://dandelion.eu/datamine/open-big-data/)