# AIDS_Virus_Infection_Prediction
Dataset contains healthcare statistics and categorical information about patients who have been diagnosed with AIDS. This dataset was initially published in 1996. I Analyzed the Dataset and after that I used some algorithm like LogisticRegression, RandomForest, SVC, XGBoost and SoftVoting and i got 91% Acc of that and i saved the best model.

## Attribute Information :
time: time to failure or censoring

trt: treatment indicator (0 = ZDV only; 1 = ZDV + ddI, 2 = ZDV + Zal, 3 = ddI only)

age: age (yrs) at baseline

wtkg: weight (kg) at baseline

hemo: hemophilia (0=no, 1=yes)

homo: homosexual activity (0=no, 1=yes)

drugs: history of IV drug use (0=no, 1=yes)

karnof: Karnofsky score (on a scale of 0-100)

oprior: Non-ZDV antiretroviral therapy pre-175 (0=no, 1=yes)

z30: ZDV in the 30 days prior to 175 (0=no, 1=yes)

preanti: days pre-175 anti-retroviral therapy

race: race (0=White, 1=non-white)

gender: gender (0=F, 1=M)

str2: antiretroviral history (0=naive, 1=experienced)

strat: antiretroviral history stratification (1='Antiretroviral Naive',2='> 1 but <= 52 weeks of prior antiretroviral therapy',3='> 52 weeks)

symptom: symptomatic indicator (0=asymp, 1=symp)

treat: treatment indicator (0=ZDV only, 1=others)

offtrt: indicator of off-trt before 96+/-5 weeks (0=no,1=yes)

cd40: CD4 at baseline

cd420: CD4 at 20+/-5 weeks

cd80: CD8 at baseline

cd820: CD8 at 20+/-5 weeks

infected: is infected with AIDS (0=No, 1=Yes)

## Additional Variable Information :
Personal information (age, weight, race, gender, sexual activity)

Medical history (hemophilia, history of IV drugs)

Treatment history (ZDV/non-ZDV treatment history)
Lab results (CD4/CD8 counts)
