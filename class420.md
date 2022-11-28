# class 19
## _Django models_
#
#### ****__Django models__**** when  we talk about models, we mean data bases. 

#### A model is the single, definitive source of information about your data. It contains the essential fields and behaviors of the data you’re storing. Generally, each model maps to a single database table.

#### The most important part of a model – and the only required part of a model – is the list of database fields it defines. **Fields** are specified by class attributes. Be careful not to choose field names that conflict with the models API like clean, save, or delete.

#### Field types:
* The column type, which tells the database what kind of data to store (e.g. INTEGER, VARCHAR, TEXT).

* The default HTML widget to use when rendering a form field 

* The minimal validation requirements, used in Django’s admin and in automatically-generated forms.