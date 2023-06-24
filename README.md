___
# Machine Learning Approach for Music Emotion Recognition
___

## Abstract
Music is a powerful language that stirs up a wide range of emotions in people. Understanding and recognizing these emotions is crucial for applications like personalized music recommendations, music therapy, and affective computing. Music Emotion Recognition (MER) systems aim to automatically analyze and classify the emotional content of music, providing insights into how different compositions affect our emotions. 

## Inroduction
Music and emotions share an inseparable bond, surpassing language and cultural barriers. Music has the remarkable ability to evoke a wide range of emotions in listeners. It has the unique ability to evoke joy, sadness, excitement, nostalgia, and many other emotional states. This inherent connection between music and emotions has become a key subject of interest for researchers. Music Emotion Recognition (MER) is an engaging and dynamic area of research that involves the application of machine learning techniques, including neural networks, to unravel the emotional characteristics embedded within musical compositions. It includes the exploration of diverse musical elements, including melody, tempo, rhythm, harmony, and timbre, to ascertain and interpret the range of emotional states evoked by music. Music has the exceptional ability to evoke a wide range of emotions in listeners, making the task of accurately recognizing and classifying these emotions a fascinating challenge.

Moreover, the application of MER extends to various domains, including Enhancing the User Experience, this allows for the development of personalized music recommendation systems, and creating playlists and experiences based on the emotional preferences of individuals. By accurately identifying and understanding the emotional content of music, these systems can provide a more enjoyable and valuable listening experience for users. Also, MER helps in Music Theropy and Mental Health sectors since music has been widely recognized for its therapeutic benefits in promoting emotional well-being and supporting mental health. MER can help in the development of effective music therapy interventions by enabling therapists to select appropriate music that aligns with the emotional needs and goals of their clients. This can reduce stress and anxiety, and improve overall psychological well-being. Moreover, Media and Entertainment industry has huge benefits from MER systems since by analyzing the emotional content of music, it becomes possible to enhance audiovisual experiences in movies, television shows, video games, and advertisements. Understanding the emotional impact of music on viewers and listeners allows for more targeted and impactful storytelling, creating engaging and immersive content. Also in Music Composition and Production sectors and in Music Research and Cognitive Studies, MER systems are widely used.

Given its interdisciplinary nature and wide-ranging implications,MER has garnered considerable attention from researchers. Their efforts are directed towards advancing robust algorithms, machine learning models, and sophisticated signal processing techniques to accurately analyze and classify the emotional content of music.This literature review aims to explore the methodologies, methods, and materials employed in previous studies on MER, with a particular focus on the application of machine learning algorithms and neural networks. we undertake a comprehensive analysis of the performance and accuracy of existing MER systems.By thoroughly examining and evaluating those systems, we aim to identify their strengths, limitations, and areas for improvement. Building upon the foundation laid by previous studies, our aim is to enhance the performance and accuracy of these systems. To achieve this, we explore the potential utilization of Deep Neural Networks (DNN) and Bidirectional Long Short-Term Memory (LSTM) models.

## Preliminary Knowledge
Existing MER publications can be mainly categorized into two sections, namely song-level MER (or static) and music emotion variation detection (MEVD, or dynamic). Assigning
the overall emotion label (or labels, if the task is viewed as a multi-classification or regression problem) to one song is referred to as song-level MER.MEVD considers the emotion of the music as a changing process, where the dynamic changing process of emotion needs to be recognized when conducting MEVD research.

#### Research framework: 
Most existing MER works based on machine learning include three parts and they are, domain definition, feature extraction, and emotion recognition. “Figure. 1”, shows the overall framework of MER systems.

#### Emotion Model: 
Dimensional emotion models are widely used in MER systems. There are two main dimension emotion models namely Thayer’s emotion model and Russell’s circumplex model. Both models use arousal and valence values (AV values) to identify the emotion in a given music sample. Associated with the AV values, each music sample becomes a point in the arousal-valence plane, so the users can efficiently retrieve the music sample by specifying a desired point in the emotion plane."Figure. 2" shows Thayer’s emotion model associated with MER.

| Figure 1 | Figure 2 |
| ------- | ------- |
| ![Image 1](/docs/images/fig1.jpg) | ![Image 2](/docs/images/fig2.jpg) |
|  MER framework   |  Thayer’s arousal-valence emotion plan |


## Related Links
1. [Project page](https://cepdnaclk.github.io/e17-4yp-Music-Emotion-Recognition/ )
2. [Github repo](https://github.com/cepdnaclk/e17-4yp-Music-Emotion-Recognition)
3. [Department of computer engineering](http://www.ce.pdn.ac.lk/)


## Team Members
1. E/17/040 Chandrasena M.M.D [[e17040@eng.pdn.ac.lk](mailto:e17040@eng.pdn.ac.lk)]
2. E/17/356 Upekha H.P.S [[e17356@eng.pdn.ac.lk](mailto:e17356@eng.pdn.ac.lk)]
3. E/17/407 Wijesooriya H.D [[e17407@eng.pdn.ac.lk](mailto:e17407@eng.pdn.ac.lk)]
