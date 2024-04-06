# Study_Finder_Chatbot

### Initial Challenge

The initial state of Expatrio's study finder tool presented several challenges for international undergraduate students seeking study courses in Germany. Relying on a set of pre-defined questions, the tool often provided irrelevant and unhelpful suggestions, leading to inaccuracies in course recommendations. 

Recognizing the critical need for improvement, the Expatrio team sought our assistance to address these obstacles. The existing study finder lacked an intuitive user experience, failed to accurately connect student profiles with suitable programs, and lacked personalization in the discovery process. 

To overcome these challenges, our goal was to develop a new system that not only replaces the current study finder but also introduces a gamified chatbot. This innovative approach engages students through interactive conversations while implementing a refined matching algorithm that gathers pertinent student information. 

By providing personalized course recommendations based on student interests, qualifications, and preferences, our solution aims to enhance student satisfaction and success in finding their ideal study program in Germany. The scale of the problem is vast, impacting a large number of international undergraduate students. Ineffectiveness in the study finder results in frustration and dissatisfaction during a crucial decision-making process. 

Our proposed solution targets the heart of the issue by addressing the limitations of the existing tool and meeting the unmet needs of international students. Through the development of a user-friendly chatbot and a sophisticated matching algorithm, our project aims to create a more effective and satisfying experience for undergraduate students navigating their educational journey in Germany.

### User Research

In conducting user research for Expatrio's study finder tool, our aim was to thoroughly assess the feasibility and advantages of implementing a chatbot solution tailored to match students with suitable programs in Germany. Through a comprehensive analysis, we investigated the relevance of chatbots in facilitating program matching, scrutinized existing competitors and alternative solutions both locally and globally, and identified key features and functionalities essential for our target audience.

Our research methods encompassed a thorough literature review and a detailed competitive analysis. The literature review delved into the benefits and applications of chatbots in student support and program matching, highlighting their accessibility, scalability, personalization, and engagement aspects. Similarly, the competitive analysis examined offerings by German universities, DAAD, private agencies, and global chatbot platforms such as Comm100, Ada, [Ivy.ai](http://ivy.ai/), EdSights, and Ocelot.

The findings from our research underscored several advantages of integrating a chatbot into Expatrio's platform. These included enhanced accessibility, scalability, personalization, and engagement for students. Additionally, we identified crucial needs of the target audience, emphasizing convenience, multilingual support, cost-effectiveness, and personalization as key factors.

In terms of chatbot functionality, our research highlighted the importance of features such as stateless vs. stateful interaction, natural language processing (NLP), data collection, vector embeddings, enhanced user experience, and improved matching algorithms. However, we also recognized certain limitations, including technical complexity and cost implications associated with AI tools.

In conclusion, our user research strongly supported the adoption of a chatbot solution for Expatrio. The potential benefits of personalization, data collection, and improved matching algorithms present a compelling case for further development. While acknowledging the technical challenges and cost considerations, our research underscores the significance of AI chatbots in enhancing the student experience and optimizing program matching within the Expatrio platform.

### Desired Customer Proposition

Expatrio's chatbot is tailored to meet the needs of international students pursuing undergraduate studies in Germany. We recognize the complexities of navigating a foreign education system, particularly in a language different from one's own. Our chatbot empowers students to navigate this journey with confidence by providing personalized support and guidance.

Expatrio distinguishes itself through a range of key features:

- **AI-powered Matching:** Our cutting-edge algorithms offer a sophisticated and precise matching experience, surpassing the capabilities of traditional information portals.
- **Personalized Interaction:** The chatbot engages users in personalized conversations, adapting its responses and recommendations to suit individual needs and aspirations.
- **Multiple Languages:** Language barriers are eliminated with our chatbot, which is proficient in multiple languages. Students can comfortably interact and receive assistance in their preferred language.
- **24/7 Support:** Accessible anytime and anywhere, our chatbot provides round-the-clock support, ensuring students receive guidance and answers to their queries promptly and efficiently.

With Expatrio's chatbot, international students gain access to a comprehensive support system designed to enhance their educational journey in Germany. Our commitment to personalized assistance, advanced technology, multilingual support, and constant availability sets us apart, empowering students to make informed decisions and achieve their academic goals with ease.

### Questions Development

Based on the research by Perez (2020) on how gender and ethnicity influence college major perceptions, we can consider incorporating aspects that may be influenced by these biases. Here's how each question was informed by or related to the research:

1. **Athletics**:
    - Are you interested in participating in any sports or athletic activities during your time at university?
        - Athletics can be a factor students consider while applying for universities.
2. **Style of Learning**:
    - Do you prefer hands-on, experiential learning, or are you more comfortable with traditional classroom-based learning?
        - Research suggests that stereotypes about certain groups may influence perceptions of their learning preferences.
3. **Social Life**:
    - How important is it for you to have a vibrant social life and be involved in extracurricular activities outside of academics?
        - Social life is one factor when students choose university preferences that they consider the courses and course load they would take.
4. **Subjects of Learning**:
    - What are your primary areas of interest for academic study? Are there specific subjects or fields you're particularly passionate about?
        - Gender and ethnicity stereotypes may influence perceptions of academic interests and passions. Research has shown that certain fields may be stereotypically associated with specific genders or ethnicities. However, in general, students’ choice of University is associated with what majors are available.
5. **Background Biases**:
    - Are there any personal or cultural biases that may influence your decision when choosing a university?
        - This question directly addresses potential biases that may influence university decisions. It’s important to encourage students to reflect on any biases, including those related to gender and ethnicity, that may impact their decision-making process.
6. **Financial Background**:
    - How would you describe your financial situation, and how does it impact your decision-making process when considering university options?
        - Research indicates that socioeconomic status can influence perceptions and opportunities in higher education.
7. **Exchange Semester**:
    - Are you interested in participating in an exchange program or studying abroad during your university experience?
        - Factors such as cultural expectations or financial constraints may play a role in these disparities. However, some students would prefer courses offering exchange semesters to enrich their experience.
8. **What Matters the Most (Academics, Professional, Social, Cost of Living)**:
    - Which of the following factors is most important to you when selecting a university: academics, professional opportunities, social environment, or cost of living?
        - Consider how gender and ethnicity may influence priorities in university selection. For example, research indicates that individuals from underrepresented groups may prioritize factors such as diversity and inclusion in their decision-making process. Therefore, it’s crucial to capture this data to provide the best university matches.
9. **Can Financial Aid Affect Your Enrollment Decision**:
    - Would financial aid or scholarship opportunities significantly impact your decision to enroll in a university?
        - Disparities in access to financial aid can impact enrollment decisions and access to higher education opportunities.
10. **Preferred Cohort Size**:
    - Do you prefer smaller class sizes for a more personalized learning experience, or do you thrive in larger academic communities?
        - These preferences may vary based on cultural background and individual experiences and may influence students’ choices for universities.
11. **Inclusion and Diversity**:
    - How important is it for you to attend a university that prioritizes inclusion and diversity among its student body and faculty?
        - Research suggests that individuals from underrepresented groups may prioritize these factors in their university selection process.
12. **Health & Well-being (Health Insurance)**:
    - Are you concerned about access to healthcare and health insurance coverage while attending university?
        - It’s important to consider disparities in access to healthcare and health insurance coverage. These factors may influence the overall well-being and academic success of students.
13. **Projects**:
    - Are you interested in participating in research projects, internships, or other hands-on learning opportunities during your studies?
        - Research suggests that these opportunities may be unequally distributed among student populations and therefore are important factors to consider.
14. **Student Clubs**:
    - Are you interested in joining any specific student clubs or organizations on campus?
        - Investigate the diversity and inclusivity of student clubs and organizations on campus. Encouraging participation in diverse groups can contribute to a sense of belonging and community.
15. **Reputation of University**:
    - How much weight do you place on the reputation and prestige of a university when making your decision?
        - Consider how perceptions of university reputation may be influenced by gender or ethnicity biases. Research suggests that these biases can impact perceptions of institutional prestige and quality.
16. **Which degree are you aiming for? (put higher weights for this question)**
    - Bachelors
    - Masters
    - PhD

### Ideas Development and Prototyping

During our first sprint, we initiated discussions surrounding the product's overall design, embracing an agile approach to ensure flexibility and responsiveness to evolving requirements. Initially, the notion of crafting a static algorithm with predefined choices dominated our discourse. However, recognizing its limitations in accommodating the diverse backgrounds of our users and susceptibility to biases such as leading questions and selection bias, we swiftly pivoted towards a more adaptable solution. Embracing principles of Kanban and Scrum, we championed a customized approach, leveraging sophisticated Machine Learning algorithms to power our dynamic AI-driven chatbot.

Subsequently, our technical journey delved into the intricacies of developing the AI-powered chatbot. We embarked on a quest for an extensive dataset encompassing information on study programs in Germany, initially exploring the realm of web scraping from reputable sources such as the German Academic Exchange Service (DAAD). Guided by Agile methodologies, we swiftly adapted our strategy upon encountering legal constraints, pivoting towards collaborative engagement with our partner company to secure access to a comprehensive dataset. This dataset, albeit robust with 41 features, posed significant challenges for processing, necessitating meticulous data-cleaning procedures.

**Preparing the vector data:**

We decided to use the RAG - Retrieval Augmented Generation - model to create the personalized recommendations and chat feature. The first step in this was to convert our cleaned data into vector embeddings. We were constrained to using free models, so we chose voyageai to perform the vector embeddings. This choice was arrived at by consulting the Hugging Face [MTEB leaderboard](https://huggingface.co/spaces/mteb/leaderboard) where AI models are ranked on functionalities. Voyageai ranked source and is open source and has easy usability so we adopted it for this project. Next we utilized Google’s gemma-7b-it LLM to parse each entry in the dataset to a summary paragraph and then passed this summarized paragraph into VoyageAI for conversion into vector embeddings. The reason we chose to summarize the entry first was to section the data and maintain the relationship between each entry. At first, we attempted just concatenating each feature of each entry but the length of this turned out to be too large for the embedding model - VoyageAI, hence the need for summarizing. Finally, these embeddings needed to be stored for future retrieval. Vector Databases are especially useful for storing embeddings such as this and so we used [AstraDB](https://accounts.datastax.com/session-service/v1/login) which has a free tier. With these steps followed, our data was ready for inference. You may find the code file we used [here](https://colab.research.google.com/drive/1GgYaJIYbNrFicZvdo2hy55N9PfHy5VrN#scrollTo=VT9CfAXI7v4C).

**Inference:**

Now, we can run inference on our model. To do this we first build a query. As described in another section, we had some questions, based on research, to help the user build this query. While these were pre-determined questions, we allowed the response to be open-ended and flexible, even showing the user their query and allowing them to adjust the information we had gathered from them however they liked. Once the query is built, we then turn this query into a vector embedding using the same VoyageAI model described above. Now based on this query we are able to perform a cosine similarity for semantic search ([this](https://medium.com/@pankaj_pandey/exploring-semantic-search-using-embeddings-and-vector-databases-with-some-popular-use-cases-2543a79d3ba6) is a good explanation of semantic search, vector embeddings and vector databases). The mathematics and most the technicalities is handled by the vector database (AstraDB) and so we merely needed to ask it to perform the search. In this demo, we chose to receive the top 3 entries (from our dataset that we converted earlier) that most fit our search. The choice of 3 was arbitrary and can be changed for future uses if so desired. This is the retrieval stage. However, presenting these three choices to the user was not conducible as it did not necessarily respond to the prompt, it just indicated the data entries that were closest. To give a proper response, we once again harness the power of Google’s gemma-7b-it LLM and augment it with the retrieved data and the student’s query to generate a response. Below was the prompting message we used:

```python
f""" You are a course adviser for a student looking for a course in Germany.
	    Given the student's query {student_details} and possible responses {possible_matches}
	    Start by saying 'Hey {student_name}, based on your interests and preferences, I found the following courses'.
	    To determine the best fit, prioritize the response that aligns most with {degree} and then {major}.
	    You may also draw on external, accurate knowledge about the suggested university/program to determine if it is a good fit
	    Present the best fit and highlight why each is a good fit for their query and which ways it doesn't fit the query perfectly
	    """
```

As the prompt above might show, this gives a response ranking the retrieved entries and explaining why it is a good fit and ways it falls short. 

**Chatbot:** 

Finally, we created a chatbot that has access to the student’s query, the three matches and the final recommendations provided by the chatbot. This allows the user to ask further questions regarding the recommendations they have received and any other aspects they may need clarifications on. The response of the chatbot is based on general knowledge but also supplemented with the data received. As such it can only answer detailed questions that were originally in the dataset or refer the user to check the school’s website. 

Initially, we planned to implement a memory-aware chatbot that remembers previous conversations but the cost of saving those previous message was not supported by the free model that we utilized. Moreover, passing all the information (which is a lot) to the model greatly decreased the quality of the free model. As such for the chatbot, we decided to switch to GPT 3.5-turbo which is a paid, but quite inexpensive model (costing around $1 per million tokens). For reference, a single request with all the information passed is about 1,500 tokens. However, creating a memory-aware chatbot still provided the risk of running up the costs as the conversation got longer and longer. Therefore, we implemented the chatbot without memory, but maintaining our use of GPT 3.5-turbo. For future implementation, it is possible to maintain the use of open-source, albeit a more powerful model. This cannot be run on an average computer however, as they are computationally very expensive. There are ways to host this model on dedicated servers (e.g using Hugging Face inference endpoints/spaces) that can allow us run these models, but these cost money - although inexpensive. 

To make this more presentable, we went with [Gradio](https://www.gradio.app/) UI to display the predetermined questions and chatbot in a more interactive but simple manner. We didn’t put too much effort into the design of the UI as advised by our partner, merely using Gradio’s already existing template. For future use cases, it may be helpful to consider personalizing or improving the UI to Expatrio’s taste. 

### Final Prototype

**Step 1: Data Collection and Cleaning**

- We first collected and cleaned the data by using the provided scraped data by Expatrio
- We filtered the data of interest from the data set
    
    **1- Program name:**
    
    We need to retrieve the name of the university and the name of the program respectively from those two columns “the university_name” and “study_name”. Also, indicate the degree (masater”s,bachelor”s, Ph.D) from the “degree column”.
    
    **2- Program Details**
    
    From the column “o_teaching_language” and “o_languages”, determine the teaching languages of the course and whether the course is taught in multiple languages or not, and if so what are these languages. Also, consider the mode of study if it”s offline or online, or hybrid. Eventually, from the column “o_programme_duration” the number of semesters spent in the program. Moreover, from the column “O_joint_degree” indicate, if the program is double major or not. Eventually, From the “description_content” column, we need to determine what is the learning style and desired skills and background appropraitte for someone who is taking the program.
    
    **3- Finances:**
    
    For each program, we need to take numbers from the following columns: the tuition_fees_program, Cost_of_living, and the semester_contribution and sum them so that their numerical output would be the total fees for the program. Moreover, you should browse the column of “Possibility_of_finding_part_time_employment” to indicate whether students can get work on campus or external internship opportunities to fund their living costs while being in the university. Eventually, consider checking in the “accommodation” column whether there are accommodations provided for the students or not because it will determine whether the students should look for independent housing or not. From “funding_opportunities_within_university” and “description_of__above_mentioned_funding_opportunites__within_universities” indicate if there are scholarships or funding opportunities within the university and talk about them.
    
    **4- Admission Requirements:**
    
    Eventually, We also need to define if there are any special requirements to secure admission in the program from admission_requirements and language_requirements.
    
- We prompt engineered Google’s gemma-7b-it to give a course description combining the data of interest.
    
    ### This is the prompt:
    
    Given a prompt {prompt} with the following data about courses in Germany,  Consider yourself a seasoned data engineer. You are tasked with providing key information about various courses in Germany in a single-paragraph format. The goal is to create a concise overview for efficiently matching international students with suitable programs. The paragraph should include the following details: We are designing a matching algorithm that takes information from international students looking to study in Germany and matches them with the best programs or degrees. We have a large dataset with multiple entries that contains some information about the different courses in Germany. We need to create a dataset that contains the information about these courses. We want to distill the information from our large dataset and summarize it into shorter and smaller versions so that the vector embedding algorithms that will match the student with the program provide accurate results. The final data should be written in a paragraph format and contain the following sections respectively: 1- Program name: First and foremost in the paragraph; we need to retrieve the name of the university and the name of the program from those two columns “the university_name” and “study_name.” Also, indicate the degree (master”s, bachelor”s, Ph.D.) from the “degree column.” 2- Program Details From the columns “o_teaching_language” and “o_languages,” determine the teaching languages of the course, whether the course is taught in multiple languages or not, and if so, what these languages are. Also, consider the mode of study, whether offline, online, or hybrid; eventually, from the column “o_programme_duration,” the number of semesters spent in the program. Moreover, the column “O_joint_degree” indicates whether the program is a double major. Eventually, from the “description_content” column, we needed to determine the learning style, desired skills, and background appropriate for someone taking the program. 3- Finances: For each program, we need to take numbers from the following columns: the tuition_fees_program, Cost_of_living, and the semester_contribution and sum them so that their numerical output would be the total fees for the program. Remember, you should provide numerical output here. Moreover, you should browse the column “Possibility_of_finding_part_time_employment” to indicate whether students can get work on campus or external internship opportunities to fund their living costs while at the university. Eventually, consider checking in the “accommodation” column whether accommodations are provided for the students because it will determine whether the students should look for independent housing. From “funding_opportunities_within_university” and “description_of__above_mentioned_funding_opportunities_within_universities,” indicate if there are scholarships or funding opportunities within the university and discuss them. 4- Admission Requirements: Eventually, we also need to define if there are any special requirements to secure admission into the program, from admission_requirements and langauge_requirements.
    

**Step 2: Preprocessing and Embedding**

- We started by preprocessing the cleaned data by tokenizing.
- We converted the processed course description text to vector embeddings using the free [voyageai](https://dash.voyageai.com/) vector embedding model.

**Step 3: Semantic Search and RAG Model Training**

1. Using the similarity metric of?خ
2. Choose a RAG model architecture.
3. Implement a retrieval mechanism to efficiently retrieve relevant passages from the corpus using the trained RAG model. (Utilize prompt engineering and iterate to identify the best way to generate the desired answers)

### Step 4: Chatbot Integration

1. Develop a chatbot interface using the open-source Python library Gradio.
2. Integrate the trained RAG model into the chatbot interface to provide responses based on user queries.

Amidst our agile strides, we encountered a juncture during the second sprint wherein the viability of our UI design came under scrutiny. Tempted by the allure of gamification, we initially envisioned a maze algorithm-inspired interface to captivate our target demographic of 16-20-year-olds. 

We envisioned the maze idea where students enter a maze and answer questions at each checkpoint, the answers will translate to students’ interests and traits and this could be matched to the courses of interest using vector embeddings and the RAG model. Finally, on the maze exit, the students arrive at the best matching university and course for their interests.

However, adopting a Scrum mindset, we conscientiously deliberated the frontend intricacies and opted for a pragmatic approach. Focused on delivering value incrementally, we deferred the implementation of the maze UI in favor of a streamlined Chatbot interface, earmarking the former as a future endeavor. Indeed, we found that 64% of CX leaders are increasing their investments in chatbots and it’s generally a successful competitor to existing solutions.

# Sources

### **Existing Competitors**

- https://www.study-in-germany.de/en/plan-your-studies/study-options/programme/higher-education-compass/
- http://www.educationplanner.org/students/self-assessments/learning-styles-quiz.shtml
- https://learningstylequiz.com/quiz/start
- https://vark-learn.com/the-vark-questionnaire/
- https://www.ie.edu/university/program-quiz/
- https://universitycompare.com/degree-quiz

### **Technical Research**

- **Target Challenge Research**
    - Zendesk. (2023). *The Zendesk Customer Experience Trends Report 2023*. CX Trends 2023. https://cxtrends.zendesk.com/
    - TEST, E. (2022, March 9). *Germany International Student Statistics 2022*. Erudera. https://erudera.com/statistics/germany/germany-international-student-statistics/
- **AI Research**
    - MOC. (2020, April 15). *10 Amazing Cases Of Using AI in Business*. Master of Code Global. https://masterofcode.com/blog/10-amazing-cases-of-using-ai-in-business
- **Vector Embeddings**
    - Analytics Vidhya. https://www.analyticsvidhya.com/blog/2021/10/support-vector-machinessvm-a-complete-guide-for-beginners/
    - Saini, A. (2021, October 12). *Support Vector Machine(SVM): A Complete guide for beginners*.
- Chatbot
    - Abdellatif, A., Costa, D., Badran, K., Abdalkareem, R., & Shihab, E. (2020). Challenges in Chatbot Development. *Proceedings of the 17th International Conference on Mining Software Repositories*. https://doi.org/10.1145/3379597.3387472
    - Ritter, D. (2023, January 26). *Chatbot statistics crucial to know in 2023*. Dashly Blog. https://www.dashly.io/blog/chatbot-statistics/

### Academic Research

- **Learning Styles**
    - Buckley, J. (2007). *Learning Styles: Are There Differences Between Academic Majors? Learning Styles: Are There Differences Between Academic Majors?* https://scholarworks.calstate.edu/downloads/k3569541z
    - Komarraju, M., Karau, S. J., Schmeck, R. R., & Avdic, A. (2011). The Big Five personality traits, learning styles, and academic achievement. *Personality and Individual Differences*, *51*(4), 472–477. https://doi.org/10.1016/j.paid.2011.04.019
    - Koohestani, H. R., & Baghcheghi, N. (2020). A comparison of learning styles of undergraduate health-care professional students at the beginning, middle, and end of the educational course over a 4-year study period (2015–2018). *Journal of Education and Health Promotion*, *9*(208). https://doi.org/10.4103/jehp.jehp_224_20
    - Magulod, G. (2019). Learning styles, study habits and academic performance of Filipino University students in applied science courses: Implications for instruction. *Journal of Technology and Science Education*, *9*(2), 184. https://doi.org/10.3926/jotse.504
    - Komarraju, M., Karau, S. J., Schmeck, R. R., & Avdic, A. (2011). The Big Five personality traits, learning styles, and academic achievement. *Personality and Individual Differences*, *51*(4), 472–477. https://doi.org/10.1016/j.paid.2011.04.019
- **Questions’ Generation**
    - Perez, A. (2020). Major Biases: How Gender and Ethnicity Influence College Major Perceptions. *Digital.library.txst.edu*. https://digital.library.txst.edu/items/c965c890-947c-4d77-98f6-7252141382d3
