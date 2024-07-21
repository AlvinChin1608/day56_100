# day56_100

# Speed up your web development with this quick trick

I wanted to share a nifty trick to boost your web development productivity. 🖥️✨

## Quick In-Browser Editing
In this example, I demonstrate how you can speed up web development by quickly editing your webpage right in your browser's developer tools. Here’s a step-by-step guide, along with a GIF demo to show how it works.

![](https://github.com/AlvinChin1608/day56_100/blob/main/gif/copy_B749F46C-9674-48D8-A2FE-7910BC1EFEAE-ezgif.com-video-to-gif-converter.gif)

## Step-by-Step Guide:
1. **Choose a Template:** Start by picking a sleek and modern template from HTML5 UP.

2. **Set Up a Local Server:** I'm using Flask as my local server to test the changes. If you haven't already, you can set up Flask with:
```python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)
```

3. __Enable In Browser Editing:__ Open the template in your browser. Then, in the browser console, type:

```python
document.body.contentEditable = true
```
4. __Edit On-the-Fly:__ You can now directly click and edit elements, delete sections you don't need, and make quick changes without diving into the code.

5. __Save Your Work:__ Once you're happy with the edits, save the page to your computer. Simply right-click and select "Save as..." to store the modified HTML.

6. __Copy Over the Edits:__ Replace the original template files with your newly edited version, and you're good to go!

