# HTML-Embedding-Issue
To demo how a HTML Injection works

Copy the following code:

```
<img src="https://invalid_url" onerror="alert('but most of all, samy is my hero')">
```
and paste that to one of the text boxes (that support to add a song).

Since the provided image is not existing, it displays an alert message!!

This means the form input text boxes are used to manipulate the code. So whever clicks on this playlist, this message is displayed.
