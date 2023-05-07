Download Link: https://assignmentchef.com/product/solved-int301-lab-10-radial-basis-function-neural-networks
<br>
<span class="kksr-muted">Rate this product</span>

Radial Basis Function Neural Networks

The following exercise can be used to model an RBF network

<pre>    %Radial Basis Function Network    clear;close all;</pre>

<pre>    %Generate training data (input and target)    p = [0:0.25:4];    t = sin(p*pi);</pre>

<pre>    %Define and train RBF Network    net = newrb(p,t);    plot(p,t,'*r');hold;</pre>

<pre>    %Generate test data    p1 = [0:0.1:4];</pre>

<pre>    %Test network    y = sim(net,p1);</pre>

<pre>    plot(p1,y,'ob');    legend('Training','Test');    xlabel('input, p');    ylabel('target, t');</pre>

Part 1

Revise demo.m in Week 6 lab with RBF network, to demonstrate the capability of RBF network to model the XOR logic gate.

Part 2

Demonstrate the capability of an RBF to approximate the function f(t) = sin(t)*exp(-t/20); 0 &lt; t &lt; 50