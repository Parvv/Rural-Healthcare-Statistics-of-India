# Rural-Healthcare-Statistics-of-India
Amid the global crisis of COVID-19 and India being affected the most, questions are being raised regarding the current health infrastructure of the country. After months of lockdown and regulations, India still struggles to control the number of active cases. Since the second wave started to affect the rural areas, It made me wonder how was the healthcare infrastructure of the country before the crisis and what are the drastic measures government took in lieu of the pandemic. Though Urban cities have been the epicenter of this spread, there has been negligible to no update about the situation of rural India. It is hard to believe that rural India remained unaffected considering the loopholes and falling healthcare infrastructure in the cities themselves.

Inspired by the current scenario, This project aims to analyze different Healthcare facilities available to rural India in various States and Union Territories throughout different years. Emphasis is on the availability of resources for people living in villages or tribal areas, be it health centers or medicinal staff. Data of 2005 is used along with 2019 and 2020 to compare the facilities and growth trends.

You can check out the data above and [here](https://www.kaggle.com/vineethakkinapalli/rural-health-statistics-india2005-2019-2020)

It suggested using the data provided in the repo since I have made added more data.

Data has five sections: 
Rural Healthcare Statistics of 2005,
Statistics of 2019,
Statistics of 2020,
Rural Population Stats, and,
Rural Area Stats.

The data of all three years are divided by State, into subcategories described below:

- **State/UT** - Name of State/ Union Territory

- **Sub Center** - Most peripheral contact point between Primary Health Care System & Community

- **Primary Health Center** - A Referral Unit for 6 sub-centers 4-6 bedded manned with a Medical Officer Incharge and 14 subordinate paramedical staff.

- **Community Health Center** - A 30 bedded Hospital/Referral Unit for 4 PHCs with Specialized services

- **Auxiliary Midwife** - Auxiliary nurse-midwife, commonly known as ANM, is a village-level female health worker in India who is known as the first contact person between the community and the health services.

- **Doctors** - Number of Doctors in position

- **Specialists** - Surgeons, OB&GY, Physicians & Paediatricians

- **Radiographers** - A health professional who uses x-rays to produce radiographs of patients to help diagnose the patient's medical condition.

- **Pharmacists** - prepare and dispense prescriptions, ensure medicines and doses are correct, prevent harmful drug interactions, and counsel patients on the safe and appropriate use of their medications.

- **Lab Technician** - Medical Lab Technologist deals with performing complex tests for the detection, diagnosis, and treatment of diseases.

- **Nursing Staff** - a person trained to provide medical care for the sick or disabled, especially who is licensed and works in a hospital or physician's office.

For a broader understanding, I have divided this analysis into four sections, namely, Doctors, Healthcare and Nursing Staff, Primary Health Centers, and Secondary Healthcare Centers.

- Section "Doctors" includes the combined number of "Doctors" and "Specialists"

- Section "Healthcare and Nursing Staff" includes the combined number of "ANM/Health Worker Female" and "Nursing Staff"

- Section "Primary Health Center" includes the combined number of "Subcenters", "PHCs" and "CHCs"

- Section "Secondary Healthcare Center" includes the combined number of "Radiographers", "Pharmacists" and "Lab Technicians".

**NOTE:
In order to understand the gaps of the maps betters,following data is followed:

- Telangana came to existence in 2014 after bifurcation of Andhra Pradesh
- Jammu & Kashmir and Ladakh bifurcated and became UTs during Aug 2019.
- Dadra & Nagar Haveli and Daman Diu merged as single UT during Jan 2020.

## Doctors in Rural India

 This cader includes all the governmental doctors and specialists allocated to rural or tribal areas. They are the ones officially licensed for the detection, diagnosis, and treatment of diseases. Analysis tries to answer the following questions:


How many doctors are present concerning 1000 rural citizens?

Which states have the best and worst ratio between Rural Population and Doctors in a particular year?

What is the density of Doctors present in each kilometer square of Rural area in every state?

How have states been performing in the ratio and density through different years? Which states are performing better and which states have the serious matter of concern?

- Analyzing 2005 data gave the following results:
![1 BDocR05](https://user-images.githubusercontent.com/78965701/122639903-2d0b4400-d11a-11eb-95b8-11ed303594f9.jpg)
![2 WDocR05](https://user-images.githubusercontent.com/78965701/122640660-5af28780-d11e-11eb-9979-bf8e03f3a4a4.jpg)


In the case of Rural Population to Doctor Ratio, Uttar Pradesh had the worst ratio of having 1 Doctor in 187657 people while Puducherry performed best with 1 in 4724 people. WHO officially recommends 1 Doctor in 1000 people whereas even the best performing state/UT in India has four times the recommended rate.

- Analyzing 2019 data gave the following results:
![3 BDocR19](https://user-images.githubusercontent.com/78965701/122641807-2635fe80-d125-11eb-8838-853e57360876.jpg)
![4 WDocR19](https://user-images.githubusercontent.com/78965701/122641815-2fbf6680-d125-11eb-9e8e-c3700ff9136a.jpg)

In the case of Rural Population to Doctor Ratio, this time West Bengal had the worst ratio of having 1 Doctor in 71343 people while Lakshdeep performed best with 1 in 375 people. 
![5 BDocD19](https://user-images.githubusercontent.com/78965701/122641835-4fef2580-d125-11eb-8250-a540fc8e25a1.jpg)
![6 WDocD19](https://user-images.githubusercontent.com/78965701/122641838-57163380-d125-11eb-8ed5-440d162cdd75.jpg)

In the case of Doctor's density, Lakshadweep again performed the best while Arunachal Pradesh was the worst performer among all the states. By seeing the fact that comparatively small states with medium population density like Kerala are among the top performers shows density becomes secondary assessment tactics. Even in terms of density, other than Lakshadweep standing proud at 0.99, most states have a mere 0.02 to 0.01 density. This indicates there is barely 1 to 2 doctor in 100 km square of rural area in each state.

- Analyzing 2020 data gave the following results:
![7 BDocR20](https://user-images.githubusercontent.com/78965701/122641893-a8bebe00-d125-11eb-8d47-71623e799da2.jpg)
![8 WDocR20](https://user-images.githubusercontent.com/78965701/122641898-ae1c0880-d125-11eb-9b34-1fd780621ce8.jpg)

In the difference of single year when COVID struck, Jharkand performed worst with 1 to 70605 people while West Bengal improved from 71343 to 36143. West Bengal certainly has more than doubled the number of doctors in the situation. Again, Lakshadweep performed the best. Small states like Goa, Arunachal Pradesh, and Jammu Kashmir have also performed exceptionally well than the large population states.
![9 BDocD20](https://user-images.githubusercontent.com/78965701/122641910-c1c76f00-d125-11eb-9fa6-674f107fd344.jpg)
![10 WDocD20](https://user-images.githubusercontent.com/78965701/122641915-c724b980-d125-11eb-8821-cbadc837e3f6.jpg)

The result becomes unambiguous with the density, small to medium-sized states with less population performed better while large states with a medium population like Madhya Pradesh and Chhattisgarh performed comparatively low.

- The ratio of Rural Population to Doctor in different years can be seen below:

2005

![a](https://user-images.githubusercontent.com/78965701/122641941-e9b6d280-d125-11eb-8dfd-3cb1da067687.png)

2019

![b](https://user-images.githubusercontent.com/78965701/122641945-ee7b8680-d125-11eb-9aa7-a1ab107fc71b.png)

2020

![c](https://user-images.githubusercontent.com/78965701/122641948-f3d8d100-d125-11eb-8b86-c3a47cf37fa6.png)


Analyzing and comparing from different years and parameters, it seems fair to say India always had poor healthcare infrastructure even back in 2005. The population rose exponentially and the number of doctors is not close to being at par. Though it certainly improved from worst to worse, considering UP had 1 doctor among 187657 people in 2005 that toned down to 48896 people in 2020, there is still a long road to go.

## Healthcare and Nursing Staff in Rural India

This section attributes the number of frontlines healthcare workers, the worker who comes first in contact with the patient before the doctor performs the diagnosis. They are trained to deal with minor problems and give remedies.

- Analyzing 2005 data gave the following results:
![11 BWorkR05](https://user-images.githubusercontent.com/78965701/122642172-ab6de300-d126-11eb-8f9b-3011b3a02a3e.jpg)
![12 WWorkR05](https://user-images.githubusercontent.com/78965701/122642174-b0329700-d126-11eb-99a8-58cef1c0799a.jpg)

The results were somewhat different than the previous ones. Other than common entries like UP, Bihar, and West Bengal, small states like Delhi and Punjab also showed up as the worst performer in terms of ratio. Mizoram stood at the best following Lakshadweep.

- Analyzing 2019 data gave the following results:
![13 BWorkR19](https://user-images.githubusercontent.com/78965701/122642181-ba549580-d126-11eb-98c9-3aa92e567978.jpg)
![14 WWorkR19](https://user-images.githubusercontent.com/78965701/122642184-c0e30d00-d126-11eb-9a1f-f9afc39504ca.jpg)

In 2019 too, Delhi had the worst ratio of 6166 following Bihar, UP, MP in the 3000s and 4000s. Lakshadweep had the same ratio of mere 27 people.
![15 BWorkD19](https://user-images.githubusercontent.com/78965701/122642189-ce989280-d126-11eb-8854-3135615fb1b2.jpg)
![16 WWorkD19](https://user-images.githubusercontent.com/78965701/122642197-d35d4680-d126-11eb-9f2a-d0f2626b77a8.jpg)

Following the trend of previous results, Union Territories toped the density may be due to smaller area and comparatively better facility while larger states with a less dense population like Jammu and Kashmir, Arunachal Pradesh showed at the bottom.

- Analyzing 2020 data gave the following results:
![17 BWorkR20](https://user-images.githubusercontent.com/78965701/122642216-e4a65300-d126-11eb-9f67-5f9e3ed50678.jpg)
![18 WWorkR20](https://user-images.githubusercontent.com/78965701/122642221-ea9c3400-d126-11eb-8fdd-6bb7390b1c44.jpg)

This year too large states like Bihar, UP, MP, Maharashtra took the worst position with Ladakh and Laksgdeep at the best. There is an average ratio of 1 for 1000 to 3000 people. The worst performing states are the ones that had the highest number of COVID positive cases. Maybe more people could have been saved if there were ample workforce in these states.
![19 BWorkD20](https://user-images.githubusercontent.com/78965701/122642226-f12aab80-d126-11eb-803a-1081bbf9552c.jpg)
![20 WWorkD20](https://user-images.githubusercontent.com/78965701/122642234-f7b92300-d126-11eb-8761-d99834c8fe48.jpg)

An interesting result showed up this time, Ladakh having the best ratio suffers from the worst density of the country. This further proves the theory that density is more sort of second assessment which could be compared only by having the population density. The density ranged mostly from 0.003 to 0.1.

- The ratio of the staff in different areas can be observed below in the map:

2005
![d](https://user-images.githubusercontent.com/78965701/122642244-07386c00-d127-11eb-82ee-6a086dbdc328.png)

2019

![e](https://user-images.githubusercontent.com/78965701/122642677-49fb4380-d129-11eb-9c1d-fc29406e4391.png)

2020

![f](https://user-images.githubusercontent.com/78965701/122642684-52537e80-d129-11eb-9697-9321d71c252a.png)

The situation of Healthcare workers and nursing staff is more or less similar to doctors. Small states and UT performed better while large states still had to suffer. A general estimate can be made that there is 1 staff to be responsible for around 4000 people which is huge.  The point to be noted that they are the people we look up to for a simple band-aid or at the requirement of minor first aid. There might be 3 to 4 health workers in a medium-sized village and they have to serve the entire village on their own as there is a high probability that there won't be any doctor nearby.

## Primary Healthcare Centers in Rural India

This section includes small healthcare facilities which contain basic amenities such as 2-4 beds, primary medicinal equipment, etc with a dispensary. It might not include machinery and other tech devices for treatment but the facility will be sufficient for acute diseases and primary diagnosis.

- Analyzing 2019 data gave the following results:
![21 BPHCD19](https://user-images.githubusercontent.com/78965701/122642737-8d55b200-d129-11eb-81b9-75b946e5d981.jpg)
![22 WPHCD19](https://user-images.githubusercontent.com/78965701/122642739-9181cf80-d129-11eb-8b88-11c6ded3d455.jpg)

Since the ratio might not be the appropriate comparison, the analysis is done on the basis of density in different states. In 2019, the density came similar to the density of doctors and nursing staff. Lakshadweep had the best density following Pududchery, Dadra and Nagar Haveli and Daman and Diu at around 0.2 while Mizoram, Arunachal Pradesh, and Jammu Kashmir were at the bottom.

- Analyzing 2020 data gave the following results:
![23 BPHCD20](https://user-images.githubusercontent.com/78965701/122642752-9cd4fb00-d129-11eb-889c-296331763e4c.jpg)
![24 WPHCD20](https://user-images.githubusercontent.com/78965701/122642761-a199af00-d129-11eb-9d75-962bfc192bbf.jpg)

The result of 2020 was again similar though Ladakh showed up at the bottom this year.

- The number of PHCs in different areas can be observed below in the map:

2005

![g](https://user-images.githubusercontent.com/78965701/122642779-b7a76f80-d129-11eb-8630-9dd2a2a2d33e.png)

2019

![h](https://user-images.githubusercontent.com/78965701/122642787-c2620480-d129-11eb-8b9c-7133e498fdce.png)

2020

![i](https://user-images.githubusercontent.com/78965701/122642795-ce4dc680-d129-11eb-849b-63031eb9f413.png)

The situation of PHCs seems worse than the above two. Since there is on average 3-4 center in the area of 100km square, how can we even expect the facility to reach the patients? It can also be concluded that the understaffed system also lacks resources to deal with the patients.

## Secondary Healthcare Centers in Rural India

Secondary healthcare centers refer mostly to the amenities required by the patient after being diagnosed by the specialists or doctor. This might include lab centers, radiographers, dedicated centers like the Cancer care center, etc. These facilities are usually expensive and require experts for maintenance and operation.

- Analyzing 2019 data gave the following results:
![25 BSHCD19](https://user-images.githubusercontent.com/78965701/122642846-1967d980-d12a-11eb-8b62-97338969cc43.jpg)
![26 WSHCD19](https://user-images.githubusercontent.com/78965701/122642847-1e2c8d80-d12a-11eb-954a-2b37c79c1eaf.jpg)

As one can expect, the results are very underwhelming. There is 1 facility in 1000 km of Arunachal Pradesh which is disheartening. Most of the results fluctuate between 0.01 to 0.02. Smaller states will normal populations have performed better than smaller states with scarce populations. 

- Analyzing 2020 data gave the following results:
![27 BShcD20](https://user-images.githubusercontent.com/78965701/122642856-27b5f580-d12a-11eb-914f-08bce0995fb6.jpg)
![28 WShcD20](https://user-images.githubusercontent.com/78965701/122642860-2be21300-d12a-11eb-8c86-d02cc6881759.jpg)

The result is no different from the previous year and since Ladakh is a newly formed UT, the infrastructure is trembling of the entire state in every aspect. The state has 98% rural area, still could not receive basic facilities of healthcare.

- The number of SHCs in different areas can be observed below in the map:

2005

![j](https://user-images.githubusercontent.com/78965701/122642872-38ff0200-d12a-11eb-99b7-6b756fa00e23.png)

2019

![k](https://user-images.githubusercontent.com/78965701/122642879-40261000-d12a-11eb-9dfe-1a82360cd789.png)

2020

![l](https://user-images.githubusercontent.com/78965701/122642892-4ddb9580-d12a-11eb-9176-93a153753e17.png)


After analyzing and comparing every aspect of rural healthcare, be it physical infrastructure or workforce, it seems the system has been falling for decades now. Because of lack of attention, the whole healthcare is only left for namesake. Some drastic measures are required to revamp the system or else, a common will be left to suffer due to negligence.
  
  

