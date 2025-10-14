Revisiting a question solved with SUVAT from last year. It is now possible solve it using WEP.
![[Pasted image 20251010140218.png]]
$$
\begin{gather*}
\text{70mph car}: \\ \\
E_{\text{start}} = E_{{end}} \\ 
KE = WF_{\text{braking}} \\ 
\frac{1}{2}m(70)^{2} = WF_{\text{braking}} = 2450m\\ \\
\text{100mph car}: \\ \\
E_{\text{start}} = E_{\text{end}} \\
KE_{\text{start}} = WF_{\text{braing}} + KE_{end} \\
\frac{1}{2}m(100)^{2} = 2450m + \frac{1}{2}mv^{2} =
2450\cancel{ m } + \frac{1}{2}\cancel{ m }v^{2} \\
\therefore v = 71.4ms ^{-1}
\end{gather*}
$$
Revisiting an A-Level mathematics connected particles problem. For such problems, much like the A-Level mechanics problems, it is possible to split the problem into the energy for the whole system and the separate particles. 

As well as that, for such questions, the velocity gained is equal if the pulley system is released from rest.

![[Pasted image 20251010144022.png]]
$$
\begin{gather*}
F = 0.15(4g\cos 30) \\ 
E_{s} = E_{e} \\ 
GPE_{Q} = GPE_{P} + WF + KE_{P} + KE_{Q} \\ \\
6g(3) = 4g(3\sin 30) + 3(0.15(4g\cos 30)) + \frac{1}{2}(4)v + \frac{1}{2}v^{2} \\ \\
v = 4.52ms ^{-1}
\end{gather*}
$$

# Power
Power is defined as the rate of doing work:
$$
\therefore P = \frac{dW}{dt} = \frac{d}{dt}(Fs)
$$
If the force remains constant, then the power can be written as:
$$
P=F\frac{ds}{dt} \therefore P=Fv
$$
Power is measured in Watts (W), IW = $1Js^{-1}$
![[Pasted image 20251012161231.png]]

## Worked Example 1
Consider a 100W motor lifting up a 100N weight at a constant velocity. How long will it take for the motor lift up the weight 100m?

Now although the resultant force of the system is 0. The individual forces of the system are still in action however they are in equilibrium. If there is a 100N force of weight downwards due to the weight. The motor must also exerting a 100N pulling force upwards on the weight to ensure the system is in equilibrium. 

![[Pasted image 20251012161329.png]]

It is beneficial identify the local forces relative to each object in the system and label them differently, e.g. denoting the resultant force of the system $F_{r}$ and denoting any other forces as $F$
$$
\begin{gather*}
F_{\text{motor}} = 100N \\ \\
P = Fv \implies 100=100v \implies v = 1ms^{-1} \\
\therefore \text{It will take 100s to lift 100m}
\end{gather*}
$$
## Worked Example 2
What is the acceleration of an 800kg car moving at 8$ms^{-1}$ with engine working at 18kW facing a constant total resistive force of 400N?
![[Pasted image 20251012163406.png]]

Again in such scenarios, it is beneficial to look at the global resutant force of the system and the local forces relative to each object in the system. Much like A level mechanics problems, it possible to look at the force on the car only and then use that to calculate the force in the system to calculate the acceleration:

$$
\begin{gather*}
\text{Car:} \\
P = Fv \\
18000 = F(8) \\
F = 2250N \\ \\
\text{Whole system:} \\
2250 - 400 = 800a \\
a = 2.31ms ^{-1}
\end{gather*}
$$

Now calculate the terminal (maximum) velocity of the car.

Always remember that the terminal velocity of an object occurs when it's acceleration is 0. When the acceleration is 0, the resultant force is also 0 and thus the system is in equilibrium. This means that any opposing forces are equal. This means it is also possible to use power equation:

$$
\therefore F = 400, v=\frac{P}{F} \implies v = \frac{18000}{400} = 45ms ^{-1} (101mph)
$$
## Worked example 3
The same example however the slope is inclined:
![[Pasted image 20251012163429.png]]
Calculate the power output of the engine, assuming the 600N force is constant:
Always remember that for constant velocity, the forces opposing each other are equal.
$$
\begin{gather*}
F = 600 + 900g\sin 10 \\ 
P = (600+900g\sin 10)12 = 25600W
\end{gather*}
$$

## Worked example 4
It is possible to have cases where the resultant force is dependant on $v$. This feels more realistic due to $F\propto v$.

A 1200kg car is driving up a slope inclined at 15$^\circ$  at constant speed $v$. The total non-gravatational resistive force is measured as 500 + 6v. The engine is working at 25kW. Find v
![[Pasted image 20251013080255.png]]
$$
\begin{gather*}
\text{Constant speed } \implies F=500+6v + 1200g\sin 15 \\ \\
\text{Force for car engine}: \\
P=Fv\\ 
25000 = (500+6v+1200g\sin 15)v \\ 
25000 = 500v + 6v^{2}+ 1200gv\sin 15 \\ 
v = -597.6ms ^{-1} \qquad v = 6.97 ms ^{ -1} \boxxed{}

\end{gather*}
$$