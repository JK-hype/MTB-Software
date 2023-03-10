# MTB-Software
This software supports the Molecular Tumour Board at the Universit√§tsklinikum Eppdendorf (UKE).

It functions is mainly to ease the workload for the physicians at the UKE, improve effectiveness and patient safety and provide a further to step to a more digitalised healthcare system.

The software integrates the <a href="https://github.com/AG-Boerries/MIRACUM-Pipe-docker">MIRACUM-Pipeline</a> developed at the Uniklinik Freiburg and the <a href="https://www.dkfz.de/de/clinical-trial-office/knowledgeconnector.html">Knowledge Connector</a> (KC) developed at the DKFZ at the Universit√§tsklinikum Heidelberg.
For this, it sends the output of the MIRACUM-Pipeline (MAF-file) to the KC. Further, it can receive Emails containing the input of the MIRACUM-Pipeline (FASTQ-files).

The MTB-Software is build according to the Microservice Architecture. The code of the Microservices are in the following repositories:
<ul>
<li><a href="https://github.com/JK-hype/de.uke.iam.mtb.miracumapi">API of MIRACUM</a></li>
<li><a href="https://github.com/JK-hype/de.uke.iam.mtb.kcapi.git">API of KC</a></li>
<li><a href="https://github.com/JK-hype/de.uke.iam.mtb.emailapi">API to receive emails</a></li>
<li><a href="https://github.com/JK-hype/de.uke.iam.mtb.mafmapper">API to map MAF file</a></li>
<li><a href="https://github.com/JK-hype/de.uke.iam.mtb.idgenerator">API to generate ID</a></li>
<li><a href="https://github.com/JK-hype/de.uke.iam.mtb.dto/tree/develop">DTO library</a></li>
</ul>

The Microservices communicate via REST.

The MTB-Software was topic of a <a href="https://jankramer.me/index.php/s/E7BRSiffR5GSgtJ">Master Thesis</a>.
