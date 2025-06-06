---
title: Clinical Data Uses
---



# Clinical Data Uses

## Learning Objectives

## General uses of clinical data

### Cancer Prevention and Care

The near universal adoption of electronic health record (EHR) systems in the US has created unprecedented opportunities to improve cancer prevention and care. As described in previous chapters, EHR systems store comprehensive longitudinal records of a patient's interactions with a healthcare system, including data about demographics, conditions, family history, clinical notes, laboratory test results, medications, procedures, imaging, and genetic test reports. These data can be accessed not only by health professionals, but also by patients through patient portals. EHR data can also be used to enable data-driven interventions such as provider- and patient-facing clinical decision support (CDS) and population health management (PHM).

CDS has been defined as tools that "provide clinicians, staff, patients, or other individuals with knowledge and person-specific information, intelligently filtered or presented at appropriate times, to enhance health and health care" [@Osheroff_2007]. Examples of widely adopted CDS tools with demonstrated effectiveness for cancer prevention, diagnosis, and care include

  * provider and patient reminders for cancer screening
  * decision aids and shared decision-making tools (e.g., for prostate cancer treatment, lung cancer screening)
  * AI-supported diagnostic imaging
  * chemotherapy decision support
  * at-home symptom care

While CDS tools generally provide decision support focused on a specific patient at a time, PHM are strategies that target specific patient populations [@Swarthout_Bishop_2017]. PHM efforts generally consist of

  * population algorithms that are applied over EHR and other data sources to identify individuals who are eligible for a specific healthcare intervention (e.g., colorectal cancer screening, tobacco cessation, HPV vaccination)
  * patient engagement strategies (e.g., patient portals, text messaging, chatbots, patient navigators) that provide education and access to those interventions
  * analytic tools that assess the effectiveness of the PHM program.

Several PHM programs have demonstrated to be effective in increasing the uptake of cancer prevention. For example, the colorectal cancer screening program at Kaiser Permanente uses digital (i.e., text messaging, patient portal), mailed, and patient navigation approaches to increase colorectal cancer screening by mailing Fecal Immunohistochemical Test (FIT) kits to patients' homes [@Gupta2020]. Also the Cancer Moonshot BRIDGE trial used the GARDE platform [@Bradshaw2022] (ITCR-funded) to identify candidates for genetic testing of hereditary cancer syndromes based on EHR data; and for patient outreach, pre- and post-test education via automated chatbots [@Kaphingst2024].

While some CDS and PHM approaches have been successfully adopted widely, emerging technologies such as the use of generative AI approaches to analyze diagnostic imaging, large language models (LLMs) to extract information from narrative texts (e.g., clinical notes), LLM-based chatbots to communicate with patients, and digital health tools such as home-based sensors are creating unprecedented opportunities for next generation CDS and PHM. These approaches have the potential to enable significant breakthroughs through the implementation of patient-tailored cancer prevention and care at a population scale. Nevertheless, substantial research is needed to ensure effective, fair, and equitable implementation of these CDS and PHM interventions.

## Types of questions that can be asked with clinical data

### Risk Prediction

Risk prediction in clinical research involves using data to assess the likelihood of certain outcomes or events occurring in patients. This could include predicting the risk of developing a particular disease, experiencing a specific complication, or responding to a treatment.

Data used for risk prediction can come from various sources, including:

  * Clinical Data: This includes patient demographics, medical history, laboratory results, and imaging studies.
  * Genetic Data: Genetic information, such as DNA sequencing results, can provide valuable insights into an individual's susceptibility to certain diseases.
  * Environmental and Lifestyle Data: Factors such as diet, exercise habits, smoking status, and environmental exposures can influence disease risk and may be included in risk prediction models.
  * Biomarkers: Biological markers indicative of disease or physiological processes can be used as predictors in risk models [@Bodaghi_Fattahi_Ramazani_2023].

Once relevant data is collected, statistical and machine learning techniques can be applied to develop predictive models. These models aim to identify patterns and relationships within the data that are associated with the outcome of interest. Common techniques include logistic regression, decision trees, random forests, support vector machines, and neural networks.

After the model is trained on a dataset, it can be validated using independent datasets to assess its performance and generalizability. Once validated, the model can be used to predict risk in new patients based on their individual characteristics and data.

Clinical prediction rules are a subset of risk prediction models, specific to clinical research.

Examples of risk prediction models ...

Risk prediction models are important because ...

Overall, risk prediction in clinical research allows healthcare professionals to identify individuals at higher risk of certain outcomes, enabling targeted interventions, personalized treatments, and more efficient resource allocation.

### Cohort identification for research

Clinical data plays a crucial role in cohort identification for research purposes. Researchers typically use electronic health records (EHRs), medical databases, or registries to identify cohorts based on specific criteria such as age, gender, medical conditions, treatments, medications, and outcomes. Advanced data mining and natural language processing techniques can also be employed to extract relevant information from unstructured data sources like clinical notes. Once cohorts are identified, researchers can analyze the data to study disease progression, treatment effectiveness, and outcomes.

Cohort identification is important regardless of research study type, but to provide specific examples:

* Research Design: Identifying cohorts allows researchers to design studies with appropriate inclusion or exclusion criteria. By selecting specific groups of individuals with similar characteristics or exposures, researchers can investigate hypotheses effectively.
* Clinical Insights: Cohort studies enable researchers to observe the natural history of diseases, track outcomes over time, and assess the effectiveness of interventions or treatments. Understanding how different factors influence disease progression or treatment response can inform clinical decision-making and improve patient care.
* Epidemiological Studies: Cohort identification is crucial for epidemiological research to understand the incidence, prevalence, and risk factors associated with diseases. By following cohorts over time, researchers can identify trends, patterns, and associations that contribute to our understanding of disease causation and prevention.
* Precision Medicine: Identifying cohorts based on genetic profiles, biomarkers, or other specific characteristics allows researchers to tailor treatments and interventions to individual patients. This approach, known as precision medicine, aims to optimize therapeutic outcomes while minimizing adverse effects.
* Healthcare Policy and Planning: Cohort studies provide valuable data for informing healthcare policies, resource allocation, and public health strategies. By identifying high-risk populations or groups with specific healthcare needs, policymakers can develop targeted interventions to improve health outcomes and reduce disparities.

### Case report forms

### Clinical trials/studies

### Retrospective analysis

## Research Design Considerations

Researchers need to intentionally use methods earlier in the research process than data analysis to manage data biases associated with clinical data, especially EHR.

One of the most important challenges in using EHR data in cancer research is that, as in many other fields, healthcare data are plagued with several types of biases that result from disparities in the delivery of healthcare. Overall, cancer research has historically relied on data from high resource academic medical centers, which disproportionately provide care to patients who are White, have high socioeconomic status, and live in urban areas. As a result, medical knowledge produced from these data have disproportionately benefited those patients. Different sources of bias are prevalent in EHR data. For example,

* *Information representativeness bias* occurs when certain groups are disproportionately less present in the EHR because they have no contact with the healthcare system.
* *Information presence bias*, on the other hand, occurs when certain groups may be represented in the EHR, but have disproportionately less comprehensive healthcare data due to issues such as overall lower access to and use of healthcare service, lack of a primary care provider, lack of access to specialty care, and lack of access to digital resources (e.g., patient portals, home sensors, telehealth) that can be used to provide healthcare data.
* *Treatment biases* happen when certain groups receive disproportionate access to more advanced treatments, which is often determined by social drivers such as insurance, distance, health literacy, and socioeconomic status.
* *Algorithm bias* further amplifies these previous sources of bias by leveraging biased EHR data to make predictions about diagnosis, treatment and prognosis that are used by clinicians to make potentially biased healthcare decisions, which are then documented in the EHR.

Recent advances in sophisticated and costly technology such as genetic testing, artificial intelligence, and digital health, which are disproportionately available in high resource healthcare systems further compound the problem. Therefore, cancer researchers increasingly need to use intentional methods to prevent, identify, and correct for biases in EHR data. For example, the National Institutes of Health Pragmatic Trials Collaboratory has made several recommendations to address EHR data biases in research [@BoydCCT2023; @BoydJAMIA2023]:

* Include data from low resource healthcare settings such as community health centers that provide care for patients who are racially diverse, have low socioeconomic status and live in rural areas.
* Engage with diverse communities in study design and conduct to ensure proper representation, data collection, analysis, and representation.
* Use data collection methods for self-reported data that rely on more accessible technology such as text messaging, using accessible and culturally adapted communication.
* Include subgroup analysis by different demographic groups according to variables such as socioeconomic status, race, ethnicity, sex, geographical location, and social determinants of health.

With such approaches, cancer researchers while aiming to avoid exacerbating health disparities, in addition help to reduce disparities.

## Conclusion
