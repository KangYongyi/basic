# HW3  

<div align="right"><font size="4">2019732021 강용이</font></div>


---

### P3.1  

<a href="https://ibb.co/j5s7yMD"><img src="https://i.ibb.co/QctsPNM/275322627-d7893625-d197-49d7-abb3-43c42bb6b58d.png" alt="275322627-d7893625-d197-49d7-abb3-43c42bb6b58d" border="0"></a>


<a href="https://ibb.co/K2j0Z5t"><img src="https://i.ibb.co/Cb51dwj/Kakao-Talk-20241013-225745997-04.jpg" alt="Kakao-Talk-20241013-225745997-04" border="0"></a><br />

---

### P3.3

<a href="https://ibb.co/hgX6JHk"><img src="https://i.ibb.co/vcsF6mb/275322634-2ffb10e4-a4e2-4c72-b09c-98dc62a1da28.png" alt="275322634-2ffb10e4-a4e2-4c72-b09c-98dc62a1da28" border="0"></a>

<a href="https://ibb.co/tmHzndY"><img src="https://i.ibb.co/3rTvVJS/Kakao-Talk-20241013-225745997-03.jpg" alt="Kakao-Talk-20241013-225745997-03" border="0"></a><br />

---

### P3.5

<a href="https://ibb.co/Lnb2LXq"><img src="https://i.ibb.co/5BtfNgz/275322643-86fec3b2-836d-4d8e-bd3b-a38921e8e74a.png" alt="275322643-86fec3b2-836d-4d8e-bd3b-a38921e8e74a" border="0"></a>

<a href="https://ibb.co/Nx9S4qr"><img src="https://i.ibb.co/tBqXd6z/Kakao-Talk-20241013-225745997-02.jpg" alt="Kakao-Talk-20241013-225745997-02" border="0"></a><br />

---

### P3.12

<a href="https://ibb.co/2k3D2yg"><img src="https://i.ibb.co/d54d9rG/275322648-6ac88ad8-6114-4ff4-a3b2-e0a96971d5e3.png" alt="275322648-6ac88ad8-6114-4ff4-a3b2-e0a96971d5e3" border="0"></a>

<a href="https://ibb.co/s6KJXZM"><img src="https://i.ibb.co/cC6Xsj7/Kakao-Talk-20241013-225745997-01.jpg" alt="Kakao-Talk-20241013-225745997-01" border="0"></a>

매트랩 코드

```
clear;
clc;
A = [0, 1, 0;0, 0, 1;-48, -44, -12]

syms s t
Phi = inv(s*eye(3) - A)
PI = ilaplace(Phi)
```
실행 결과

<a href="https://imgbb.com/"><img src="https://i.ibb.co/xs5CzcL/3-12.jpg" alt="3-12" border="0"></a><br />


---

### P3.17

<a href="https://ibb.co/TkphwYk"><img src="https://i.ibb.co/FKN7hmK/275322651-2f8f62d6-1e0e-45ea-b332-1eeb22bcfa22.png" alt="275322651-2f8f62d6-1e0e-45ea-b332-1eeb22bcfa22" border="0"></a>

<a href="https://ibb.co/09gh38q"><img src="https://i.ibb.co/z2yGwjs/Kakao-Talk-20241013-225745997.jpg" alt="Kakao-Talk-20241013-225745997" border="0"></a>

매트랩 코드

```
clear;
clc;
A = [1, 1, -1;4, 3, 0;-2, 1, 10]
B = [0;0;4]
C = [1, 0, 0]

syms s t
Phi = inv(s*eye(3) - A)
G_s = C*Phi*B
```

실행 결과

<a href="https://imgbb.com/"><img src="https://i.ibb.co/QkXHdYv/3-17.jpg" alt="3-17" border="0"></a>
