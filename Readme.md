### Contest Link
https://www.kaggle.com/competitions/asl-signs

### Notebook Link
The notebook link has more details of the dataset used which can be find here : https://www.kaggle.com/code/stanptown/ensemble/notebook

### Final Accuracy 
Public Score - 0.66
Private Score - 0.74

### Contest Description
Goal of the Competition
The goal of this competition is to classify isolated American Sign Language (ASL) signs. You will create a TensorFlow Lite model trained on labeled landmark data extracted using the MediaPipe Holistic Solution.

Your work may improve the ability of PopSign* to help relatives of deaf children learn basic signs and communicate better with their loved ones.

Context
Every day, 33 babies are born with permanent hearing loss in the U.S.
Around 90% of which are born to hearing parents many of which may not know American Sign Language. (kdhe.ks.gov, deafchildren.org) Without sign language, deaf babies are at risk of Language Deprivation Syndrome. This syndrome is characterized by a lack of access to naturally occurring language acquisition during their critical language-learning years. It can cause serious impacts on different aspects of their lives, such as relationships, education, and employment.

Learning sign language is challenging.
Learning American Sign Language is as difficult for English speakers as learning Japanese. (jstor.org) It takes time and resources, which many parents don't have. They want to learn sign language, but it's hard when they are working long hours just to make ends meet. And even if they find the time and money for classes, the classes are often far away.

Games can help.
PopSign is a smartphone game app that makes learning American Sign Language fun, interactive, and accessible. Players match videos of ASL signs with bubbles containing written English words to pop them.
PopSign is designed to help parents with deaf children learn ASL, but it's open to anyone who wants to learn sign language vocabulary. By adding a sign language recognizer from this competition, PopSign players will be able to sign the type of bubble they want to shoot, providing the player with the opportunity to practice the sign themselves instead of just watching videos of other people signing.

You can help connect deaf children and their parents.
By training a sign language recognizer for PopSign, you can help make the game more interactive and improve the learning and confidence of players who want to learn sign language to communicate with their loved ones.

### Why TensorFlow Lite
To allow the ML model to run on device in an attempt to limit latency inside the game, PopSign doesn’t send user videos to the cloud. Therefore, all inference must be done on the phone itself. PopSign is building its recognition pipeline on top of TensorFlow Lite, which runs on both Android and iOS. In order for the competition models to integrate seamlessly with PopSign, we are asking our competitors to submit their entries in the form of TensorFlow Lite models.
