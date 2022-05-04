 # Data-Driven Project:  California Animal Euthanasia #
by Zhiwei Feng

Story Title: Kill or Save: Reducing Euthanasia in California Is Starting To Pay Off

Story Context: Shelter euthanasia is one of the most debated topics in the field of animal wellfare. California, being the most populous state in the country, is also known as the state with most shelter-kills. A look at the recent shelter euthanasia data suggests a turn in the trends – shelter euthanasia has dropped significantly since Covid. This data-driven story explore shelter euthanasia in the state of California, and provide a gimplse into the backstory through a hyperlocal focus on Oakland Animal Services.

##  Story: Kill or Save: Reducing Euthanasia in California Is Starting To Pay Off ##
When Robbie the Rottweiler arrived at Oakland's animal shelter, everyone was heartbroken.  
  
Robbie was just hit by a car when animal control found him. His jaw was bleeding, almost completely broken, and needed urgent medical attention.
Within 24 hours, Friends of Oakland Animal Services (FOAS), a local non-profit supporting Oakland's only open-door animal shelter, received donations from over 120 community members, many of whom had received help from the shelter before. Robbie's surgery went successfully. After recovery, he will be prepared for adoption and eventually find himself in a loving home.
  
Robbie is one of the lucky animals. "He would have been euthanized. That (the surgery) was a lot of money," said Tony Cruz, Executive Director of FOAS. But for the past three years in California, more animals like Robbie were saved instead of being put down.
  
One of the biggest challenges for animal welfare in the US is the sheer number of animals coming into shelters, according to the American Society for the Prevention of Cruelty to Animals (ASPCA). In the state of California, approximately 380,000 cats and dogs enter shelters every year, and only half of them would get adopted.
  
Many things could happen to the unadopted. Some go to other shelters with hopes of adoption opportunities elsewhere, some return to the wild after spaying and neutering, and a few escape by accident. Still, for the rest, death is almost certain.
  
As the most populous state in the United States, California has a history of a high number of shelter euthanasia cases. From 2016 to 2019, shelters in the state put down an average of 76,000 cats and dogs annually. In the past six years, California has put down the most animals among all states in the country, plus Washington DC, and US territories.
  
Meanwhile, California has been progressive in pursuing no-kill practices in animal shelters. Since 2020, California has funded shelter-support programs with the state budget and passed multiple legislation banning the retail sale of animals. In 2021, the city of Los Angeles officially became the largest no-kill city in the country, as the life-saving rate had reached the commonly defined no-kill standard of 90%。

Best Friends Animal Society, one of the biggest national advocating organizations for no-kill practices, reported an over 60% drop in overall shelter deaths in California by 2020.

But how did that come to be?

One of the reasons is Covid. According to an ASPCA survey, approximately 1 in 5 Americans acquired a cat or a dog during the first year in Covid.

In California, the desire for animal companionship through seemingly endless lockdowns and quarantines brought a light of hope to animal shelters statewide. The state's adoption rate went up from approximately 49% before Covid-19 to roughly 54% during the pandemic.

But the more significant reason is that fewer animals are entering shelters due to changes in how animal shelters function in communities. Jennifer McDevitt, Development Coordinator at Friends of Oakland Animal Services, has witnessed this effort first-hand.

During the pandemic, the Animal Control Officer of Oakland received a report that someone had chained a dog to the fence, which is illegal in California, McDevitt said.
  
The officer found out that it was a loving home for this animal, but they had fallen under some financial hardships and could not afford to care for the dog's medical situation. Instead of taking that animal away and into shelters, FOAS eventually came up with ways to fundraise and help the owner with medical costs.
  
The key is offering help to owners, working with low-income communities, and keeping animals in homes in the first place, McDevitt said. "Happy dogs, happy guardians, and we would have one more room in the shelters."
  
The cost, Cruz and McDevitt said, is much lower to keep animals in homes instead of taking them into shelters. As part of the effort, FOAS also helps shelters with pet fostering programs, monthly low-cost and free spay and neuter events for community cats, and nearly daily adoption events. The best way to lower shelter intakes and euthanasia is to make saving animals a community-wide effort and let shelters be a last resort for the animals that really need it, they said.
  
While animal welfare workers in Oakland continue their effort, the future of reducing shelter euthanasia still faces multiple layers of challenges.

One crucial obstacle is housing discrimination, Nathan Winograd, Executive Director of The No Kill Advocacy Center, wrote in an email.  
 
"47% of rental housing did not allow pets, and only 9% of pet-friendly units allowed pets without limitations on type or size," citing a Columbia University Research.
  
Another concern for shelters like Oakland Animal Services is a recent increase in pets being returned to shelters as people started going back to work in person, McDevitt said.
 
"We are facing a problem that's never truly going away," Cruz said. "But there is so much room for more and more people to help out there, and starting with awareness would be a big one."

*Author's note: Shelter Euthanasia data are extremely difficult to pinpoint precisely. All current datasets rely on monthly self-report from animal shelters around the US, and may not cover all shelters in operation. The analysis of this story relied mostly on the The Shelter Animals Count dataset, which is one of the largest and most comprehensive collection of shelter data nationwide. Part of the story also referred to dataset published by Best Friends Animal Society, another shelter data collecting organization. Euthanasia data from before 2016 are largely incomplete, therefore this story mostly refer to data dated between 2016 to 2021.* 

## Data Diary ##
This section documents the data analysis process for future reference.
  ### I. Sourcing ###
  #### Data Source ####
  __1. The Shelter Animals Count National Database__
    
  This original dataset is acquired through official request to [The Shelter Animals Count](https://www.shelteranimalscount.org/). However, this dataset is huge (127 megabytes) and was not fit for OpenRefine or google doc. Therefore, I used R studio to extract the portions I needed to perform further analysis. Original Data can be viewed [here](链接链接)
  
  1.1 Subset: California Data
    
  The first subset I extracted is all data with a [state] value of CA. It contains all available shelter data in California. Data can be viewed [here](链接链接)
    
  1.2 subset: All State Euthanasia by Year
    
  The second subset is all state euthanasia numbers by year. It contains only euthanasia numbers in each state and which year the data was for. Data can be viewed [here](链接链接).
  
  __2. The Best Friends Animal Society State-by-state Ranking data__
    
  This data is published by Best Friends Animal Society and can be accessed [here](https://s3fs.bestfriends.org/s3fs-public/211907_State%20Ranking%202021_ECM.pdf). Analyzed data can be viewed [here](链接链接)
    
  *Creator's note: Please not that while Best Friends Animal Society's data is called no-kill, it is not the actual number of euthnasia. Their calculation method is introduced in their [methodology page](https://bestfriends.org/map-methodology).* 
    
  ####Interview Source####
    
  __1.Tony Cruz, Executive Directoer of non-profit Friends of Oakland Animal Services__
    
Email: tony@oaklandsanimals.org
  
Phone Number: (925)-980-9706
    
As the director of local non-profit Friends of Oakland Animal Services, Tony works closely with staff and funders of Oakland Animal Services, the only open-door animal shelter in Oakland, CA. He can provide insight into how local animal shelters functioned, and made effort to lower shelter kill rates despite challenges of funding issue and Covid. Tony invited me to attend their weekly staff meeting where I got the opportunity to meet staff members and ask questions.
  
2. Eric Rayvid, Director Public Relations and Content Marketing & Marnay Chamberlain, Member Liaison of Best Friends Animal Society</h5>
Email: ericr@bestfriends.org & info@bestfriends.org  
  
Phone number: Eric: (917)-861-8290 Marnay:(435)-644-2001
  
Best Friends Animal Society is a non-profit organization that operates the nation’s largest sanctuary for homeless animals. It is also one of the largest data collecting agency and major advocate of the No Kill 2025 campaign. A conversation with Eric and Marnay would provide a larger picture of shelter euthanasia in the United States. Their recourse also allows analysis on California’s status in comparison to other states.

__3. Nathan Winograd, Executive Director, The No Kill Advocacy Center__
  
Email: info@nokilladvocacycenter.org
  
Nathan is only available by email but he could provide insight into the challenges of the no-kill campaign, especially in terms of legal difficulties. Nathan's No Kill Advocacy Center is based also in Oakland, CA and has been pushing for animal welfare legislation nationwide.
  
####Methodology Note####
  
To calculate euthanasia rate in this piece, I am referring to [this academic paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217190/#ref-13), who introduced one of the ways to calculate. This method may be different than some other calculation formulas, such as the ones used by Best Friends Animal Society, etc. 
    
*"The euthanasia rate is calculated by dividing the number of cats euthanized by total live intake, less owner requested euthanasia, and dead on arrival, in accordance with Maddie’s Fund/Asilomar reporting requirements (Maddie’s Fund, 2011). The Save Rate is calculated by subtracting the euthanasia rate from 100. The euthanasia rate does not include those cats who died of natural causes while in the shelter, which is 1% or less annually."*
  
### II. Data Analysis Questions and Visualizations ###

  #### Notes on data cleaning ####
  
  The data aquired from all sources appeared to have been cleaned for analysis. To be sure, I imported the data into OpenRefine and checked the following:
    
    - 1. All City, County, State names are spelled correctly.
    - 2. Animal Shelter names do not have similar clusters, and are spelled correctly.
    - 3. Number, date, and other formats appears to be correct.
      
After that process I have found no major cleaning issue with this dataset, and decided to move on with the analysis.
  

  #### Question Overview ####
  
- Question 1: On average, how many cats and dogs enter California shelters every year, and how many gets adopted
- Question 2: How many cats and dogs are euthanaized annually around 2016 to 2021? What's California's ranking in the US?
- Question 3: How does the adoption and euthanasia rate differ between cats and dogs?
- Question 4: How did adoption rate change before and after Covid break out? How did adoption number change? 
- Question 5: Which county has the highest save rate? Which county has the lowest?
  
  
  #### Question 1: On average, how many cats and dogs enter California shelters every year, and how many gets adopted  ####
  Steps: 
1. (Work on California Shelter Data) Make copy of original dataset, freeze and bold first row.
  
2. Add column and name it "intake_sum", apply function "=SUM(Q2:V2,Z2:AQ2)" (3 columns are not included because owner_intended_euthanasia is not considered in this analysis becuase it is not part of the intake that's intended to stay in the shelter.) And then use cmd+d to autocomplete the rest of the column.
  
3. Add column and name it "adoption_sum", apply function "=SUM(AR2:AT2)" to calculate the sum of adopted animals.
  
4. Create Pivot Table as shown in the screenshot, and calculate average annual intake and adoption, as well as average adoption rate, remember to apply species names as filters and select cats and dogs only
    
    **Therefore reached the conclusion that from 2016-2021, an average of 380k animals enter shelter every year, and only half gets adopted.**
    ![Question1-1](链接链接)     ![Question1-2](链接链接)     <br>![Question1-3](链接链接)
    ![Question1-visualization1](链接链接)（链接图片后 给图片加超链接到：https://infogram.com/question-1-data-vis-1h7g6k0590goo2o?live
  
#### Question 2: How many cats and dogs are euthanaized from 2016 to 2021? What's California's ranking in the US (comparing to other states)? ####
1. Add column and name it "euthanasia_sum", apply function "=SUM(BV2:BX2)", and calculate the sum of euthanized animals.

2. Turn to the pivot table and add euthanasia_sum as value, and can see the number of euthanized animals of each year as well as the total(368431). Remember to apply species names as filters and select cats and dogs only

3. Calculate the average euthanasia rate of 2016-2019, which is 18.35%. Using the same method, the average euthanasia rate of 2020-2021 is 10.50%

4. Move to *All State Euthanasia* data set, add a column and name it euthanasia sum, apply function similar to what have been done above to calculate the sum of euthanasia for all ages.

5. Create pivot table as shown in the screenshot. Apply filters with year of record, which presents euthanasia numbers of each state by year. By selecting 2016 through 2021, we get a overview of how many animals was euthanized by each state in these six years, and California ranks top among all states plus DC and US territories.
    
   ![Question2-1](链接链接) ![Question2-2](链接链接) ![Question2-3](链接链接)
   ![Question2-visualization1](链接链接)(链接图片后 给图片加超链接到：https://datawrapper.dwcdn.net/D4m25/4/）
    

    
    
#### Question 3: How does the adoption and euthanasia rate differ between cats and dogs? #### 
    
   1. (Return to California Shelter Data) Create a pivot table as shown in the screenshot, remember to apply the selected years(2016-2021) and animal species as filters.
   
   2. Calculate adoption rate and euthanasia rate by dividing the sum number by total intake number. Reach conclusion that around 52% of cats and 48% dogs get to be adopted. 23%-24% of cats, and less than 10% of dogs are euthanized in the past six years.
     
   ![Question3-1](链接链接)
   ![Question3-visualization1](链接链接) (链接图片后 给图片加超链接到：https://infogram.com/question-3-vis-1-1h7j4dvy055794n?live)
    
#### Question 4: How did adoption rate change before and after Covid break out? How did adoption number change? ####
  1. Create pivot table as shown in the screenshot
  2. Calculate adoption rate for 2016-2019 and 2020-2021 respectively for comparison.
  3.As screenshot shows, adoption increase since 2020 from 49% to around 54%, yet the total number of adoption dropped.
    
  ![Question4-1](链接链接)
    
#### What happened to Oakland Animal Service's euthanasia rate? Before and since the beginning of the pandemic ####
  
  1. Create pivot table as shown in the screenshot, be mindful of adding organization name: Oakland Animal Service as filter, as well as animal species.
  2. Calculate adoption rate and euthanasia rate like demonstrated above. OAS skipped reporting data in 2016, so this part will start from 2017.
  3. Reach conclusion that Oakland Animal Services showed significant increase in adoption rate and decrease in euthanasia rate.
    
  ![Question5-1](链接链接)
  ![Question5-visualization1](链接链接)(链接图片后 给图片加超链接到：https://infogram.com/question-5-vis-1-1hzj4o35jrw534p?live)
    
 
 
  
