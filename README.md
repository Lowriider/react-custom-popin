
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Simple example code
![img_3.png](img_3.png)

### Available props

<ul>
<li>
isVisible: boolean
</li>
<li>
onClose: boolean
</li>
<li>
large: boolean | default: false
</li>
<li>title: string | default: null</li>
<li>leftButton: string | default: "Cancel"</li>
<li>leftButtonVisible: boolean | default: false</li>
<li>rightButton: string | default: "Save"</li>
<li>rightButtonVisible: boolean | default: true</li>
<li>onSubmit: function | default: null</li>
</ul>

### IMPORTANT

This package requires Tailwindcss put this following line in content(Array) inside tailwind.config.js file

``
    './node_modules/react-custom-popin-v1/dist/*.{js,jsx}'
``