===================================
Web2Py - VueJS Scaffold Application
===================================

This is a small example of integration between VueJS and Web2py.

It includes:

- vue.js_
- Axios_
- APIMaker_

**(*)**  This is based on this_ app from the official web2py_ repo
  
How it works
------------

- Clone this repo
- Run web2py shell

  *$python web2py.py -S vue-scaffold -M*

- In the shell populate the table

  *from gluon.contrib.populate import populate*

  *populate(db.doc, 100)*
  
- Then in your browser open

  *http://127.0.0.1:8000/vue-scaffold*

Testing Stuff
-------------

Adding for testing pourpuses upload forms, single and multiple with API

TODO
----
 
- model DONE
- filter form DONE
- results display table DONE
- button to show all records DONE
- add record DONE
- edit record DONE
- delete record DONE
- Simple upload DONE
- Multiple uploads DONE (it should need the multiple option enabled in input file tag, and count number of items in script before upload)


.. _this: https://github.com/web2py/scaffold
.. _vue.js: http://www.vuejs.org
.. _Axios: https://github.com/axios/axios
.. _APIMAker: http://experts4solutions.com/collection2/default/examples
.. _web2py: http://web2py.com 
