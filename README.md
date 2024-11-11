# HW_11

# SEIR Model Implementation and Sensitivity Analysis for Pandemic Spread

**Author**: [Your Name]  
**Contact**: [Your Email]

### Question Selected
- HW1: SEIR Model Implementation and Sensitivity Analysis

### Key Insights
This project implemented the SEIR model to analyze pandemic dynamics and conducted a sensitivity analysis to understand how variations in transmission and recovery rates impact infection spread. The SEIR model extends the traditional SIR model by including an exposed (E) compartment and birth/death rates, providing a more realistic model of infectious disease spread.

### Comparative Model Performance
- **SIR vs SEIR**: The SEIR model captures delays in the infection cycle due to an exposed period, which the SIR model does not. This leads to smoother infection peaks and oscillatory waves in the SEIR model, illustrating recurring pandemic waves more accurately.
- **Sensitivity Analysis**: The sensitivity analysis showed that higher transmission rates (\( \beta \)) lead to higher peak infections, while increased recovery rates (\( \gamma \)) reduce peak and total infections. These findings align with pandemic control measures, indicating the importance of reducing transmission and increasing recovery rates through social distancing and medical interventions.

### Relevance to Model-Based Machine Learning
Model-based machine learning approaches, like the SEIR model, provide interpretable insights into the dynamics of pandemic spread. These models enable parameter tuning to reflect real-world interventions, demonstrating the utility of incorporating domain-specific knowledge into machine learning models. The model’s compartmental design aids in understanding disease dynamics and designing targeted interventions.

### Suggestions for Future Modeling Improvements
- **Stochastic Modeling**: Future models could incorporate stochastic elements to simulate random events, providing more nuanced pandemic predictions.
- **Vaccination and Immunity Decay**: Including a vaccination compartment and accounting for immunity decay could yield insights into long-term pandemic control.
- **Spatial and Agent-Based Extensions**: Expanding to spatially aware or agent-based models could help simulate localized outbreaks and the effects of varied intervention strategies across regions.


### Disclaimer: 
GPT-4o was used to provide the initial code and answers for this homework problem. 
Having prior experience solving ODEs in Fortran, I felt confident in my ability to access the veracity of ChatGPT's answers and made modifications as needed.
