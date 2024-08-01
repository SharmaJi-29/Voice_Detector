# Voice_Detector
My Building AI Course project

<!-- This is the markdown template for the final project of the Building AI course, 
created by Mrityunjay Sharma! -->

# Project Title - Voice Detector

This is the Final project for the Building AI course which is held by elementsofai.com by Google. below the necessary information about my project "Voice Detector"

## Summary

In this project, I will make project with the help of AI which recognise the Voice of the humans (like Male Voice or Female Voice). with the help of various module (tensorflow, xgboost, mglearn, sklearn etc) and use of different types of classifiers (XGBClassifier, RandomForestClassifier etc.) to get to know whether it is male voice or female voice. !


## Background

Voice activity detection (VAD) is a technique in which the presence or absence of human speech is detected. The detection can be used to trigger a process. VAD has been applied in speech-controlled applications and devices like smartphones, which can be operated by using speech commands.

Voice recognition software on computers requires analog audio to be converted into digital signals, known as analog-to-digital (A/D) conversion. For a computer to decipher a signal, it must have a digital database of words or syllables as well as a quick process for comparing this data to signals.

This is how you make a list, if you need one:
* problem 1 - Consumers can multitask by speaking directly to their voice assistant                 or other voice recognition technology.

* problem 2 - Users who have trouble with sight can still interact with their devices.
 
* problem 3 - Machine learning and sophisticated algorithms help voice recognition                  technology quickly turn spoken words into written text.


## How is it used?

  # Process of using the solution
  1. Insert csv format of voice instead of wave format as an input which will be recognoize.
  2. It convert csv dataset of voice into essential csv dataset wherein main data columns are present.
  3. After that It Will be recognize the voice which are Male or Female using XGBClassifier() because it have higher accuracy.
  4. Then it display the result of Voice are male voice or female voice.


  It can be classified the voice of the man which is as like this image as given below :

  ( https://img.freepik.com/premium-photo/cheerful-man-engages-lively-conversation-his-mobile-phone-while-gesturing-with-his-hand_116547-       114750.jpg?size=626&ext=jpg )

  or voicec of a women or a female which is also recognised by my voice detector. A female is tell something in a wave format of voice         like this :

  ( https://media.istockphoto.com/id/1226400727/photo/african-woman-takes-part-in-videocall-chatting-with-foreign-friend.jpg?                  s=612x612&w=0&k=20&c=D58Lb1jQQe0e-DXmwkFjQwLHR0xVVJdRv8TTY6ubL9Y= )


## Data sources and AI methods

I can access data from the Internet by the help of google, where I can easily find the voice of Male and female also in the wave format as well as csv format, So I download those data and put into my projectand recognise the voice of male and female.Below is the link for the voice dataset : 

https://www.audible.in/?ref=Adbl_ip_rdr_from_US&source_code=AUDTM002080318002F&ipRedirectFrom=US&ipRedirectOriginalURL=ep%2Faudiobooks

There is the various Data Sources and AI method used in this project : 

| Data Sources| Description                             |
| ----------- | --------------------------------------- |
| Tensorflow  | for recognition of voice                |
| Pandas      | Imserting dataset into the compiler     |
| Numpy       | Numerical python to recognise the voice |
| sklearn     | Use various classifier for accuracy     |
| Matplotlib  | Graphical Analysis                      |
| seaborn     |  Advanced graphical Analysis            |

## Challenges

1. The challenge of accuracy. The accuracy of a Speech Recognition System (SRS) must be high to create any value. ...
2. The challenge of language, accent, and dialect coverage. 
3. The challenge of data privacy and security. ...
4. The challenge of cost and deployment.


## Uses 

The uses for voice recognition have grown quickly as AI, machine learning and consumer acceptance have matured. Examples of how voice recognition is used include the following:
1. Virtual assistant 
2. Smart device 
3. Automated phone system

## Advantages of Voice Recognition 

1. Consumers can multitask by speaking directly to their voice assistant or other voice recognition technology.
2. Users who have trouble with sight can still interact with their devices.
3. Machine learning and sophisticated algorithms help voice recognition technology quickly turn spoken words into written text.
4. This technology can capture speech faster than some users can type. This makes tasks like taking notes or setting reminders faster and more convenient

## Disadvantages of Voice Recognition 

1. Background noise can produce false input.
2. While accuracy rates are improving, all voice recognition systems and programs make errors.
3. There's a problem with words that sound alike but are spelled differently and have different meanings -- for example, hear and here. This issue might be largely overcome using stored contextual information. However, this requires more RAM and faster processors.

## What next?

1. Clear its present disadvantages like background noice etc.
2. With continuous advancements in AI
3. we can expect more sophisticated and accurate voice recognition system.
4. more understanding of context and emotion in speech, allowing for more pertionalized and responsive interactions.


## Acknowledgments

* My Source of inspiration is the Google assistant and Siri from apple.
* the act of recognizing and validating the importance or quality of someone’s voice or speech.
* Technique used in speech processing in which the presence or absence of human speech is detected

## References

1. https://en.wikipedia.org/wiki/Voice_activity_detection
2. https://www.languagehumanities.org/what-is-voice-activity-detection.htm
3. https://www.shaip.com/blog/voice-recognition-overview-and-applications/
4. https://www.researchgate.net/publication/221786556_Voice_Activity_Detection_Fundamentals_and_Speech_Recognition_System_Robustness
