# Lab-5_202001095



IT314 - Software Engineering
Lab 5 - Static Analysis


Name: Isha Popat
ID:202001095







1)  https://github.com/qxresearch/qxresearch-event-1
![s1](https://user-images.githubusercontent.com/123543637/225288699-d3639e7d-df60-45a8-8844-2aea40ec83a4.png)
error: Duplicate module named "source-code"


→ duplicate file named modules were found

2) https://github.com/ashu1230/Alarm-clock.git

![s2](https://user-images.githubusercontent.com/123543637/225289253-d973afb7-d6eb-47bd-aa7a-6d4159da9adf.png)

Incompatible import of "Event" (imported name has type "Type[threading.Event]", local name has type "Type[tkinter.Event[Any]]") 

→here the import of ”event “ is not supported occurs when a function (on a given object), is called with a this not corresponding to the type expected by the function.




3)https://github.com/sukhmani1303/Practical-Harmonic-Ananlysis.git

![s3](https://user-images.githubusercontent.com/123543637/225289368-759cb8a8-4848-4c43-b1cf-51b2bdbf0a9a.png)

error: No overload variant matches argument types "int", "int"  [call-overload]

→ I think it may be translating the type int to a callable incorrectly, so it no longer matches Type


4)https://github.com/mananpatel06/Covid-19-Tracker.git

![s4](https://user-images.githubusercontent.com/123543637/225289462-b95a1c01-a72b-4d55-9d6c-24c48c557cd6.png)
![s5](https://user-images.githubusercontent.com/123543637/225289467-c0108f7c-cf9d-4442-94f5-93be4afc26ee.png)

error: Library stubs not installed for "requests"  [import]


→"Library stubs not installed" typically indicates that mypy, a static type checker for Python code, cannot find stub files for the libraries that your code is using




5)https://github.com/thevkrant/turtle_spirals.git




![s5](https://user-images.githubusercontent.com/123543637/225289487-dded3cfa-c7dc-444c-9508-a380c3e4ecbe.png)


error: Incompatible types in assignment (expression has type "float", variable has type "int")  [assignment]
Found 1 error in 1 file (checked 5 source files)


→here while assigning the type of the variable there is an error where the variable has type int but the expression has type float.



