# Django E-commerce

This is an e-commerce website built with Django.

The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. They can then enter their address and choose Stripe to handle the payment processing.

[![alt text](https://justdjango.s3-us-west-2.amazonaws.com/media/gifs/djecommerce.gif "Logo")](https://youtu.be/z4USlooVXG0)

---

## Running this project

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install pipenv with

```
pip install pipenv
```

or use one of the other methods mentioned on [https://pypi.org/project/pipenv/](https://pypi.org/project/pipenv/)

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
pipenv install
```

That will install packages from Pipfile. Next activate it with this command:

```
pipenv shell
```

Now you can run the project with this command

```
python manage.py runserver
```

**Note** you'll also need to rename `.env.template` with `.env` and to change some settings to make things work

---

## Useful Links

This project is bulding based on [series on YouTube](https://youtu.be/z4USlooVXG0) that teaches how to build an e-commerce website with Django.

You can support that project through GitHub Sponsors. On GitHub, [this repository](https://github.com/justdjango/django-ecommerce) shows a button where you can Sponsor the contributors.

If you're learning Django and want to take your next step to become a professional Django developer, consider signing up on [JustDjango](https://learn.justdjango.com).
