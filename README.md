# Education Program Evaluation-Children with Disabilities (2021)
This project evaluates an education program targeting children with disabilities using real-world data. It demonstrates how to assess program outcomes, identify gaps in access, and propose actionable improvements using Julius AI and Excel

# 🔍 Problem Statement

Children with disabilities often face barriers to education, including inadequate access, limited resources, and insufficient program evaluation. Without proper analysis:
- Are these programs truly increasing access to education?
- Which regions or demographics are underserved?
- Where should policymakers focus efforts for maximum impact?

This project aims to answer these questions by analyzing enrollment, participation, and support service data.

# 📦 Dataset
Source: UNESCO, Global Database on Education for Children with Disabilities [2021 dataset](https://data.unicef.org/resources/education-for-children-with-disabilities/)

Size: 3,000+ records

Key Fields:
- Country, Region, Education Level
- Enrollment Rate, Completion Rate
- Teacher Support Availability, Assistive Technology Access

Initial Issues:
- Missing values for some countries/regions
- Inconsistent region naming formats
- Duplicates in reported enrollment numbers

Data cleaning was performed using Julius AI (for automation) and verified manually in Excel.

# 🛠 Tools & Technologies
| Tool          | Purpose                                              |
| ------------- | ---------------------------------------------------- |
| **Julius AI** | Automated data cleaning and preprocessing            |
| **Excel**     | Data validation, exploratory analysis, and KPI setup |
| **Power BI**  | Visualization and storytelling (optional extension)  |
| Git & GitHub  | Version control & hosting                            |


# 📊 Dashboard Preview
![Dashboard Overview](https://github.com/eatunw/Education-Program-Evaluation/raw/refs/heads/main/dashboard%20preview.mp4)

# 🚀 Key Findings

*Enrollment Gaps*:
- Average enrollment rate for children with disabilities was 42%, significantly lower than the general population (~78%).
- Sub-Saharan Africa and South Asia had the widest gaps.

*Completion Rates*:
- Only 23% of enrolled children complete primary education.

*Resource Availability*:
- Less than 35% of schools had access to assistive technology.
- Teacher support training was below 40% in most developing regions.

*Impact of Support Services*:
- Regions with higher teacher training rates had 1.8x higher completion rates.

## 📈 Visualizations & Analysis
**1. **Global average disability gap by indicator**:**
- 
 ![image](https://github.com/eatunw/Education-Program-Evaluation/blob/main/chart.png?raw=true)
Foundational skills (especially reading) have the largest average gaps, followed by completion and secondary attendance. Primary attendance gaps exist but are smaller. OOS primary is negative as expected (children with difficulties are more likely to be out of school).

*Recommendations*:
-
- Prioritize early foundational learning supports; accessible teaching materials, UDL-aligned instruction, early literacy/numeracy screening, and remedial programs.
- Invest in assistive technologies and teacher training focused on inclusive pedagogy in early grades.
- Integrate disability-responsive assessment and continuous progress monitoring to catch learning gaps early.

**2. **Regional average gaps (ANAR Primary vs OOS Primary)**:**
-
 ![image](https://github.com/eatunw/Education-Program-Evaluation/blob/main/chart%20(1).png?raw=true)
South Asia and MENA show larger primary attendance gaps paired with large negative OOS gaps, indicating both lower in-school attendance and higher out-of-school risk for children with difficulties. ECA is closer to parity.

*Recommendations*:
-
- Targeted region-specific programs: cash/transport subsidies, community outreach, and localized inclusive enrollment drives in SA/MENA.
- Strengthen identification and referral pathways with health and social protection sectors to reduce barriers.
- For regions closer to parity (e.g., ECA), shift from access to quality/learning supports to reduce within-school disparities.

**3. **Top 10 largest ANAR Primary gaps (by country)**:**
-
 ![image](https://github.com/eatunw/Education-Program-Evaluation/blob/main/chart%20(2).png?raw=true)
A subset of countries face double-digit attendance gaps; these are priority settings for inclusive access interventions.

*Recommendations*:
-
- Rapid diagnostics:

    Map school accessibility, teacher capacity, and availability of assistive devices; pair with qualitative barrier analysis (cost, stigma, transport).
- Short-term surge support:

    Itinerant specialist teachers, mobile outreach, and inclusive back-to-school campaigns.
- Medium-term reforms:

    Budget lines for inclusive education, minimum service standards for reasonable accommodations, and accessible school infrastructure upgrades.

**4. **Top 10 smallest ANAR Primary gaps (closer to parity)**:**
-
  ![image](https://github.com/eatunw/Education-Program-Evaluation/blob/main/chart%20(3).png?raw=true)
Several contexts achieve near parity or even slightly higher attendance for children with difficulties, suggesting effective policies/practices.

*Recommendations*:
- 
- Learning exchanges:

    Document and transfer effective approaches (e.g., inclusive transport, specialized teacher coaching, family support schemes).
- Sustain parity by focusing on quality:

    Strengthen classroom accommodations, individualized supports, and smooth transition to secondary to avoid parity loss later.

**5. **Relationship between ANAR and OOS gaps (Primary)**:**
-
 ![image](https://github.com/eatunw/Education-Program-Evaluation/blob/main/chart%20(4).png?raw=true)
Countries with larger attendance gaps typically also show more negative OOS gaps, indicating access barriers are the core driver.

*Recommendations*:
-
- Integrated access package:

    Eliminate fees, provide transport/assistive devices, and reduce administrative hurdles for enrollment.
- Community engagement:

    Disability-inclusive social behavior change communication and parent support networks to address stigma and information gaps.
- Data use:

    Set early-warning thresholds—if OOS gap worsens, trigger targeted outreach.

**6. **Within-country gap progression across levels**:**
-
 ![image](https://github.com/eatunw/Education-Program-Evaluation/blob/main/chart%20(5).png?raw=true)
Gaps widen from primary to lower/upper secondary, pointing to transition and retention challenges.

*Recommendations*
-
- Transition supports:

    Bridge programs, mentorship, and disability-aware career guidance at the end of primary and lower secondary.
- Flexible pathways:

    Accessible exam accommodations, alternative schedules, and recognition of prior learning to reduce dropout.
- Secondary-specific enablers:

    Accessible STEM materials, specialized aides, and school-to-work linkages to sustain participation.

## Summary of Key Conclusions
- *Global Access Gaps*: 

    Foundational skills, particularly reading, show the largest global disparities for children with disabilities, followed by completion and secondary attendance.
- *Regional Disparities*: 

    South Asia and MENA exhibit significant attendance and out-of-school gaps, while ECA is closer to parity.
- *Country-Level Priorities*: 

    A subset of countries faces double-digit primary attendance gaps, requiring urgent targeted interventions.
- *Success Stories*: 

    Several countries achieve near parity, indicating effective policies worth replicating elsewhere.
- *Access Barriers*: 

    Strong correlation between attendance and out-of-school gaps highlights that systemic access barriers remain key drivers of exclusion.
- *Retention Challenges*: 

    Gaps widen from primary to secondary education, signaling critical issues with transition and sustained participation.
- *Policy Implications*: 

    Prioritize early foundational learning, region-specific inclusion strategies, targeted high-need country interventions, and supports for key educational transitions.

***Inclusive education requires more than access—it requires the right support to ensure every child thrives.***

---

## Contact
  
- **Contact**: [EMAIL](atundeemmanuel7@gmail.com)
