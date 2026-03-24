# Live Demonstration
 
Supporting material for Andrew Barker's session: AI: Friend or Foe? — ALGA Emerging Professionals Expo, 26 March 2026.
 
Open a public/free AI chat, e.g.:
 
- [chatgpt.com](https://chatgpt.com/)
- [gemini.google.com](https://gemini.google.com/app)
- or use your own account
 
## Example 1: The weak prompt - asking AI for the answer
 
1. Start a new chat, 
2. add the following prompt, 
3. add the Results, using either:
    * [Results](#Results-as-Text) text in the section below, or 
    * attach the [Results.csv](./Demo-Data/Results.csv) file in the [Demo Data](./Demo-Data/) folder
 
```
Screen these results against the NEPM
```

## Example 2: The strong prompt - asking AI for the tool

1. Start a new chat, 
2. add the following prompt, 
3. add the Results, using either:
    * [Results](#Results-as-Text) text in the section below, or 
    * attach the [Results.csv](./Demo-Data/Results.csv) file in the [Demo Data](./Demo-Data/) folder
4. add the Criteria, using either:
    * [Criteria](#Criteria-as-Text) text in the section below, or 
    * attach the [Criteria.csv](./Demo-Data/Criteria.csv) file in the [Demo Data](./Demo-Data/) folder
    

```
The attached tables are chemical 'results' and 'criteria'. The criteria join to the results using the 'Chem Name' column in both tables. Write me an Excel formula that compares column D in the results table against the HIL-A criteria values in the 'Action Level' column in the criteria table. Convert the '<' results to half when comparing values to criteria
```


## Supporting Data 
### Criteria as Text

```
Chem Name,Action Level
Lead,300 mg/kg
Mercury,40 mg/kg
Nickel,400 mg/kg
Arsenic,100 mg/kg
Cadmium,20 mg/kg
Chromium (total),100 mg/kg
Copper,6000 mg/kg
Zinc,7400 mg/kg
```

### Results as Text

```
Location Code,Depth,Sampled Date,Chem Name,Prefix,Result,Unit
BH01,3 - 3.1,15/11/2023,Arsenic,,45,mg/kg
BH01,3 - 3.1,15/11/2023,Cadmium,,24,mg/kg
BH01,3 - 3.1,15/11/2023,Chromium,,615,mg/kg
BH01,3 - 3.1,15/11/2023,Copper,,253,mg/kg
BH01,3 - 3.1,15/11/2023,Lead,,1800,mg/kg
BH01,3 - 3.1,15/11/2023,Mercury,,0.1,mg/kg
BH01,3 - 3.1,15/11/2023,Nickel,,694,mg/kg
BH01,3 - 3.1,15/11/2023,Zinc,,2340,mg/kg
BH01,4.8 - 4.9,15/11/2023,Arsenic,,26,mg/kg
BH01,4.8 - 4.9,15/11/2023,Cadmium,,5,mg/kg
BH01,4.8 - 4.9,15/11/2023,Chromium,,50,mg/kg
BH01,4.8 - 4.9,15/11/2023,Copper,,2150,mg/kg
BH01,4.8 - 4.9,15/11/2023,Lead,,837,mg/kg
BH01,4.8 - 4.9,15/11/2023,Mercury,,0.2,mg/kg
BH01,4.8 - 4.9,15/11/2023,Nickel,,88,mg/kg
BH01,4.8 - 4.9,15/11/2023,Zinc,,5310,mg/kg
BH03,0.5 - 0.6,15/11/2023,Arsenic,,11,mg/kg
BH03,0.5 - 0.6,15/11/2023,Cadmium,<,1,mg/kg
BH03,0.5 - 0.6,15/11/2023,Chromium,,42,mg/kg
BH03,0.5 - 0.6,15/11/2023,Copper,,23,mg/kg
BH03,0.5 - 0.6,15/11/2023,Lead,,22,mg/kg
BH03,0.5 - 0.6,15/11/2023,Mercury,<,0.1,mg/kg
BH03,0.5 - 0.6,15/11/2023,Nickel,,37,mg/kg
BH03,0.5 - 0.6,15/11/2023,Zinc,,72,mg/kg
BH03,2 - 2.1,15/11/2023,Arsenic,,6,mg/kg
BH03,2 - 2.1,15/11/2023,Cadmium,<,1,mg/kg
BH03,2 - 2.1,15/11/2023,Chromium,,28,mg/kg
BH03,2 - 2.1,15/11/2023,Copper,,49,mg/kg
BH03,2 - 2.1,15/11/2023,Lead,,184,mg/kg
BH03,2 - 2.1,15/11/2023,Mercury,<,0.1,mg/kg
BH03,2 - 2.1,15/11/2023,Nickel,,26,mg/kg
BH03,2 - 2.1,15/11/2023,Zinc,,225,mg/kg
BH05,1.8 - 1.9,15/11/2023,Arsenic,,5,mg/kg
BH05,1.8 - 1.9,15/11/2023,Cadmium,<,1,mg/kg
BH05,1.8 - 1.9,15/11/2023,Chromium,,56,mg/kg
BH05,1.8 - 1.9,15/11/2023,Copper,,22,mg/kg
BH05,1.8 - 1.9,15/11/2023,Lead,,26,mg/kg
BH05,1.8 - 1.9,15/11/2023,Mercury,<,0.1,mg/kg
BH05,1.8 - 1.9,15/11/2023,Nickel,,55,mg/kg
BH05,1.8 - 1.9,15/11/2023,Zinc,,344,mg/kg
BH05,5 - 5.1,15/11/2023,Arsenic,,12,mg/kg
BH05,5 - 5.1,15/11/2023,Cadmium,,2,mg/kg
BH05,5 - 5.1,15/11/2023,Chromium,,34,mg/kg
BH05,5 - 5.1,15/11/2023,Copper,,1460,mg/kg
BH05,5 - 5.1,15/11/2023,Lead,,557,mg/kg
BH05,5 - 5.1,15/11/2023,Mercury,<,0.1,mg/kg
BH05,5 - 5.1,15/11/2023,Nickel,,80,mg/kg
BH05,5 - 5.1,15/11/2023,Zinc,,30000,mg/kg
BH05,7.5 - 7.6,15/11/2023,Arsenic,<,5,mg/kg
BH05,7.5 - 7.6,15/11/2023,Cadmium,<,1,mg/kg
BH05,7.5 - 7.6,15/11/2023,Chromium,,52,mg/kg
BH05,7.5 - 7.6,15/11/2023,Copper,,43,mg/kg
BH05,7.5 - 7.6,15/11/2023,Lead,,68,mg/kg
BH05,7.5 - 7.6,15/11/2023,Mercury,<,0.1,mg/kg
BH05,7.5 - 7.6,15/11/2023,Nickel,,79,mg/kg
BH05,7.5 - 7.6,15/11/2023,Zinc,,1950,mg/kg
```

 