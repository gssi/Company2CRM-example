# Company2CRM-example
This repository contains an ATL Project called Company2CRM transforming models conform to the Company metamodel into models conform to the CRM metamodel by means of the [Company2CRM.atl](https://github.com/gssi/Company2CRM-example/blob/master/Company2CRM.atl) transformation.
## This reposity is composed as follows:
- The *Company2CRM* transformation
- A folder *metamodels* containing the Company (left) and CRM (right) metamodels
<p align="center">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/metamodels/CompanyMM.png" alt="alt text" width="300px">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/metamodels/crmMM.png" alt="alt text" width="300px">
</p>
- A folder <i>models</i> contaning the *CompanyModel.xmi* (left) for running the transformation and the obtained *crm.xmi* (right)
<p align="center">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/models/companyModel.png" alt="alt text" width="400px">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/models/crm-xmi.png" alt="alt text" width="400px"></p>
- Each folder also includes an *evo* folder: this folder contains the evolved version of the artifacts.
    
    - For example the *evo* in the root of the repo contains the evolved transformation , 
    - The *evo* in the metamodel folder contains the evolved company metamodel (left), 
    - and the *evo* in the models folder contains the evolved Company model (right) with a relative diagrammatic representation *evoCompanyModel.png* to inspect the evolved model without installing the complete bundle.

<p align="center">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/metamodels/evo/company2MM.png" alt="alt text" width="400px">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/models/evo/evoCompanyModel.png" alt="alt text" width="400px"></p>
