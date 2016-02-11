---
layout: post
title:  "Blog Post Two!"
date: 2016-2-11 9:17:24
categories: arrays and hashes
keywords: "array, hash, computer science"
categories: computer science
- welcome
tags:
- hash
- array

	An array is the simplest and most fundamental of data structures. Hash tables are a bit more complicated, and usually are not provided by the language but rather are coded by the developer or included from some library that provides an implementation. Both are a collection of memory cells that can store something (a number, a string, etc.). Arrays are generally fixed in size. Hash tables generally have no size limit (that is, you can store an unbounded number of things in a hash table). It is easy to find things in arrays by specifying its index. While for a hash, it is easy to find something by specifying the thing you want to find. For example, if I want to find the string “bobby oomen", I specify that and I get back the element in the hash that corresponds to “bobby oomen". Why would you want to get an element from a hash when you already know it? Simple: you want to know if it is stored in the hash, or “bobby ommen" is a key that provides you with access to more data.Now, let's say I need to find “bobby ommen" in an array. If you don’t know the index, then you have to start at the beginning of the array, and search each cell until you find it. Hash will always be much faster to look up. You could sort the array, to get faster lookup times, but that now makes insertion time slower, and the lookups will likely be slower than in a hash table for some suitably large size array. So, hash tables are much better when it comes to looking up things in a big collection of data when you want to find it fast, and often will be faster for insertion too.