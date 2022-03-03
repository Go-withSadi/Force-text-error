# Force-text-error
In this repository you can find the error solution to make 'force-text' error .


Description::::
Without wasting your time, Let’s start This Article to Solve This Error.

I am trying to import force_text from django But I am facing following error.
ImportError: cannot import name 'force_text' from 'django.utils.encoding'

NO.1) How To Solve ImportError: cannot import name 'force_text' from 'django.utils.encoding' Error ?

To Solve ImportError: cannot import name 'force_text' from 'django.utils.encoding' Error From Django 4 we dont have force_text You Just have to Use force_str Instead of force_text. Just Replace this line in your YOUR_VENV/lib/site-packages/graphene_django/utils/utils.py: from django.utils.encoding import force_text to from django.utils.encoding import force_str Now, Your error must be solved.

NO.2) ImportError: cannot import name 'force_text' from 'django.utils.encoding'

To Solve ImportError: cannot import name 'force_text' from 'django.utils.encoding' Error You Have to use django Less than or equal to version 3 Because of Django 4 we dont have force_text Now, Your error should be solved. 

