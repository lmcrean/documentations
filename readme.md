# Coach Matrix <!-- omit in toc -->

Coach Matrix is an open-source CPD platform for educators to connect and share knowledge.

## Table of Contents <!-- omit in toc -->


- [1. Features](#1-features)
- [2. User Stories reviewed against UX Planes and Manual Testing](#2-user-stories-reviewed-against-ux-planes-and-manual-testing)
- [3. Automatic Testing](#3-automatic-testing)
- [4. Issues and Bugs](#4-issues-and-bugs)
- [5. Acknowledgement and credits](#5-acknowledgement-and-credits)

***
- [1. Features](#1-features)
  - [1.1. User Posts Questions ](#11-user-posts-questions-)
  - [1.2. Tags ](#12-tags-)
  - [1.2. User Posts Answers ](#12-user-posts-answers-)
  - [1.3. User Upvotes and Downvotes ](#13-user-upvotes-and-downvotes-)
  - [1.4. Toggle Sort content by highest vote vs newest post  ](#14-toggle-sort-content-by-highest-vote-vs-newest-post--)
  - [1.5. Toggles Views between Compact and Expanded](#15-toggles-views-between-compact-and-expanded)
  - [1.6. Convenient User Authentication with Google and Microsoft ](#16-convenient-user-authentication-with-google-and-microsoft-)
  - [1.7. Landing Page ](#17-landing-page-)
  - [1.8. Navbar ](#18-navbar-)
  - [1.9. Footer ](#19-footer-)
- [2. User Stories reviewed against UX Planes and Manual Testing](#2-user-stories-reviewed-against-ux-planes-and-manual-testing)
  - [2.1. Strategy plane](#21-strategy-plane)
  - [2.2. Scope plane](#22-scope-plane)
  - [2.3.  Skeleton plane](#23--skeleton-plane)
  - [2.4. Surface plane](#24-surface-plane)
- [3. Automatic Testing and Deployment](#3-automatic-testing-and-deployment)
  - [3.1. Browserstack testing](#31-browserstack-testing)
  - [3.2. Deployment](#32-deployment)
- [4. Issues and Bugs](#4-issues-and-bugs)
  - [4.1. Issue 1: "Cannot Access Django-Admin Panel on Port."](#41-issue-1-cannot-access-django-admin-panel-on-port)
    - [5. Expecting to be able to access django admin panel and add social accouunt](#5-expecting-to-be-able-to-access-django-admin-panel-and-add-social-accouunt)
    - [5.1. Error message:](#51-error-message)
    - [6. Currently trying to fix with this tutorial](#6-currently-trying-to-fix-with-this-tutorial)
    - [7. settings.py and url are likely problem areas](#7-settingspy-and-url-are-likely-problem-areas)
  - [7.1. Issue 2: "IntegrityError When Adding Social Application in Django: Null Value in Column ‘Provider\_id.’"](#71-issue-2-integrityerror-when-adding-social-application-in-django-null-value-in-column-provider_id)
  - [7.2. Issue 3: "Cannot Delete ‘Forgot Password?’ On Sign in Page. Seems Completely Unresponsive to Code."](#72-issue-3-cannot-delete-forgot-password-on-sign-in-page-seems-completely-unresponsive-to-code)
  - [7.3. Issue 4: "Cannot Access Django-Admin Panel on Port."](#73-issue-4-cannot-access-django-admin-panel-on-port)
  - [7.4. Issue 5: "Django NoReverseMatch Error for ‘questions’ View After Google OAuth Sign-In."](#74-issue-5-django-noreversematch-error-for-questions-view-after-google-oauth-sign-in)
  - [7.5. Issue 6: "Social Login Expects to Lead to Questions.Html via Django Urlpatterns, Instead Leads to Home Page."](#75-issue-6-social-login-expects-to-lead-to-questionshtml-via-django-urlpatterns-instead-leads-to-home-page)
  - [7.6. Issue 7: "Django QuestionForm in Forms.Py Not Creating Instance in Questions.Html."](#76-issue-7-django-questionform-in-formspy-not-creating-instance-in-questionshtml)
- [8. Acknowledgement and credits](#8-acknowledgement-and-credits)
  - [8.1. Coding Languages](#81-coding-languages)
  - [8.2. Frameworks, Libraries and Programs](#82-frameworks-libraries-and-programs)
    - [8.2.1. 4.2.1 Front-end modules](#821-421-front-end-modules)
    - [8.2.2. 4.2.1 Back-end modules](#822-421-back-end-modules)
  - [8.3. Deployment and IDE](#83-deployment-and-ide)
  - [8.4. UX Software](#84-ux-software)
  - [8.5. Resources](#85-resources)



# 1. Features

The following features were implemented, tested and debugged throughout the development process. Many of them are tightly interwoven e.g. Users Post Questions with Tags.

## 1.1. User Posts Questions <!-- omit in toc-->
Users can post questions, which can be edited and deleted. 

## 1.2. Tags <!-- omit in toc-->

Tags are used throughout the programme. Users can add tags to their questions. Users can also filter for questions by tag.

##  1.2. User Posts Answers <!-- omit in toc-->

Users can post answers in response to questions, which can be edited and deleted.

##  1.3. User Upvotes and Downvotes <!-- omit in toc-->

Users can upvote and downvote both questions and answers

##  1.4. Toggle Sort content by highest vote vs newest post  <!-- omit in toc-->

The user can toggle between sorting content by highest vote vs newest post. The default is highest vote. This applies to both questions and answers. Answers also provides a toggle to sort by oldest post, so they can get a sense of the narrative.

##  1.5. Toggles Views between Compact and Expanded

##  1.6. Convenient User Authentication with Google and Microsoft <!-- omit in toc-->

##  1.7. Landing Page <!-- omit in toc-->

The landing page provides a brief description of the site and a call to action to sign up. It also provides a link to the questions page. It features appealing animations and a video background.

##  1.8. Navbar <!-- omit in toc-->



##  1.9. Footer <!-- omit in toc-->



# 2. User Stories reviewed against UX Planes and Manual Testing


## 2.1. Strategy plane

The user stories are organised by EPICS. They can be summarised here:

https://docs.google.com/spreadsheets/d/1tii97g0Q4bVVvkrn_llrX8nOc_N2EyoOecOuMOEYFz0/edit?usp=sharing

%%%%%%%%%%%%%%%%%%% INSERT SCREENSHOT %%%%%%%%%%%%%%%%%%%

## 2.2. Scope plane
Based on the user stories above, the following features were prioritised which you can see in the [features section](1-features) above.

 2.3. Structure plane

## 2.3.  Skeleton plane
Figma was used to create the wireframes during the design process, prioritising a mobile-first approach. The wireframes can be found here:

https://www.figma.com/file/jXT4Bi1WXVwYG4daO3Yczi/Portfolio-Project-4?type=design&node-id=0%3A1&mode=design&t=0DTJelaO4PzBf99a-1

Codepen was used to test and debug code snippets in the front-end using bootstrap and css. The codepen collection can be found here:
https://codepen.io/collection/jbEjoo

## 2.4. Surface plane

The colour scheme was chosen to be bright and engaging, with a primary colour of dark turqoise.

Root vars were used to make the colour scheme consistent throughout the site with a more.

<details><summary><i>review</i></summary>

</details>

# 3. Automatic Testing and Deployment

## 3.1. Browserstack testing

## 3.2. Deployment

# 4. Issues and Bugs

All major issues and bugs were documented on StackOverflow, which turns out to be an invaluable learning strategy for debugging.

## 4.1. Issue 1: "Cannot Access Django-Admin Panel on Port." 

“Cannot Access Django-Admin Panel on Port.” Stack Overflow, https://stackoverflow.com/questions/77465837/cannot-access-django-admin-panel-on-port. Accessed 12 Nov. 2023.

<details><summary><i>issue</i></summary>

### 5. Expecting to be able to access django admin panel and add social accouunt

opening admin panel by adding standard `admin/` extension to local preview port URL. This is expected to lead to classic [django admin panel.](https://www.programink.com/static/img/django-admin-login.png)

**going to the admin url instead leads to an [error message](https://i.stack.imgur.com/z4v0U.png)**

the website is otherwise displaying fine.

*A simple google oath signin is currently being implemented.*

### 5.1. Error message:

```
DoesNotExist at /admin/login/
Site matching query does not exist.
Request Method:	GET
Request URL:	http://8000-lmcrean-project4-avaw7dd1zq8.ws-eu106.gitpod.io/admin/login/?next=/admin/
Django Version:	3.2.23
Exception Type:	DoesNotExist
Exception Value:	
Site matching query does not exist.
Exception Location:	/workspace/.pip-modules/lib/python3.9/site-packages/django/db/models/query.py, line 435, in get
Python Executable:	/home/gitpod/.pyenv/versions/3.9.17/bin/python3
Python Version:	3.9.17
Python Path:	
['/workspace/Project-4',
 '/home/gitpod/.pyenv/versions/3.9.17/lib/python39.zip',
 '/home/gitpod/.pyenv/versions/3.9.17/lib/python3.9',
 '/home/gitpod/.pyenv/versions/3.9.17/lib/python3.9/lib-dynload',
 '/workspace/.pip-modules/lib/python3.9/site-packages',
 '/home/gitpod/.pyenv/versions/3.9.17/lib/python3.9/site-packages']
Server time:	Sat, 11 Nov 2023 15:17:58 +0000
```

[traceback details in full](https://file.io/haymHM3ANkEI)

### 6. Currently trying to fix with this tutorial

“Set up Google Sign-in for Faster Django Login Experience Feat. Tech with Tim.” Akamai DevRel, YouTube Video, 12 Dec. 2022, https://youtu.be/yO6PP0vEOMc?feature=shared&t=1328. Accessed 11 Nov. 2023.

- have followed correctly with all working up to 22 minutes in
- migration was recently made after setting up urls, views and templates for google oauth as per the tutorial, there were no obvious issues with this
- before that django-admin panel seemed to be working fine


### 7. settings.py and url are likely problem areas


installed apps seems ok on [settings.py - can be viewed here in full](https://file.io/HDZjRjk17k3w)

this was recently implemented but is correct according to tutorial:
```
AUTHENTICATION_BACKENDS = (
    "django.contrib.auth.backends.ModelBackend",
    "allauth.account.auth_backends.AuthenticationBackend"
)
```


urlpatterns in urls.py
```
urlpatterns = [
    path('admin/', admin.site.urls),
    path("", include("blog.urls"), name="blog-urls"),
    path('summernote/', include('django_summernote.urls')),
    path("accounts/", include("allauth.urls")),
    path("", include("users.urls"))
]
```

</details>

<details><summary><i>solution</i></summary>

The error message "Site matching query does not exist," typically occurs in Django when the SITE_ID setting in settings.py refers to a Site object that does not exist in the database.

I managed to debug this with the Python Shell by checking existing site ID.

    from django.contrib.sites.models import Site
    existing_site = Site.objects.get(domain='http://127.0.0.1:8000')
    print(existing_site.id)

The returning statement revealed that the SITE_ID should be 2, not 1 as previously set.

This was fixed with an update to settings.py to match the correct site ID:

    SITE_ID = 2

[The django admin panel can now be accessed][1] without any further errors.


[1]: https://i.stack.imgur.com/GY9LK.png

</details>

## 7.1. Issue 2: "IntegrityError When Adding Social Application in Django: Null Value in Column ‘Provider_id.’" 
“IntegrityError When Adding Social Application in Django: Null Value in Column ‘Provider_id.’” Stack Overflow, https://stackoverflow.com/questions/77466342/integrityerror-when-adding-social-application-in-django-null-value-in-column-p. Accessed 12 Nov. 2023.

- <details><summary><i>issue</i></summary>

</details>

- <details><summary><i>solution</i></summary>

</details>

## 7.2. Issue 3: "Cannot Delete ‘Forgot Password?’ On Sign in Page. Seems Completely Unresponsive to Code." 
“Cannot Delete ‘Forgot Password?’ On Sign in Page. Seems Completely Unresponsive to Code.” Stack Overflow, https://stackoverflow.com/questions/77427112/cannot-delete-forgot-password-on-sign-in-page-seems-completely-unresponsive. Accessed 12 Nov. 2023.

- <details><summary><i>issue</i></summary>

</details>

- <details><summary><i>solution</i></summary>

</details>

## 7.3. Issue 4: "Cannot Access Django-Admin Panel on Port."
“Cannot Access Django-Admin Panel on Port.” Stack Overflow, https://stackoverflow.com/questions/77465837/cannot-access-django-admin-panel-on-port. Accessed 26 Nov. 2023.

- <details><summary><i>issue</i></summary>

</details>

- <details><summary><i>solution</i></summary>

</details>

## 7.4. Issue 5: "Django NoReverseMatch Error for ‘questions’ View After Google OAuth Sign-In."
“Django NoReverseMatch Error for ‘questions’ View After Google OAuth Sign-In.” Stack Overflow, https://stackoverflow.com/questions/77547799/django-noreversematch-error-for-questions-view-after-google-oauth-sign-in. Accessed 26 Nov. 2023.

- <details><summary><i>issue</i></summary>

</details>

- <details><summary><i>solution</i></summary>

</details>

## 7.5. Issue 6: "Social Login Expects to Lead to Questions.Html via Django Urlpatterns, Instead Leads to Home Page."
“Social Login Expects to Lead to Questions.Html via Django Urlpatterns, Instead Leads to Home Page.” Stack Overflow, https://stackoverflow.com/questions/77634816/social-login-expects-to-lead-to-questions-html-via-django-urlpatterns-instead-l. Accessed 10 Dec. 2023.

- <details><summary><i>issue</i></summary>

</details>

- <details><summary><i>solution</i></summary>

</details>

## 7.6. Issue 7: "Django QuestionForm in Forms.Py Not Creating Instance in Questions.Html."
“Django QuestionForm in Forms.Py Not Creating Instance in Questions.Html.” Stack Overflow, https://stackoverflow.com/questions/77704846/django-questionform-in-forms-py-not-creating-instance-in-questions-html. Accessed 25 Dec. 2023.

- <details><summary><i>issue</i></summary>

</details>

- <details><summary><i>solution</i></summary>

</details>

 # 8. Acknowledgement and credits



 ## 8.1. Coding Languages

- [HTML](https://en.wikipedia.org/wiki/HTML)
    - HTML is the standard markup language for documents designed to be displayed in a web browser.
- [CSS](https://en.wikipedia.org/wiki/CSS)
    - Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language such as HTML.
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
    - JavaScript, often abbreviated as JS.
- [Python](https://www.python.org/)
    - Python is an interpreted high-level general-purpose programming language.

 ## 8.2. Frameworks, Libraries and Programs

The following libraries were used to assist with the development of the site:

### 8.2.1. 4.2.1 Front-end modules

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
- [Font Awesome](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
- [JQuery](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive.
- 

### 8.2.2. 4.2.1 Back-end modules

- [asgiref](https://pypi.org/project/asgiref/)
    - ASGI is a standard for Python asynchronous web apps and servers to communicate with each other, and positioned as an asynchronous successor to WSGI.
- [cloudinary](https://cloudinary.com/)
    - Cloudinary is a cloud service that offers a solution to a web application's entire image management pipeline.
- [dj-database-url](https://pypi.org/project/dj-database-url/)
    - This simple Django utility allows you to utilize the 12factor inspired DATABASE_URL environment variable to configure your Django application.
- [dj3-cloudinary-storage](https://pypi.org/project/dj3-cloudinary-storage/)
    - A Django storage backend for Cloudinary.
- [Django](https://www.djangoproject.com/)
    - Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.
- [django-allauth](https://django-allauth.readthedocs.io/en/latest/)
    - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.
- [django-crispy-forms](https://django-crispy-forms.readthedocs.io/en/latest/)
    - django-crispy-forms provides you with a |crispy filter and {% crispy %} tag that will let you control the rendering behavior of your Django forms in a very elegant and DRY way.
- [django-summernote](https://django-summernote.readthedocs.io/en/latest/)
    - Summernote is a simple WYSIWYG editor.
- [gunicorn](https://gunicorn.org/)
    - Gunicorn 'Green Unicorn' is a Python WSGI HTTP Server for UNIX.
- [oauthlib](https://oauthlib.readthedocs.io/en/latest/)
- [psycopg2](https://pypi.org/project/psycopg2/)
    - Psycopg is the most popular PostgreSQL database adapter for the Python programming language.
- [PyJWT](https://pyjwt.readthedocs.io/en/stable/)
    - A Python library which allows you to encode and decode JSON Web Tokens (JWT).
- [python3-openid](https://pypi.org/project/python3-openid/)
    - This is a set of Python packages to support use of the OpenID decentralized identity system in your application.
- [pytz](https://pypi.org/project/pytz/)
    - pytz brings the Olson tz database into Python.
- [requests-oauthlib](https://pypi.org/project/requests-oauthlib/)
    - OAuthlib support for Python-Requests!
- [sqlparse](https://pypi.org/project/sqlparse/)
    - A non-validating SQL parser module for Python.
- [urllib3](https://pypi.org/project/urllib3/)
    - urllib3 is a powerful, sanity-friendly HTTP client for Python.



 ## 8.3. Deployment and IDE

- [Heroku](https://www.heroku.com/)
    - Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.
- [GitHub](https://www.github.com/)
    - GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
- [Git](https://git-scm.com/)
    - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
- [GitPod](https://www.gitpod.io/)
  - gitpod is an online IDE for GitHub that provides a complete dev environment with a single click.
- [Visual Studio Code](https://code.visualstudio.com/)
    - Visual Studio Code is a source-code editor made by Microsoft for Windows, Linux and macOS.
- [CodePen](https://codepen.io/)
    - CodePen is a social development environment for front-end designers and developers. It was used to test and debug code snippets.


 ## 8.4. UX Software

- [Figma](https://www.figma.com/)
    - Figma is a vector graphics editor and prototyping tool which is primarily web-based. This was used to create the wireframes during the design process.
- [Canva](https://www.canva.com/)
    - Canva is a graphic design platform, used to create social media graphics, presentations, posters, documents and other visual content.

 ## 8.5. Resources

- [StackOverflow](https://stackoverflow.com)
  - Stackoverflow was used to document the bugs
-

