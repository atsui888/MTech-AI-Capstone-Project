# MTech-AI-Capstone-Project
National University of Singapore - Institute of System Science - Masters of Technology in Artificial Intelligence Systems - Capstone Project<br>
By Richard Chai (https://www.linkedin.com/in/richardchai/)


# Problem Statement
The persistent misalignment between question complexity and perceived difficulty presents a fundamental challenge in AI-driven educational technologies, where subjective human judgments frequently diverge from objective question characteristics. 
<br>
> “How can we improve the AI system’s ability to generate questions with complexity levels that consistently align with human expectations of difficulty?”
<br>

# Challenges
Achieving proper alignment between AI understanding of question complexity and human perception of difficulty faces several interrelated challenges.
This is because "difficulty" is:
- A Fluid Concept
- Malleable
- Hard to Define and Measure

Hence, to date, there is no universal standard for defining and measuring question difficulty.


# Proposed Solution - The Cerebro Index Framework
Introducing the Cerebro Index (CI), a novel framework that integrates educational theory, cognitive science, and technical metrics into a unified system to quantify the complexity of a question.
<img width="2970" height="1800" alt="Cerebro Index Framework - visual selection" src="https://github.com/user-attachments/assets/b6f3aa52-65b0-487e-a13f-4ef04550fc61" />

When given a text question as input, the Cerebro Index Framework outputs a complexity score (CI Score) that quantifies and represents the question’s inherent complexity. CI Scores are in a continuous range from 0.0 to 10.0 (inclusive).
The CI framework addresses limitations in existing methods, such as subjective human judgment, rigid rule-based systems, and opaque machine learning models, by combining educational theory with scalable, interpretable metrics.  
<br>

# Cerebro Index Framework - System Design
<img width="2101" height="1210" alt="CI System Components" src="https://github.com/user-attachments/assets/c3e8802d-6833-4f0b-9440-f4623e56d2d4" />

<img width="1842" height="1103" alt="System Implementation" src="https://github.com/user-attachments/assets/c140047e-0c59-49a8-b259-79ee5a39e787" />


# Human Validation of the CI Framework
<b>Research Questions</b>
1.	RQ1: Do CI scores positively correlate with human-perceived question complexity rankings?
2.	RQ2: Do CI complexity categories align with those assigned by human evaluators?
<img width="2849" height="1604" alt="Finding 01" src="https://github.com/user-attachments/assets/8c9791ce-f98b-4141-a0f8-a14f6a059da5" />
<br>
Human evaluators frequently do not agree among themselves on complexity categorisation.
<br>
<img width="2853" height="1601" alt="Finding 02" src="https://github.com/user-attachments/assets/1fe20356-0851-4cd2-8205-a2fa085edf1e" />
<br>


# Limitations
While the results are promising, especially for RQ1, the study has limitations. The sample size was small, with only 54 unique questions evaluated by 51 participants for a total of 588 ranked or categorised questions, which limited the statistical power of the study. 
It was a deliberate study design not to provide rubrics to the human evaluators to avoid biasing judgements. While the study did capture the raters’ natural correlations and category assignments, it introduced variability in human judgment for RQ2.

The coverage for this study was narrow, with only three domains and limited question diversity. 
Despite these constraints, the study confirmed the potential of the Cerebro Index Framework.
<br>


# Study Conclusion and Next Steps
The Cerebro Index (CI) Framework demonstrates empirical validity as a quantitative method for assessing question complexity. The framework exhibits strong rank-order correlation between CI Scores and human-perceived difficulty (Spearman’s ρ > 0.7 in 6 of 9 domain-format conditions), with statistically significant alignment (p < 0.05) in key configurations such as Time in Personal Travel - MCQ (ρ = 0.943) and Supervised Machine Learning - True/False (ρ = 0.986).
<br>

These findings support the CI Framework’s utility in:
- Cognitive load modelling in educational assessments
- Instructional sequencing and curriculum design
- Adaptive learning systems, where CI scores can inform item selection and difficulty progression
- AI evaluation, enabling benchmarking of LLMs on questions with objectively calibrated complexity

Furthermore, the standardised nature of CI scoring enables cross-domain comparability, allowing for equating difficulty across disparate knowledge areas (e.g., supermarket math vs. machine learning theory), provided format-specific adjustments are applied.
The CI Framework provides a psychometrically grounded, continuous measure of question complexity that bridges subjective perception and objective quantification. 
<br>

With further refinement and expanded validation, the Cerebro Index Framework has the potential to become a foundational tool for intelligent tutoring systems, automated assessment design, and rigorous AI capability benchmarking, enhancing the AI ability to generate questions with complexity levels that consistently match the difficulty expected by human users.

<br>
<img width="1315" height="201" alt="End Image CI Framework" src="https://github.com/user-attachments/assets/704e454d-d108-44eb-8066-8b926318bcc3" />






