## COVID-19 Vaccine Willingness and Hesitancy among Residents in Qatar: a Quantitative Analysis based on Machine Learning
A survey was done among the residents and citizens in the state of Qatar where respondents from various age, gender, nationality and profession participated. In this study, various demographic information along with their respective opinion regarding COVID-19 vaccine willingness and hesitancy were recorded. Based on the recorded data, common statistical and Machine Learning (ML) based analysis were performed to infer the relation between their other responses to their opinion about taking the vaccine.  

![Project Flowchart](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/Documents/Images/Image%201.jpeg "Project Flowchart")   

## Project Breakdown  
The study was divided into three main sections viz.  
- **Descriptive Analysis and Statistical Inference:** In this stage, traditional statistical techniques such as Analysis of Variance (ANOVA), t-test, etc. were performed for finding quantitative characteristics and relations of the data.  
- **Machine Learning based Classification:** ML techniques were used to classify sujects under study into 4 distinct classes (created based on their level of willingness and hesitancy for taking the COVID-19 vaccine) based on collected survey data.  
- **Dominance Analysis:** Dominance Analysis was performed to determine and rank the most contributing parameters behind people's willingness or hesitancy for taking the vaccine.  
![Project Breakdown](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/Documents/Images/Image%202.jpeg "Project Sections") 

## Data Pre-processing for Machine Learning  
Originally the respondents were asked to report their level of willingness and hesitancy for taking the vaccine out of a scale of 7. Both scales were combined to make the problem into a **single 4-Class Problem** as depicted below. It paved a way for robustly classifying the respondents into well-defined classes using ML. The classes are as follows:  
- Willing and Not Hesitant
- Hesitant and Not Willing
- Not Willing but Not Hesitant
- Willing but Hesitant
Mentionable that Hesitancy is not exactly the opposite of Willingness rather it a more vague term where people are confused or hesitant about taking the vaccine for some valid/invalid reason. It can happen even if they are willing to take it due to the pandaemic or lockdown restrictions.  
![Creating 4Class Problem](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/Documents/Images/Image%204.jpeg "Creating 4Class Problem")  

## Machine Learning  
Various ML techniques have been tried for the Classification task. Their Accuracy performances (among other metrics reported in the paper) are as follows:  
![ML Accuracy](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/Documents/Images/Image%205.png "ML Accuracy")  

## Dominance Analysis
Dominance Analysis (DA) also showed plausible and practical results for both Willingness and Hesitancy parameters proving its effectiveness in such cases. The most contributing factors, as provided in the Table below with their respective influences quantitatively reported from many angles, do match with the real-world expectations.

**Willingness DA Table**  
![DA for Willingness](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/Documents/Images/Image%206.png "DA for Willingness")   
**Hesitancy DA Table**  
![DA for Hesitancy](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/Documents/Images/Image%207.png "DA for Hesitancy")   
The scope of this study comprises only of COVID-19 vaccines, and the initial and mid-stage of the vaccine process. This study can be expanded or replicated for other similar studies in order to determine the factors truly contributing for vaccine hesitancy among people of a certain region, nation or culture, and ML can be a great tool to optimize and automate the process.  

## License   
[Apache 2.0 license](https://github.com/Sakib1263/COVID-19-Vaccine-Willingness-and-Hesitancy-among-Residents-in-Qatar/blob/main/LICENSE)  

## Citation Request

If you use ***PPG2ABP*** in your project, please cite the following paper

```
@article{ibtehaz2020ppg2abp,
  title={PPG2ABP: Translating Photoplethysmogram (PPG) Signals to Arterial Blood Pressure (ABP) Waveforms using Fully Convolutional Neural Networks},
  author={Ibtehaz, Nabil and Rahman, M Sohel},
  journal={arXiv preprint arXiv:2005.01669},
  year={2020}
}
```
