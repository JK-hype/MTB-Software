# MTB-Software
This software supports the Molecular Tumour Board at the Universitätsklinikum Eppdendorf (UKE).

It functions is mainly to ease the workload for the phyiscians the UKE, improve effectiveness and patient safety and provide a further to step to a more digitiliased healthcare system.

The software integrates the <a href="https://github.com/AG-Boerries/MIRACUM-Pipe-docker">MIRACUM-Pipeline</a> developed at the Uniklinik Freiburg and the <a href="https://www.dkfz.de/de/clinical-trial-office/knowledgeconnector.html">Knowledge Connector</a> (KC) developed at the DKFZ at the Universitätsklinikum Heidelberg.
For this, it sends the output of the MIRACUM-Pipeline (maf-file) to the KC. Further, it can receive Emails containg the input of the MIRACUM-Pipeline (FASTQ-files).

The MTB-Software is build according to the Microservice Architecture. The code of the Microservice are in the following repositories:

The MTB-Software was topic of a Master Thesis ()
