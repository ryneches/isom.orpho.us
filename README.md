# isom.orpho.us : a RESTful API for annotated citations

isom.orpho.us links two resources through a predicate, like so :

```
[A] reproduces [B]
[A] refutes [B]
[A] extends [B]
[A] contradicts [B]
[A] corroborates [B]
[A] is a part or component of [B]
[A] depends on [B]
```

isom.orpho.us also describes each resource, like so :

```
[article A] reproduces [article B]
[blog post A] refutes [article B]
[article A] extends [blog post B]
[tweet A] contradicts [blog post B]
[article A] corroborates [book chapter B]
[article A] is a part or component of [review B]
[editorial A] depends on [book chapter B]
```

Each annotation is contributed by a user, like so :

```
ryneches says [article A] reproduces [article B]
jaeisen says [blog post A] refutes [article B]
mtfacciotti says [article A] extends [blog post B]
adthaler says [tweet A] contradicts [blog post B]
amrobinson says [article A] corroborates [book chapter B]
mbeisen says [article A] is a part or component of [review B]
ztlewis says [editorial A] depends on [book chapter B]
```

More than one user can submit the same annotation. This can be used to
determine how accurate it is.

```
ryneches and jaeisen and adthaler say [article A] reproduces [article B]
jaeisen says [blog post A] refutes [article B]
mtfacciotti says [article A] extends [blog post B]
adthaler says [tweet A] contradicts [blog post B]
amrobinson says [article A] corroborates [book chapter B]
mbeisen and ztlewis say [article A] is a part or component of [review B]
ztlewis says [editorial A] depends on [book chapter B]
```


