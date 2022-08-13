# Harmonising electronic health record data for reproducible research: challenges and lessons learnt in a UK-wide COVID-19 research collaboration

## Project description

The COVID-19 pandemic has highlighted the need to implement efficient approaches that enable multi-nation analytics across different Trusted Research Environments (TREs) to support public health decision-making. TREs may differ in data access, sharing policies and governance, creating a challenge for projects wishing to combine data at the individual-level. One solution to this challenge is federated analytics, whereby the data from multiple TREs remains at its source and is harmonised to a common data model that allows results from multiple locations to be combined using meta-analysis technique. This harmonisation can occur via a rules-based approach with common, agreed analytic protocols applied within the separate TREs.
Harmonisation for electronic health records (EHRs) poses several technical challenges as healthcare data generally differ by underlying healthcare systems, type of information collected, drug/vaccine and medical event coding systems and language. Furthermore, different data sources have different data structures, fields, validation procedures, and accuracy issues. We addressed these challenges in the reproducible method developed for harmonising data from Wales (held within the SAIL Databank) with data from England (held within the NHS Digital TRE), a part of the CVD-COVID-UK programme.
We used linked, anonymised individual-level EHR, demographic and administrative data held within the SAIL Databank for the population of Wales. The harmonisation method was implemented as a four-layer reproducible process, starting from raw data in the first layer. Then each of the layers two to four is framed by, but not limited to, the characterised challenges and lessons learnt. We achieved curated data as part of our second layer, followed by extracting phenotyped data in the third layer. We captured any project-specific requirements in our fourth layer.
We retrieved approximately 100 health and demographic related variables for the population of Wales, and harmonised them with corresponding data for England. We fed 13 data sources into the first layer of our harmonisation method: five of these are updated daily or weekly, and the rest at various frequencies providing sufficient data flow updates for frequent capturing of up-to-date demographic, administrative and clinical information.
With a current focus on COVID-19 and its relationship with cardiovascular outcomes, the harmonised data has supported a wide range of research activities across the UK, and the method can be scaled up and expanded to serve many more projects in the future.

## How to cite this work
> Citation goes here

## Contents

* [View the analysis code and phenotypes used in NHS Digital's TRE for England](https://github.com/BHFDSC/CCU005_03/tree/main/england)
* [View the analysis code and phenotypes used in the SAIL Databank](https://github.com/BHFDSC/CCU005_03/tree/main/wales)
* [View the code used outside of the environments to prepare tables and figures for publication](https://github.com/BHFDSC/CCU005_03/tree/main/outside)
* [View the final ouput of our analysis](https://github.com/BHFDSC/CCU005_03/tree/main/outside/output)

## Project approval

This is a sub-project of [project CCU005](https://github.com/BHFDSC/CCU005) approved by the CVD-COVID-UK / COVID-IMPACT Approvals & Oversight Board (sub-project: CCU005_03).

## License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this software except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0. Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
