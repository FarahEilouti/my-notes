# class 23
## _Django Custom User_
#
#### ****__Django Custom User__**** When you have projects that require a different authentication that the built-in User model can’t provide, you have to create your own custom User model by extending from either AbstractUser or AbstractBaseUser Now, the question is which one should you extend from?

AbstractUser : Are you satisfied with the existing fields in the built-in User model but you want to use email as the primary unique identifier of your users or perhaps remove the username field? If yes, AbstractUser is the right option for you.
AbstractBaseUser : There are two things to consider whenever starting a new project :
User model focused on authentication, and another model like Profile that keeps app-related information of the user. Here you may use AbstractBaseUser if you have additional auth-related attributes that you want to include in your User model.
User model that stores all information (auth related or non-auth attributes) all in one. You may want to do this to avoid using additional database queries to retrieve related model. If you want to take this approach, AbstractBaseUser is the right option.
Note: If you’re starting a new project, it’s highly recommended to set up a custom user model, even if the default User model is sufficient for you. This model behaves identically to the default user model, but you’ll be able to customize it in the future if the need arises:
from django.contrib.auth.models import AbstractUser


class User(AbstractUser):
    pass
For the purpose of this article, we are going to use AbstractUser but the steps for AbstractBaseUser are also similar.