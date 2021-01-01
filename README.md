"# flappy_bird_game-rxjs-ts"

Steps to run:

## npm start

# Observable

An Observable is a data stream that houses data that can be passed through different threads. In our demo app, we’ll be using an Observable to supply data to our different components.

# Observer

An Observer consumes the data supplied by an Observable. In our demo app, we’ll be using our setState Hook to consume data from our Observable.

# Subject

it acts as both Observable and Observer

# Subscription

In order for our Observer to consume data from our Observable, we’ll have to subscribe it to the Observable. In our demo app, we’ll be using the subscribe() method to subscribe our setState Observer to our Observable.

# A quick aside about Why RxJS

2019 has been the year of RxJS, blowing up across the web-dev community with events like rxjs.live and ng-conf. More and more developers are finding out that RxJS is awesome and it is totally worth climbing your way through the somewhat steep learning curve.

Angular devs have been using RxJS for a while now. A quick search will find vue-rx, ember-rx, and even Svelte can use RxJS Observables as stores by default. When you learn RxJS you are learning a highly portable skill that can be used across frameworks. The concepts of Rx can actually be used across languages and platforms.

RxJS is a mature, battle hardened library for dealing with events and data flow. It is definitely going to be valuable to familiarize yourself with how it works.

Extract the project into the folder of your preference.
Go to the project's directory using a terminal.
Run npm i -D parcel.
Now call npm run serve and go to http://localhost:1234 in your browser.
