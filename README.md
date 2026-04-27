# AI Desk Object Sorter

Project Description
This project uses Google's Teachable Machine to classify common objects found on my desk.

Classes Identified
* Class 1 (Calculator)
* Class 2 (Pen)
* Class 3 (Keys)
* Class 4 (Remote)]

 Discussion & Reflection

1.  Model Performance & Iteration:
    My first trained model was fairly accurate. It matched better when the image closely resembled it. Its accuracy would drop when the light was dimmer or when anything was shiny on it. I added some additional images to each, making it perform a lot better and more accurately. This also increased its confidence scores when it had more examples to learn from.

2.  Challenges & Observations:
    The objects that were the easiest for my model to learn and distinguish were the calculator and remote. The button patterns in the remote and calculator made them easy to distinguish. The most challenging object were the pen and keys. I think the way they shone and reflected light made it harder. The pen seemed the hardest, it couldn’t decide if it was keys or the Pan.
When I showed the model an object it wasn't trained on, it tried to classify it as one of the four categories. It would give a low confidence score sometimes, and others would be incorrectly confident. This is important because it shows that the model doesn’t truly understand the object, it will only match the items that it has been trained on.

3.  Bias in AI:
  If I trained my mug with images of my specific model, and didn’t vary any of the features, I think it would struggle to recognize different versions of these objects. A different style remote or calculator might not be recognized correctly.  This shows that bias can be introduced when the training data is too limited. Instead of the model learning only the specific examples, it sees instead the general idea of the object. 
	If my training images were taken in bright lighting, the model would more than likely perform poorly in dim lighting or shadows. This shows that this model can become biased toward certain conditions and not perform as well when conditions vary, like they can in real-world situations.
	If all of my training images were taken in very bright lighting and then you tried to use the model in a dimly lit room or with strong shadows, the model would probably perform poorly. The model can become biased toward certain conditions and not perform well in real-world situations.

4.  Model Limitations & Usefulness
    Some of the key limitations of the model I created are that it struggles with variation in lighting, background, and object positioning. It also has a hard time distinguishing other objects that are not as visually distinct, such as a pen from other thin objects.
	It is useful to be able to download my trained model files like model.json, weights.bin, and share them via GitHub. It allows the model to be reused and shared. This allows others to test the model, improve it, or use it in applications without retraining it from scratch. 

5.  Real-World Applications & Ethics:
     Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
Identify household objects for smart assistants, organizing items in a warehouse, or helping visually impaired users recognize everyday objects. One ethical concern is reliability. Incorrect decisions happen when a model is wrong but highly confident. This is why users must understand their limitations.

(Optional) Challenges Faced / Interesting Discoveries
One challenge was getting enough variation in my images for items like keys and pens. They can look very different, depending on how they are placed. I noted that the model could be confidently wrong, which shows me that high confidence does not always mean the prediction is correct.
desk-object-sorter-ai
