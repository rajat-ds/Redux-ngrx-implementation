# Aim

This project was basically developed to lear implementation of ngrx in Angular.

## Redux


It is an opensource javascript library for managing the state.

##Advantages 
Predictable: Redux helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test.
Centralized : Centralizing your application's state and logic enables powerful capabilities like undo/redo, state persistence, and much more.
Debuggable : The Redux DevTools make it easy to trace when, where, why, and how your application's state changed. Redux's architecture lets you log changes, use "time-travel debugging", and even send complete error reports to a server.
Flexible : Redux works with any UI layer, and has a large ecosystem of addons to fit your needs.

## ngrx/store

Store is RxJS powered global state management for Angular applications, inspired by Redux. Store is a controlled state container designed to help write performant, consistent applications on top of Angular.

## Key Concepts 
* Actions describe unique events that are dispatched from components and services.
* State changes are handled by pure functions called reducers that take the current state and the latest action to compute a new state.
* Selectors are pure functions used to select, derive and compose pieces of state.
* State is accessed with the Store, an observable of state and an observer of actions.
