# Download-Instagram-Profile-Pic-using-Python
Download Profile Pic of Any Instagram User Account using Python

In this post we will learn how to Download Instagram Profile picture of any user using python programming language. For this you have to use a Python module named instaloader.
```python
pip install instaloader
```
Now write the below code to download profile pic from Instagram
```python
import instaloader

mod = instaloader.Instaloader()

a = input("Enter The Username --> ")

mod.download_profile(a,profile_pic_only=true)
```

All Done. Enjoy 🙂
