**AI Desk Object Sorter**

_**Project Description**_

Using Google's Teachable Machine, common objects that could be found on any desk were classified. 

_**Classes Identified**_

Class 1: Desk Clock
Class 2: Computer Mouse
Class 3: Computer Keyboard
Class 4: Pencil

_**Discussion & Reflection**_

(Please answer the following questions thoughtfully.

1. Model Performance & Iteration

	How accurate was your first trained model?
The first trained model was extremely accurate. The accuracy rate was approximately 98%.

	What steps did you take to iterate and improve its performance? (e.g., added more images, diversified image types for a specific class).
I added more images, striving to find desk clock images that were similar to the one the model misidentified. After adding several images, I retrained the model.

	How did these changes affect the model's accuracy and confidence scores?
The changes I made improved the model’s accuracy and confidence to 100%.

2. Challenges & Observations:
	Which objects were the easiest for your model to learn and distinguish? Why do you think that was?
Almost all objects were easy for the model to learn and distinguish. I think it was because the objects in each category shared common traits.

	Which objects were the most challenging? What made them difficult (e.g., similar shapes, variable appearances)?
The object the model found most challenging was a desk clock. I believe the model found it difficult because its triangular body and woodgrain shell were unique.

	What happened when you showed the model an object it wasn't trained on? How did the confidence scores behave, and why is this significant?
My model’s classes were desk clock, computer keyboard, computer mouse, and pencil. To challenge the model, I showed the model an image of a mouse (the mammal variety). The furry mouse was not part of the training data. The model determined the mouse to be a desk clock. The challenge was continued with a different mouse image, a pencil formed into a circle, and a computer keyboard that was on fire. The confidence score for the first mouse image was 100%, but it was identified 100% incorrectly. The other objects were classified as possibly being three different classes. The numbers varied from 11% to 88%. The scores could prompt a reliance on bad information, instilling false confidence in an AI’s answer.

3. Bias in AI:
	If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? How does this illustrate the concept of bias being introduced through training data?
The model would probably exhibit poor performance when shown mugs that are significantly different. Since the model learned characteristics of a particular mug, and not the general concept of “mug”, bias was introduced. The AI model then makes incorrect predictions when viewing unfamiliar mugs.

	Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?

The model would develop a dependency on the bright, direct light. It might not detect mugs or even misclassify the mugs. This would show a lack of robustness. It would also highlight how bias in the training environment could limit the model’s reliability.

4. Model Limitations & Usefulness:
	What are some key limitations of the model you created?
It lacked generalization.  It developed overfitting and was too focused on the training data.

	Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable?
Downloading the files allows portability. The model could be reproduced. Sharing the files lets others test, reuse, or improve the model. It adds to the ability to collaborate with others.

5. Real-World Applications & Ethics:
	Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
	 Inventory in the workplace—Automatically track usage of office supplies
	 Home automation—A smart refrigerator could track the contents and assist with meal planning.
	 Retail—Point of sale systems identify products for self-checkout.
	
	Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).
Fairness should be a primary consideration. If the model is biased, cultural differences may be ignored. Groups may become excluded or represented incorrectly. To ensure fairness, data must be diverse and representative.

_**(Optional) Challenges Faced / Interesting Discoveries**_
	It’s my opinion that AI cannot replace a human. An AI model cannot intentionally produce an item that a human finds funny. However, AI results can be funny without intention.

_**(Optional) Screenshot**_
	You can embed a screenshot of your Teachable Machine interface here if you like.
 
<img width="493" height="965" alt="Screenshot 2025-11-18 183551" src="https://github.com/user-attachments/assets/0ada9367-f214-4e16-96b8-01a612ba32aa" />
