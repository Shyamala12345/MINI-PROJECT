Sign Language Detection using LSTM Deep Learning Model
 
Sign language had an incredible growth over the years. Unfortunately, there are some drawbacks that have come along with this language. Not everyone knows how to interpret a sign language when having a conversation with a deaf and dumb person. There is always a need to communicate using sign language. One finds it hard to communicate without an interpreter. To solve this, we need to convert the sign language so that it is understood by common people and will help them to communicate without any barriers. We need a product that is versatile and robust. We need to convert the sign language so that it is understood by common people and will help them to communicate without any barriers. The main purpose of this project is to eliminate the barrier between the deaf and dumb and the rest.
1.INTRODUCTION
Machine learning provides a versatile and robust environment to work on. The machine learning subject also eliminates the need for the coder to write updates whenever a new sign is read, this will be done by the machine itself. Our system aims to get the deaf and dumb people more involved to communicate and the idea of a camera-based sign language recognition system that would be in use for converting sign language gestures to text (English) and then to regional languages.
Our objective is to design a solution that is intuitive and simple which simplifies the communication for the majority of people with deaf and dumb’ There are many methods to convert the sign language. We are using mediapipe to notice the coordinates of markings on the human body and convert the position and moments to text converting sign language to text.

DATASET DESCRIPTION
Using mediapipe we make markings on the human body and face and we are using cv2 to open the camera. Using cv2 we record our videos at a set number of videos and frames and save them to files we create before recording the videos. In the dataset we can record the videos and store them in a folder named after the word the sign represents in the sign language. The order in which the files will be stored is
● MP_Data
○ Hello
○ Bye
○ Thankyou
LSTM Model
Long short-term memory (LSTM) is an artificial neural network used in the fields of artificial intelligence and deep learning. Unlike standard feedword neural networks, LSTM has feedback connections. Such a recurrent neural network (RNN) can process not only single data points (such as images), but also entire sequences of data (such as speech or video). For example, LSTM is applicable to tasks such as unsegmented, connected handwriting recognition, speech recognition, machine translation, robot control, video games, and healthcare. The name of LSTM refers to the analogy that a standard RNN has both "long-term
memory" and "short-term memory". The connection weights and biases in the network change once per episode of training, analogous to how physiological changes in synaptic strengths store long-term memories; the activation patterns in the network change once per time-step, analogous to how the moment-to-moment change in electric firing patterns in the brain store short-term memories.The LSTM architecture aims to provide a short-term memory for RNN that can last thousands of timesteps, thus "long short-term memory".
