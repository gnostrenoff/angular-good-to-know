# angular-good-to-know
This repo lists important topics about angular 2

### 1 - Create your project using Angular CLI

### 2 - Create your first component

### 3 - How to make 2 components communicate ?

### 4 - What is an Observable

An Observable is like a Stream (in many languages) and allows to pass zero or more events where the callback is called for each event.

Often Observable is preferred over Promise because it provides the features of Promise and more. With Observable it doesn't matter if you want to handle 0, 1, or multiple events. You can utilize the same API in each case.

Observable also has the advantage over Promise to be cancelable. If the result of an HTTP request to a server or some other expensive async operation isn't needed anymore, the Subscription of an Observable allows to cancel the subscription, while a Promise will eventually call the success or failed callback even when you don't need the notification or the result it provides anymore.

Observable provides operators like map, forEach, reduce, ... similar to an array

There are also powerful operators like retry(), or replay(), ... that are often quite handy.

 -> source : https://stackoverflow.com/questions/37364973/angular-promise-vs-observable
 
 examples : http://embed.plnkr.co/CJNgwR8bhKv2qY1P8rGa

### 5 - AngularZones and Change Detection
https://www.joshmorony.com/understanding-zones-and-change-detection-in-ionic-2-angular-2/

### 6 - Create yout first HTTP request

### 7 - Create your first service

### 8 - How to make a pipe ?

### 9 - Create your first form

### 10 - Create yout second module

### 11 - Routing

### 12 - Project Architecture
