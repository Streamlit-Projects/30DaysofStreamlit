# st.button <br><br/>

[st.button](https://docs.streamlit.io/library/api-reference/widgets/st.button) allows the display of button widget <br/>

### What we are building?

In this challenge we built a simple app that prints out alternative messages depending on whether the button was pressed or not.

- by default, the app prints 'Goodbye'
- if user clicks on the button, the app displays the alternative message 'Why hello there'


```python
if st.button('Say hello'):
     st.write('Why hello there')
else:
     st.write('Goodbye')
```

<br><br/>

### App

App code: [button_app.py]() <br/>



