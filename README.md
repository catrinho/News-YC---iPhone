News-YC---iPhone
================

The iPhone version of News/YC, a Hacker News reader and interactive iOS application. 

## About ##

News/YC is a front-page reader for Hacker News (http://news.ycombinator.com), a portal for interestingness regarding technology and building things. This app is free, and will forever remain free - and now, starting with version 2.0, is entirely open-sourced (please don't laugh at my code).

## The Code ##

The root ViewController, App Delegate, and HNSingleton are in the top-level directory, while every other class should be self-documented through the folders they are in (Webservice, Data Objects, Utilities, etc.).

** Webservice.{h,m} **

This class contains all web requests to the API, using a delegated system so ViewController can receive callbacks about the success or failure of each call - as well as the objects (posts/comments) returned.
