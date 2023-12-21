# Text font

```
from IPython.display import HTML

# Define your text and desired font
text = "Hello, World!"
font_family = "Georgia, serif"  # You can change this to any font you like

# Create the HTML string with inline CSS to change the font
html_string = f'<p style="font-family: {font_family}; font-size: 20px;">{text}</p>'

# Display the HTML
display(HTML(html_string))
```
