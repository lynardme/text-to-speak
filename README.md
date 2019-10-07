# text-to-speak

### Installation:
#### **Creating new environment in Anaconda**
	conda create --name text-speak-env python=3
	pip install pyttsx3
	
### Usage:
#### **Text Editor (sublime)**
```python3
import pyttsx3
engine = pyttsx3.init()
engine.say("I have never heard a more eloquent silence")
engine.runAndWait()

