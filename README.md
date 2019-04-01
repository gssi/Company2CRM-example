<style>
figure figcaption {
    border: 1px dotted blue;
    text-align: center;
}
</style>
# Company2CRM-example
This repository contains an ATL Project called Company2CRM transforming models conform to the Company metamodel into models conform to the CRM metamodel.
## This reposity is composed as follows:
- The *Company2CRM* transformation
- A folder *metamodels* containing the Company and CRM metamodels

<img src="https://github.com/gssi/Company2CRM-example/blob/master/metamodels/CompanyMM.png" alt="alt text" width="400px"><figcaption>Company metamodel</figcaption><br>
<img src="https://github.com/gssi/Company2CRM-example/blob/master/metamodels/crmMM.png" alt="alt text" width="400px"><figcaption>CRM metamodel</figcaption>
<br>
- A folder *models* contaning the *CompanyModel.xmi* for running the transformation and the obtained *crm.xmi*
<div class="row"><div class="column">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/models/companyModel.png" alt="alt text" width="400px"></div><div class="column">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/models/crm-xmi.png" alt="alt text" width="400px"></div></div>
- Each folder also includes an *evo* folder: this folder contains the evolved version of the artifacts.
  - For example the *evo* in the root of the repo contains the evolved transformation , 
  - The *evo* in the metamodel folder contains the evolved company metamodel, 
  - and the *evo* in the models folder contains the evolved Company model with a relative diagrammatic representation *evoCompanyModel.png* to inspect the evolved model without installing the complete bundle.
 <div class="row"><div class="column">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/metamodels/evo/company2MM.png" alt="alt text" width="400px"></div><div class="column">
<img src="https://github.com/gssi/Company2CRM-example/blob/master/models/evo/evoCompanyModel.png" alt="alt text" width="400px"></div></div>

