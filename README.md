<p align="center">
<img src="assets/python%20logo.png" width="80">
</p>

<h1 align="center"> Python Error Helper </h1>

<img src="assets/whimsical%20book.png" width="45" align="left">

### THE STORY

Even though python is one of the easier codes to use, it can get a little stressful when errors keep plauging your work.
Especially when they're very simple mistakes compared to the very loud error message. 

Before, I used to Google every error message and when the python website made no sense it was the guy on reddit from 13 years ago who had the answers. But these weren't quick internet searches. 

I know its all part of the learning process but sometimes it was a bit too painful. Eventually I dreaded those errors messages; I knew when I saw one, it was going to be a long night.

---
<img src="assets/checklist2.png" width="40" align="left">

### THE PROJECT

This is a web app that is the less dramatic version of an error message and better, it comes with an example of how to correct this issue. Beginners can compare this to their own code and see what went wrong. Thus preventing one more newbies from rage quitting python.

---
<img src="assets/video-icon.png" width="40" align="left">
### GIF DEMO OF THE APP


---
<img src="assets/Magnifying%20glass.png" width="40" align="left">

### BEHIND THE BUILD

I had fun using the feature such as st.button(), and st.warning(). Normal writing boxes were boring so these gave it a bit more flair and personality. 

Though the dictionary did test my patience, I spent the longest on it and when it got to the Indentation error I had to google how to make it look like it was actually on python. (Worth it) Dictionarys are one of those things where once you get them they are absolutely wonderful.

Since this is a web app aimed at beginners it can only work with 3 types of errors including:

- `SyntaxError: expected ':'`
- `IndentationError: expected an indented block`
- `NameError: name 'x' is not defined`

I associated those errors with beginners mistakes because a lot of my crashes were due to those simple things. Especially the Indentation. 

---

<img src="assets/hourglass.png" width="50" align="left">

<details>
<summary><strong><h3>
IF I HAD MORE TIME...
</strong></h3></summary>

- If I dedicated more time to this web app I'd add more errors.
- I would make the formatting nicer just for my own personal satisfaction. 

- It would be great if someone could try on their own to fix an error and for the web app to tell them you got it right or to give a little tip. This would the app more interactive and giving it a greater purpose than a guide. 

- Use this as inspiration to write a code that teaches beginners how to read the python traceback (The block of text that pops up when your code crashes) 
</details>

<img src="assets/Cursor%20Select.png" width="60" align="left">

<details>
<summary><strong><h3> 
HOW TO RUN IT
</strong></h3></summary>

(with python and streamlit installed)

I personally wrote the code in my notes app on my laptop... 
(Image/git of the whole code) 

Then wrote a line to run it in a seperate note using:
```bash
py -m streamlit run python_error_explainer.py
```

(Image) 
(Explain what each line means) 
- `py` - Use python to do something aka "hey python!"
- `-m` - Run this installed python program/Module
- `streamlit` - The module I want you to run
- `run` - Command in streamlit that tells streamlit to launch the app
- `python_error_explainer.py` - The app I want you to run is this file

In plain english:  ~~Hello World~~ Python Wake up and run this module you and I both know is installed on this laptop called Streamlit. And Streamlit launch this app in the file called python_error_explainer.py ... pretty please.

When saving the file I saved it with .bat, short for a batch file which types the command I wrote above for me.


There are other ways to do it but this one works best for me. Just note it is also sensitive to Indentation error and making sure the name matches the file name exactly.... another beginners error I might expand on later.

</details>

---

### BYE BYE

The charm of turning this idea into a web app is that you can not only fix your error in python but you can learn other skills
Streamlit is in python, you can use some html for formatting and more. It's like proof you don't need to be an expert to produce something meaningful. 

 Hope you find this useful! 

>[!NOTE]
>Dictonaries fustrated me but I'm happy I stuck with them.

![python-error-helper-pixel-art](assets/python%20logo.png) ![python-error-helper-pixel-art](assets/streamlit-logo.png)

Built with: Python & Streamlit

