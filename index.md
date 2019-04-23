---
github:
  is_project_page: false
---

# About Me
I'm a machine learning researcher and high school student in San Diego, California. Although I'm still in secondary school, I have a passion for academic research and have published three papers in various conferences of machine learning, computer vision, and robotics. I have some experience in industry too, acting as a software developer for a startup company. In my free time I enjoy reading Stoic philosophy, stargazing, singing Indian classical music, and going on walks with my dog Peanut.

# Resume
<div style="width:100%; padding-bottom:100%; position:relative;">
<object data="/Resume.pdf" type="application/pdf" width="100%" height="100%" style="position: absolute; top: 0; bottom: 0; left: 0; right: 0;">
    <p>It appears you don't have a PDF plugin for this browser.
        No biggie... you can <a href="/Resume.pdf">click here to
            download my resume.</a></p>
</object>
</div>

# Projects

## MultiNet: Mulit Modal Deep Learning for Autonomous Driving

<iframe width="100%"
src="https://www.youtube.com/watch?v=VqvoSceKoGA" 
frameborder="0" 
allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>

Autonomous driving requires operation in different behavioral modes ranging from lane following and intersection crossing to turning and stopping. However, most existing deep learning approaches to autonomous driving do not consider the behavioral mode in the training strategy. This paper describes a technique for learning multiple distinct behavioral modes in a single deep neural network through the use of multi-modal multi-task learning. We study the effectiveness of this approach, denoted MultiNet, using self- driving model cars for driving in unstructured environments such as sidewalks and unpaved roads. Using labeled data from over one hundred hours of driving our fleet of 1/10th scale model cars, we trained different neural networks to predict the steering angle and driving speed of the vehicle in different behavioral modes. We show that in each case, MultiNet networks outperform networks trained on individual modes while using a fraction of the total number of parameters.

Deep networks have a hard time taking higher level directions and informations when conducting high level tasks end-to-end. To aid with this I created a system for inserting a "modal tensor" into the processing stream of a deep neural network which helps to guides network decisions (should I turn right or left at this intersection for example). This work used "behavioral modes" such as "direct" which drives on a sidewalk and "follow" which follows another model car driving ahead.

## PhonoNet: Raga Predicton and Visualization
![](https://lh3.googleusercontent.com/EoNKE8b7FQkCOBxHxmXUZAptZm1AKS01fHUyQ6umVR6KwQJmx7ArXIcu0laCecf2NDjIsiMg6wdAlQ5qnm5lR0D8P48zKcUFMjYNOSK5-qEa-AHq76_lU_TfHUmD-Co01KN433zX8M-I3r0yjxbFQnWc0sEmXt6ZjMjuQ-M4u6GsObNdSL_LkgbuTzZB9i9PgOV_kTPvfaSx8tjwD2OIUaM4PVBD2WJqwchdg34AUBlmokizuNChHHMc0QGOPdmkfWjhPNUHo5xfm8uUR0PFz3IbnmBkeKAFI8Vq4mW_P10AO_4XYTrXBlG6fA4blyjLrBwCdiL91Nd62KWF91Z4Z3maWxIlMjU-5eNnEN0N2T_j5zrFHX2kY38OdnRh23Vv4atfMHgoZFs88JLoHPlzIYNWHvibcDqS1etbF1uc038WedRjVu6rTYCe-2MKSSAtCamACTHhXmg50Uc2XWFuWKlvuVjfGFJY8bVCb2sO2oyy-fMmsMKypH2lrhYfd3v5VVRfnsCe2yQXbcdYPJOGPlD9KSWqoqMXLFww0nj8V8GcECFsas7vmS7NpDoeHHPIkDdo3fZW_dCoTWD1ZbP-ijKCBq80YWPwdLsZNyEs8gj7caCoKAIjL2OuYyC4Jg4bZ17CIUpIfORnneqyBBjN92L7YmxtLWp0=w1442-h920-no?style=centerme)
Indian classical music is a fading art form which focuses predominantly on improvisations on specific melodic modes, or ragas. The improvisational nature of the Indian ragas make them very difficult to consistently record in a distributable written format. Because ragas are passed down solely through an ancient oral tradition, much of the rich knowledge of Indian ragas is dying. 

To address this issue, I created the PhonoNet deep learning system for raga detection, a tool which documents and augments the learning of Indian classical music and ragas by providing raga prediction and audio visualization. 

<center>
<a href="https://github.com/sauhaardac/RagaAnalyzer" class="btn" style="background-color: #159957;">View on GitHub</a>
</center>

## SimpleCV for Computer Vision Workshop
<center>
<img src="https://lh3.googleusercontent.com/s5z0n2HKKlqkr2exDPA87TXgrasopPftNlaqIk7ynclknQxLOvWd28imjhmKA2xkRPnuJU85d1Jd_CCHz6_a7f3XVl2rPnuj3b4-qSAHfRuFyAnw7TDmDcTuKvmpAjT7ka5A-SEvPxBY4aVF33ZkjUuq4yGly7oBv3aucN2eSR24wo51w4RMHlct3qbBif5iRTD8GkILEbe4YLtEifDTNHrigo6Ksi4H-QUimU2nmqin2IeVkp0u318VqK1haLvKtMc65cI_gs_i7aIJVqS3IkJunyCW_YQsXTrQyFdkVpmV3rSVn5mTRhRNS8wFH0PqAzdVs0n2JDo439m-jnDdCzsiezfxqjoizLFRJZ8pGbG_bHdekTgOGOdsM9k8tJIBjsw5cZ0kiRGPcS5jquNGUbfkgctN8oCwtRVg8J3DyaXHD2DMqUwzEbWL5Dfm8wTjL7bB45sEKnzCt0vHtkdAtoQb51yq7oYnbe7iThstb5H5d1PZKlRtdOj1iDPRCiD6hlYRFGj3Mg8VmzIDvTVLlGBmlSMRFZKUhFxr8QTu8BPpZ9Wcqreg-cSkjjBkSfyEe6uyw6aIp4EKuAGqujzi38TEmnDLidkBxp8P11rTmsZ2VLFPeKL3Y22NOQUY4Hpksdjci45Nok69FYRjIMRdecdVInbIMCWx=w287-h380-no?style=centerme">
</center>

As the president of my high school robotics team, I lead a number of outreach efforts. For one of our team's STEM workshops, I created a simple wrapper on top of OpenCV called SimpleCV to teach middle school students the basics of image manipulation and computer vision. At the end of the activity, all students could draw a mustache on top of an image of a face and some were able to draw mustaches on themselves with a live feed camera!

<center>
<a href="https://github.com/sauhaardac/A-New-Vision-Workshop" class="btn" style="background-color: #159957;">View on GitHub</a>
</center>

## Haar Cascade Training Library on Windows
![](https://camo.githubusercontent.com/6c87033af321b0c113ac6436e015b655d42d7f5c/68747470733a2f2f6c68332e676f6f676c6575736572636f6e74656e742e636f6d2f2d357475746154415843586f2f562d3748737775644d55492f41414141414141414a66492f32723742324a2d50474a3871503759526f6b626c7876354f6a4e6a32566c774867434c63422f73302f696d6167652e706e67)
A comprehensive library for training Haar Cascades on Windows machines (primary operating system of my robotics team). All necessary files are compiled and stored within the repository with detailed usage instructions. Don't get me wrong, Linux RULES! This is just so my robotics computer vision team members could get started.

<center>
<a href="https://github.com/sauhaardac/Haar-Training" class="btn" style="background-color: #159957;">View on GitHub</a>
</center>
