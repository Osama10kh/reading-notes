# local storage

web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request
- Cookies are limited to about 4 KB of data

## A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5

First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.
userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.

## INTRODUCING HTML5 STORAGE

Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.

## HTML5 Storage

it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site

## USING HTML5 STORAGE

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

## TRACKING CHANGES TO THE HTML5 STORAGE AREA

to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
The storage event is supported everywhere the localStorage object is supported,

## HTML5 STORAGE IN ACTION

with HTML5 Storage, we can save the progress locally, within the browser itself
