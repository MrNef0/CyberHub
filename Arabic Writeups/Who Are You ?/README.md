# Who Are You?

Only root can talk to me, no one else

nc 52.49.52.189 8888

Flag format is CYBERHUB{...}

# Write up
<br />

التلميح زودنا برقم آي بي وبورت وذكر أمر لأداة الـNCAT, لذا نجرب استخدام الأمر في لينكس

![source](1.JPG)

<br />

Now after we used NCAT on the IP from the hint, a message pops out saying "Who are you?" and waiting for an input

![php](2.JPG)

<br />

We can remember from the hint that "Only root can talk to me", so we enter root

![source](3.JPG)

<br />

Wait a few seconds ...

![flag](4.JPG)

<br />

Congratulations :)

<br />
<br />

```
**Flag** :  CYBERHUB {curi0sity_ki11s_ne7cat}
```
