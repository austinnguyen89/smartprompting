# Smart Prompting
How to prompt accurately. 

1. **Zero-Shot Prompting**: Directly asking a question without any pre-context or examples. 
   - Example: "What is the capital of France?" This is straightforward, seeking a simple fact, so no additional context is needed for the model to provide the correct answer, "Paris."

2. **Few-Shot Prompting**: Providing a few examples to set context before asking your question.
   - Example: "A cat is to kitten as dog is to what?" Here, the first part of the sentence provides a pattern that helps the model understand the question's intent, leading to the correct answer, "puppy."

3. **Instructive Prompting**: Clearly instructing the model to think or process the information in a particular way.
   - Example: "Imagine you're explaining this to a 5-year-old: What is photosynthesis?" The instruction to simplify the explanation helps the model to deliver an easy-to-understand response suitable for a young child.

4. **Chain of Thoughts/Inception**: Encouraging the model to reason or process the information step by step.
   - Example: "Describe step-by-step how to bake a chocolate cake." This prompt encourages the model to approach the task sequentially, providing a detailed, step-by-step guide to baking a cake.

5. **Self-ask Prompting**: Allowing the model to ask itself questions to further the conversation or reasoning process.
   - Example: "How would I go about designing a new logo for a company?" The model can then generate a list of relevant questions, such as "What is the company's brand identity?" or "What are the company's colors?" to guide the design process.

6. **Emotionally-toned Prompting**: Asking the model to express a specific emotion in its response.
   - Example: "Write a sad short story." Here, the model is guided to generate a response that aligns with the specified emotion - sadness.

7. **Memetic Proxy Prompting**: Having the model assume a role or perspective to answer a question.
   - Example: "As a historian, explain the causes of World War II." The model adopts the perspective of a historian to provide an informed, historical analysis.

8. **Self-consistency Prompting**: Asking the same question multiple times and choosing the most consistent answer.
   - Example: Repeatedly asking "What is the speed of light?" and comparing responses for consistency. This method can help refine the model's accuracy.

9. **Act and ReAct Prompting**: Directing the model to perform an action or suggesting a course of action.
   - Example: "What should I do to convert this English text into French?" The model will recommend using a translation tool or may attempt to translate it if the text is provided.

10. **Plan and Execute Prompting**: Asking the model to devise a plan of action and then detail each step to achieve a complex task.
   - Example: "Create a study plan for a college semester and explain how to follow through each stage." The model will outline a comprehensive plan and guide the user through its execution.

11. **Sequential Prompting**: Breaking down a complex question into a series of simpler questions, then asking them one after the other.
    - Example: "What is a black hole? What causes black holes? What happens when something falls into a black hole?" This method takes advantage of the model's ability to answer simple questions accurately and helps ensure that the answers are in a context the user understands.

12. **Historical Context Prompting**: Providing historical context can help the model provide more accurate or relevant responses.
    - Example: "During the 1960s, what were the key accomplishments of NASA?" By specifying a time period, the model will focus on that era and provide an answer that fits the historical context.

13. **Future Speculation Prompting**: Asking the model to speculate about possible future events or developments. 
    - Example: "What could be the potential impacts of climate change on agriculture by 2050?" This encourages the model to consider future scenarios based on current knowledge and trends.

14. **Goal-Oriented Prompting**: Clearly defining a goal in the prompt can lead to more focused and useful responses.
    - Example: "My goal is to learn French. What are some effective strategies for language learning?" The model's response will be guided by the stated goal, leading to more relevant suggestions.

15. **Hypothetical Scenario Prompting**: You can ask the model to consider a hypothetical situation and then respond accordingly.
    - Example: "If gravity suddenly disappeared, what would happen on Earth?" This type of prompt encourages the model to apply known principles to hypothetical scenarios.

16. **Interpretive Prompting**: Ask the model to interpret or explain something, like a passage of text, a piece of art, or a complex concept.
    - Example: "Interpret the meaning of the poem 'The Road Not Taken' by Robert Frost." The model will analyze the text and provide an interpretation based on its training.

17. **Comparative Prompting**: Asking the model to compare two or more things.
    - Example: "Compare and contrast the leadership styles of Steve Jobs and Bill Gates." This encourages the model to analyze the similarities and differences between two subjects.

18. **Evaluative Prompting**: Asking the model to evaluate something based on a set of criteria.
    - Example: "Evaluate the impact of social media on modern communication." The model will provide a judgment or assessment based on its understanding of the subject.

19. **Perspective-Taking Prompting**: Encouraging the model to answer from the perspective of a specific person or character.
    - Example: "From the perspective of Romeo, describe the love for Juliet." The model adopts the specified perspective to generate a response that fits that character's view.

20. **Brainstorming Prompting**: Asking the model to generate a list of ideas, solutions, or suggestions for a given topic.
    - Example: "Brainstorm ideas for a science fiction short story." The model will provide a list of unique ideas, encouraging creative thought.

21. **Analogy Prompting**: Asking the model to make an analogy to explain a complex concept. 
    - Example: "Explain the concept of quantum mechanics using a day-to-day analogy." The model will provide an analogy that simplifies the complex topic, making it easier to understand.

22. **Cultural Context Prompting**: Providing a cultural context can lead to more specific and accurate responses.
    - Example: "In Japanese culture, what is the significance of cherry blossom festivals?" By specifying a cultural context, the model can provide an answer that's relevant to that culture.

23. **Rhetorical Question Prompting**: Asking rhetorical questions to generate thoughtful responses or to provoke further discussion.
    - Example: "If a tree falls in a forest and no one is around to hear it, does it make a sound?" The model can explore philosophical or theoretical ideas through rhetorical questions.

24. **Refutation Prompting**: Asking the model to refute a common misconception or false statement.
    - Example: "Refute this statement: 'Humans only use 10% of their brains.'" The model can use its understanding to clarify misconceptions.

25. **Support Prompting**: Asking the model to support a statement or idea with facts or logical reasoning.
    - Example: "Support this statement: 'Physical exercise is beneficial for mental health.'" The model can provide evidence or reasons that validate the statement.

26. **Challenge Prompting**: Prompting the model to challenge a popular belief or accepted idea.
    - Example: "Challenge the idea that 'Money can't buy happiness.'" This encourages the model to think critically and present a different perspective.

27. **Prediction Prompting**: Asking the model to predict the outcome based on given circumstances.
    - Example: "Predict the future of autonomous vehicles given current technological advancements." The model can provide an informed prediction based on its understanding.

28. **Creativity Prompting**: Encouraging the model to generate creative content, like stories, poems, or song lyrics.
    - Example: "Write a short fairy tale about a lonely dragon." This kind of prompt stimulates the model's creative capabilities.

29. **Relatability Prompting**: Asking the model to relate a complex concept to something more familiar or simpler.
    - Example: "Relate the theory of relativity to driving a car." The model will provide a comparison that simplifies the complex subject.

30. **Backcasting Prompting**: Defining a desired future outcome and asking the model to suggest how we might reach that outcome from the present.
    - Example: "In 2050, humanity has achieved global climate stability. How did we get there?" The model will generate a plausible path from the current situation to the desired future scenario.

31. **Expansion Prompting**: Asking the model to expand on a brief or condensed idea, concept or statement.
    - Example: "Expand on the statement: 'Music is a universal language.'" This prompts the model to delve into the concept and provide a more comprehensive understanding.

32. **Clarification Prompting**: Requesting the model to clarify a complex or ambiguous statement.
    - Example: "Clarify the statement: 'The pen is mightier than the sword.'" The model will interpret and simplify the statement, making it easier to understand.

33. **Elaboration Prompting**: Asking the model to elaborate on a specific topic or idea.
    - Example: "Elaborate on the potential applications of AI in healthcare." The model will provide a detailed discussion on the given subject.

34. **Visualization Prompting**: Requesting the model to describe a scene, object, or concept as vividly as possible.
    - Example: "Visualize a peaceful evening on a secluded beach." The model will provide a detailed, vivid description to create a mental image.

35. **Socratic Prompting**: Asking open-ended questions to encourage critical thinking.
    - Example: "What are the implications of privacy in a digital age?" This kind of prompt provokes thoughtful discussion on a subject.

36. **Ethical Consideration Prompting**: Asking the model to discuss the ethical implications or considerations of a situation.
    - Example: "Discuss the ethical considerations of genetic engineering." The model will consider various ethical aspects related to the given topic.

37. **Narrative Prompting**: Requesting the model to create a narrative or tell a story based on a given prompt.
    - Example: "Tell a story about a hero who saved their village with the power of music." The model will create a unique narrative based on the prompt.

38. **Consequence Exploration Prompting**: Asking the model to explore potential consequences of a particular action or decision.
    - Example: "Explore the potential consequences of deforestation." The model will provide a detailed account of possible outcomes.

39. **Empathy Prompting**: Asking the model to respond empathetically to a situation or scenario.
    - Example: "How would you comfort a friend who just lost their job?" The model will generate a compassionate and empathetic response.

40. **Opposing Viewpoints Prompting**: Requesting the model to present opposing viewpoints on a contentious topic.
    - Example: "Present opposing viewpoints on the use of nuclear energy." The model will provide balanced arguments from different perspectives.

41. **Precedent Prompting**: Asking the model to provide examples or precedents for a situation or event.
    - Example: "Provide precedents where social media has impacted political outcomes." The model will look back at past events to inform the current situation.

42. **Abstract Thinking Prompting**: Prompting the model to think abstractly about a situation or concept.
    - Example: "Think abstractly about the concept of time." This prompts the model to provide a unique perspective on the topic.

43. **Proposal Prompting**: Asking the model to propose a solution or strategy for a specific problem or challenge.
    - Example: "Propose a strategy to combat climate change." The model will use its understanding to suggest practical solutions.

44. **Teaching Prompting**: Requesting the model to explain a concept as if teaching it to someone.
    - Example: "Teach me the basics of quantum physics." The model will break down the subject into simpler parts for easier understanding.

45. **Role-Playing Prompting**: Asking the model to respond from the perspective of a specific role.
    - Example: "Imagine you're a tour guide in Paris. Describe the city's highlights." The model will generate a response that aligns with the assigned role.

46. **Contextual Clarification Prompting**: Requesting the model to provide clarification for something within a given context.
    - Example: "In the context of software development, what does 'agile methodology' mean?" The model will provide a definition suited to the context.

47. **Association Prompting**: Asking the model to make connections between two or more unrelated things.
    - Example: "What do the ocean and outer space have in common?" The model will identify and explain unexpected connections.

48. **Reverse Engineering Prompting**: Giving the model an end result and asking it to explain how that might have been achieved.
    - Example: "If we have a fully sustainable city, how might we have achieved this?" The model will work backwards from the outcome to propose possible methods.

49. **Reformulation Prompting**: Asking the model to reformulate or rephrase a sentence or concept.
    - Example: "Reformulate this sentence: 'The cat is sitting on the mat.'" The model will provide a different way of expressing the same idea.

50. **Pros and Cons Prompting**: Asking the model to list the pros and cons of a particular decision, policy, or concept.
    - Example: "What are the pros and cons of renewable energy sources?" The model will provide a balanced overview of the advantages and disadvantages.

51. **Scenario Exploration Prompting**: Asking the model to explore potential scenarios based on a particular situation or decision.
    - Example: "Explore the potential scenarios if artificial intelligence surpasses human intelligence." The model will generate possible scenarios based on the situation given.

52. **Paraphrasing Prompting**: Requesting the model to paraphrase a piece of text, maintaining the original meaning but changing the wording.
    - Example: "Paraphrase this sentence: 'The early bird catches the worm.'" The model will produce a rephrased version with similar meaning.

53. **Causal Analysis Prompting**: Asking the model to analyze the causes or effects of a certain event or situation.
    - Example: "Analyze the causes of World War I." The model will delve into the historical factors that led to the event.

54. **Solution Evaluation Prompting**: Presenting the model with a proposed solution and asking it to evaluate its effectiveness.
    - Example: "Evaluate this solution for traffic congestion: implementing a city-wide bike rental system." The model will consider the benefits and potential shortcomings of the solution.

55. **Introspective Prompting**: Asking the model to provide insight into its own functionality or reasoning.
    - Example: "How do you generate responses to prompts?" The model can offer an explanation of its own operating principles, as far as its programming allows.

56. **Direct Comparison Prompting**: Requesting the model to directly compare two or more things.
    - Example: "Compare the leadership styles of Steve Jobs and Bill Gates." The model will provide a comparative analysis based on its knowledge.

57. **Experiential Simulation Prompting**: Asking the model to simulate an experience or describe something from a specific point of view.
    - Example: "Describe a day in the life of a deep-sea diver." The model can provide a detailed, imaginative simulation based on the prompt.

58. **Historical Interpretation Prompting**: Requesting the model to interpret a historical event or phenomenon.
    - Example: "Interpret the social impact of the Internet revolution." The model will provide an analysis based on its understanding of the historical event.

59. **Speculative Fiction Prompting**: Asking the model to create a narrative based on a hypothetical or futuristic scenario.
    - Example: "Create a story set in a world where humans can teleport." The model will craft a unique narrative based on the speculative scenario.

60. **Conceptual Synthesis Prompting**: Requesting the model to synthesize multiple concepts or ideas into a cohesive whole.
    - Example: "Synthesize the concepts of democracy, globalization, and technology in the context of modern society." The model will weave together these concepts into a comprehensive response.

61. **Futuristic Projection Prompting**: Asking the model to project into the future based on current trends or data.
    - Example: "Project the future of remote work based on current trends." The model will predict potential future scenarios using existing data.

62. **Analogical Reasoning Prompting**: Requesting the model to explain a concept using an analogy.
    - Example: "Explain the concept of a black hole using an analogy." The model will present an analogy that simplifies the complex concept.

63. **Sequential Explanation Prompting**: Asking the model to break down a process into sequential steps.
    - Example: "Break down the process of photosynthesis into sequential steps." The model will provide a step-by-step breakdown of the process.

64. **Simplification Prompting**: Requesting the model to simplify a complex idea or concept.
    - Example: "Simplify Einstein's theory of relativity." The model will explain the concept in simpler, more accessible terms.

65. **Subjective Opinion Prompting**: Asking the model to generate an opinion based on a given scenario.
    - Example: "If you were a movie critic, what would your opinion be of the movie 'Inception'?" The model will generate a response based on its understanding of the movie.

66. **Thought Experiment Prompting**: Proposing a hypothetical situation and asking the model to think through it.
    - Example: "Imagine a world where gravity doesn't exist. How would daily life be different?" The model will consider the hypothetical situation and provide a thoughtful response.

67. **Critical Review Prompting**: Asking the model to critically review a piece of work or idea.
    - Example: "Critically review the novel '1984' by George Orwell." The model will provide a detailed critique based on its understanding of the novel.

68. **Problem-Solving Prompting**: Presenting a problem and asking the model to solve it.
    - Example: "Solve this problem: How can we reduce waste in our daily lives?" The model will suggest practical solutions to the problem.

69. **Symbolic Interpretation Prompting**: Asking the model to interpret the symbolism in a piece of art, literature, or event.
    - Example: "Interpret the symbolism in the novel 'To Kill a Mockingbird'." The model will provide an interpretation based on its understanding of the novel.

70. **Personalized Advice Prompting**: Requesting the model to provide personalized advice based on a specific situation.
    - Example: "I'm having trouble staying organized. What advice do you have?" The model will offer advice tailored to the situation provided.

71. **Philosophical Prompting**: Engage the model in philosophical thought or discourse.
    - Example: "What is the nature of reality?" The model will provide its AI perspective on profound philosophical questions.

72. **Unseen Scenario Prompting**: Present a new or unprecedented scenario for the model to contemplate.
    - Example: "How would society change if we could live forever?" The model will extrapolate from known information to create a response.

73. **Translation Prompting**: Ask the model to translate a phrase or text from one language to another.
    - Example: "Translate 'I love you' into French." The model will use its language understanding to provide translations.

74. **Historical Simulation Prompting**: Have the model simulate historical events or timelines.
    - Example: "Simulate the timeline of World War II." The model will generate a chronological sequence of the event.

75. **Conflict Resolution Prompting**: Request guidance on resolving a conflict or disagreement.
    - Example: "How can I resolve a disagreement with a coworker about a project?" The model will suggest possible conflict resolution strategies.

76. **Consequence Analysis Prompting**: Ask the model to analyze potential consequences of a decision or action.
    - Example: "What are potential consequences of deforestation?" The model will provide a list of possible effects based on its understanding.

77. **Emotion Evocation Prompting**: Ask the model to write something designed to evoke a specific emotion.
    - Example: "Write a short story that evokes sadness." The model will craft a narrative with the intent to evoke the specified emotion.

78. **Theory Formation Prompting**: Ask the model to form a theory based on given information or parameters.
    - Example: "Form a theory on why some people prefer dogs over cats." The model will use its ability to recognize patterns and form theories based on those.

79. **Contrast Highlighting Prompting**: Ask the model to highlight differences between two or more items or concepts.
    - Example: "Highlight the differences between classical and quantum physics." The model will compare and contrast the concepts.

80. **Assumption Challenge Prompting**: Present the model with an assumption and ask it to challenge it.
    - Example: "Challenge the assumption that all swans are white." The model will find ways to question or dispute the assumption.

81. **Scenario-Based Teaching Prompting**: You ask the model to teach a concept using a real-world scenario.
    - Example: "Teach me the concept of inflation using the scenario of buying a car." The model will use the scenario to explain the concept effectively.

82. **Element Isolation Prompting**: Ask the model to isolate and explain specific elements within a larger concept or situation.
    - Example: "In the context of a computer, explain the role of the CPU." The model will isolate and explain the function of the CPU.

83. **Creative Brainstorming Prompting**: Request the model to generate a list of creative ideas related to a given topic.
    - Example: "Generate ten creative ideas for a space-themed party." The model will come up with a list of unique and creative ideas.

84. **Pros and Cons Analysis Prompting**: Ask the model to analyze the advantages and disadvantages of a particular decision or situation.
    - Example: "Analyze the pros and cons of starting a new business." The model will provide a balanced view of the potential benefits and drawbacks.

85. **Hypothesis Testing Prompting**: You present a hypothesis and ask the model to test it with logical reasoning.
    - Example: "Test the hypothesis that increasing exercise can improve mental health." The model will use its knowledge to test the hypothesis.

86. **Cultural Analysis Prompting**: Ask the model to analyze a situation, event, or concept from the perspective of a specific culture.
    - Example: "Analyze the concept of 'hygge' from a Danish cultural perspective." The model will provide an analysis rooted in that cultural context.

87. **System Design Prompting**: Ask the model to design a system based on specified requirements.
    - Example: "Design a simple system for managing household chores." The model will propose a system that fits the given requirements.

88. **Case Study Analysis Prompting**: Present a case study and ask the model to analyze it.
    - Example: "Analyze the case study of Starbucks' global expansion." The model will break down the case study and provide an analysis.

89. **Event Prediction Prompting**: Ask the model to predict the outcome of a certain event based on given information.
    - Example: "Predict the outcome of implementing a 4-day work week in a company." The model will make a prediction based on known data.

90. **Role Play Prompting**: Engage the model in a role-play scenario to understand different perspectives.
    - Example: "Role-play a conversation between a customer and a salesperson in a shoe store." The model will simulate a dialogue based on the characters and setting.

91. **Scenario Planning Prompting**: Request the model to create a detailed plan for a specific scenario.
    - Example: "Create a plan for a successful fundraising event." The model will generate a step-by-step plan based on its understanding of successful events.

92. **Syllogistic Reasoning Prompting**: Present a logical syllogism and ask the model to deduce the conclusion.
    - Example: "All humans are mortal. Socrates is a human. What can we conclude?" The model will follow the syllogistic reasoning to arrive at the conclusion.

93. **Visual Description Prompting**: Request a detailed description of a hypothetical or real visual scene.
    - Example: "Describe a tranquil sunrise on a beach." The model will provide a vivid and detailed description.

94. **Relevance Ranking Prompting**: Present a list of items or concepts and ask the model to rank them based on relevance to a specific criterion.
    - Example: "Rank these sports – soccer, tennis, swimming, and golf – based on their physical demands." The model will rank the sports as per the given criterion.

95. **Reverse Engineering Prompting**: Ask the model to reverse engineer a process or concept to understand its origin or workings.
    - Example: "Reverse engineer the process of photosynthesis." The model will provide a breakdown of the process from the end product to the initial stages.

96. **Metaphorical Reasoning Prompting**: Ask the model to use metaphorical reasoning to explain a complex concept.
    - Example: "Use a metaphor to explain the concept of time dilation in relativity." The model will employ a fitting metaphor to make the concept more accessible.

97. **Policy Evaluation Prompting**: Request the model to evaluate the potential impacts of a proposed policy.
    - Example: "Evaluate the potential impacts of a universal basic income policy." The model will consider various aspects and provide an evaluation.

98. **Strengths and Weaknesses Analysis Prompting**: Ask the model to analyze the strengths and weaknesses of a particular person, team, concept, or strategy.
    - Example: "Analyze the strengths and weaknesses of the SWOT analysis strategy." The model will offer an insightful evaluation.

99. **Immersive Storytelling Prompting**: Request a richly detailed, immersive story from the model.
    - Example: "Tell a story about a magical realm where dreams come true." The model will spin a narrative that draws readers into the described world.

100. **Dilemma Resolution Prompting**: Present a dilemma and ask the model for potential solutions or ways to resolve it.
    - Example: "How would you resolve the trolley problem?" The model will propose possible resolutions for the ethical dilemma.
