slidenumbers: true

![right](pycon.png)

# from the first love to a serious relationship
## `pycon ukraine 2014`
### [@darkproger](http://twitter.com/darkproger)

---

![right](pycon.png)

# based on a true story

---

![fit](django.png)

---

# Python is awesome

---

![fit](django.png)

# zero to webapp in minutes

---

![fit](bboxdash.png)

---

![fit](bboxdash.png)

# complex webapps for embedded systems

---

![fit](bboxform.png)

---

![fit](bboxform.png)
# boring forms

---

![fit](bitfield.png)

---

![fit](bitfield.png)

# interactive hacking

---

![](http://directive.io/content/images/2014/Apr/gimble.png)

# other uses

* avoiding c++
* scientific computing, machine learning, etc
* desktop GUIs
* build tools
* ad-hoc automation, scripts

---

![](http://2.bp.blogspot.com/-JWWeiqkQ0qs/UY0_MjFQ0mI/AAAAAAAAADY/XtQa9fsN3sk/s1600/mustache_printables.jpg)
# [fit] movember

^ Most of us take shaving for granted
  - you can buy shavers with lots of blades
  - if you look at the history shaving was hard -- it was done with a knife and required a special person attached to it
  - shaving has been democratized

---

# [fit] Democratization

^ process of a good/service to get wider audience over time; quality goes down
  prevalent; widespread

###### thank you Erik Meijer (see "Wisdom of the cloud" on TEDx Delft, 2011)

---

![fit](http://cdn.alltheragefaces.com/img/faces/large/neutral-feel-like-a-sir-clean-l.png)
![fit](http://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Graduation_hat.svg/500px-Graduation_hat.svg.png)
![fit](http://th09.deviantart.net/fs71/PRE/f/2011/246/2/5/macbook_pro_vector_by_black__werewolf-d48pz1u.png)
# Education

---

![fit](http://cdn.alltheragefaces.com/img/faces/large/neutral-feel-like-a-sir-clean-l.png)
![fit](http://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Graduation_hat.svg/500px-Graduation_hat.svg.png)
![fit](http://th09.deviantart.net/fs71/PRE/f/2011/246/2/5/macbook_pro_vector_by_black__werewolf-d48pz1u.png)

^ education (noblemen :arrow_right: universities :arrow_right: remote/internet)

---

# food

## [fit] killing animals :arrow_right: growing :arrow_right: markets :arrow_right: supermarkets

---

### [fit] computing!

---

# [fit] abstraction
## [fit] ignoring _irrelevant_ details

^ important that you don't hold on to old traditions

---

![](http://www.afroautos.com/wp-content/uploads/2014/10/Chev-dash.jpg)

---

# old skills become impediment in the new world

* milkman :arrow_right: milk chain employee
* system/network/database admin :arrow_right: devops

^ will get back to devops soon

--- 

# programming

```python
a = 1
# ...
b = {'key': 1}
# ...
c = open('/System/Library/Kernels/kernel').read()
# ...
d = requests.get(url)
```

---

# 1950's era tools

* state
* destructive assignment
* side-effects
* sequential composition

---

![](http://imgs.xkcd.com/comics/flow_charts.png)

---

# 1950's era tools

```python
a = 1
# ...
b = {'key': 1}
# ...
c = open('/System/Library/Kernels/kernel').read()
# ...
d = requests.get(url)
```

---

![fit](latencies.png)

---

![fit](latencies.png)

# [Systems Performance: Enterprise and the Cloud](http://www.brendangregg.com/sysperfbook.html)
## (have i told you that book is awesome yet?)

---

![](http://dangreenblatt.com/blog/wp-content/uploads/2008/08/twitter-fail-whale.png)

^ the cloud

---

![](http://dangreenblatt.com/blog/wp-content/uploads/2008/08/twitter-fail-whale.png)

# [fit] distributed systems

---

# adopting a language to the new world

```python
@asyncio.coroutine
def test():
    yield from asyncio.async(create())
    yield from asyncio.async(write())
    yield from asyncio.async(close())
    yield from asyncio.sleep(2.0)
    loop.stop()
```

^ stolen from asyncio documentation

---


![right fit](http://www.reactionface.info/sites/default/files/images/1287666826226.png)
# [fit] python 3

---

![fill](journey.jpg)

---

![fit](themovie.png)

---

![fit](themovie.png)
# [fit] erlang

---

![fit](themovie.png)

# __paradigm shift__[^1]
# process per physical entity
# language + OS

[^1]: deserves another talk really
  
^ omg i've done this with zeromq so many times!

---

![](http://i4.mirror.co.uk/incoming/article1592688.ece/alternates/s2197/160757701.jpg)

---

![](http://i4.mirror.co.uk/incoming/article1592688.ece/alternates/s2197/160757701.jpg)
# `(>>=)`

---

![fit right](http://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Commutative_diagram_for_morphism.svg/2000px-Commutative_diagram_for_morphism.svg.png)

# category theory

---

![fit](http://www.quickmeme.com/img/c9/c94711e0f933eb488e0cb0baa9d3eff1888a27ead4fd6089fd37d8f7d8f45a97.jpg)

^ THE THREE MONAD LAWS
^ 
^ A monad may not injure a human being or, through inaction, allow a human being to come to harm.
^ A monad must obey the orders given to it by human beings, except where such orders would conflict with the First Law.
^ A monad must protect its own existence as long as such protection does not conflict with the First or Second Laws.
^ http://bodil.org/hipster/#/43

---

* Pattern matching `case x of Just y -> y`
* HOFs `unwords . map (++ ",") . words`
* Combinators `fix f = f (fix f)`

--- 

# Lazy evaluation
## STG-machine

---

# ADTs

```
data Tree a = Branch a (Tree a) (Tree a)
            | Leaf
            deriving (Functor)
```

---

* functors `<$>`
* semigroups `+`
* applicatives `<*>`
* monoids `0 +`
* monads `>>=`

---

# [fit] type checker!

---

![](http://www.marchoftherobots.com/wp-content/uploads/2014/05/Lego.jpg)

---

![](http://upload.wikimedia.org/wikipedia/commons/3/32/Lego_Color_Bricks.jpg)

---

![](http://upload.wikimedia.org/wikipedia/commons/3/32/Lego_Color_Bricks.jpg)
![](http://www.marchoftherobots.com/wp-content/uploads/2014/05/Lego.jpg)

---

![](http://img2.wikia.nocookie.net/__cb20120128201544/lego/images/0/08/10188_alt2.png)

---

![](http://www.merkur.su/manual/clas/clas_20.jpg)

---

![](http://www.babylessons.ru/wp-content/uploads/2010/10/163.jpg)

---

^ impendance mismatch, devops

---

# free monads
# free applicatives
# EDSL
# rich metaprogramming
# quasi quoting (php + sql + html + css on one page anyone?)

^ evaluation vs data
^ money / aws
^ template haskell / generics

---

# `haxl` slide

---

# operational stuff

* static binaries once in a while

---

# [fit] haskell and glue

---

# testing

* quickcheck
* types
* tdd doesn't go away

--- 

# community

---

# [fit] computer science
# [fit] as the first class citizen

---

> I don't use mathematics for the sake of using mathematics. The purpose behind structuring programs mathematically is to compose small bits of mathematical functionality, each of which is correct in isolation, to build larger mathematical structures which are still correct.

-- [haskellforall.com](http://www.haskellforall.com/2014/06/spreadsheet-like-programming-in-haskell.html?showComment=1402844512192#c4741783835572817187)

---

# take away

* `fn.py`

---

# [fit] kthxbai
