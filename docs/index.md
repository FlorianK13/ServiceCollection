# NFDI4Energy Service Definition
This site collects data services that are relevant in the energy domain. We distinguish between services that are developed within the [NFDI4Energy project](NFDI4Energy Services/best_practices.md) and services that come from [other stakeholders](Other Services/enargus.md). 

## Categorization of Services

### Categorization based on the `Data Life Cycle`

Data Services are tools that help researchers in one or multiple steps of the Research Data Management Life Cycle. Hence, services can get one or multiple of the tags [planning](categories.md#dlcplanning), [production](categories.md#dlcproduction), [analysis](categories.md#dlcanalysis), [storage](categories.md#dlcstorage), [access](categories.md#dlcaccess), and [re-use](categories.md#dlcre-use).

<figure markdown="span">
  ![Image](assets/nfdi4energy_datalifecycle.png){width="50%" }
  <figcaption>Research Data Management Life Cycle.</figcaption>
</figure>


### Categorization based on the DFG Definitions
These categories are relevant for the DFG reporting. They can be accessed from the nfdi1000 Excel sheet [here](https://www.dfg.de/de/foerderung/foerderinitiativen/nfdi/formulare-merkblaetter) and the [Guide](https://www.dfg.de/en/research-funding/funding-initiative/nfdi/guide-to-filling-out-the-supplementary-data-sheet-for-consortia-of-the-national-research-data-infrastructure-nfdi-)

First, Categories are defined based on the [de.NBI](https://zenodo.org/records/6597826) definitions (see Drop Down Categories from the reporting excel sheet, Tab 5)

| Category             | Definition                                                                                                                                                 |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Database             | software providing large amounts of structured data to the user. Usually the data can be uploaded, accessed, searched and/or downloaded via a web browser. |
| Library / API        | collection of pre‐implemented functions for a specific task that can be accessed via a well‐ defined interfaces.                                           |
| Workflow             | software that combines multiple tools / applications. They may be used locally or remotely via the internet.                                               |
| Tools / applications | software that can be downloaded and executed locally on the users' hardware.                                                                               |
| Web applications     | software that is installed on a server and can be used by users via a web page and the internet.                                                           |
| Storage              | Not defined by de.NBI                                                                                                                                      |
| Data Curation        | Not defined by de.NBI                                                                                                                                      |

de.NBI additionally defines `Support / consulting` as "service with direct user contact for topics going beyond the support for the other services".

### Categorization based on the DFG Service Descriptions
Source: Service Overview from the Excel, Tab 2-4
In which stage is the software - exactly one of

* Development
* Prototype
* Operation
* Terminated

Is the software open-source? If yes, add the tag

* open-source



### Categorization based on the NFDI4Energy proposal
In the NFDI4Energy [proposal](https://zenodo.org/records/6772013), a Research & Tranfser Cycle is defined. It introduces the following categories:

<figure markdown="span">
  ![Image](assets/nfdi4energy_Abbildung_aussen.png){width="50%" }
  <figcaption>Research & Transfer Cycle from the NFDI4Energy proposal.</figcaption>
</figure>

Based on this Research & Tranfser Cycle, **Core Services** are defined:

| Category       | Definition                                                                                                                                                           |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Competence     | help to navigate the interdisciplinary research field                                                                                                                |
| Best Practices | get information on successful conduct of research in the field of energy systems and their research data management                                                  |
| Registry       | find suitable data sets and software modules                                                                                                                         |
| Simulation     | couple existing simulations and, therefore, increase the reuse of software artefacts                                                                                 |
| Transparency   | involve more stakeholders in all research stages, especially integrating their data, and to convey the appropriate key research results to all relevant stakeholders |