+++
order = 1 #order of the project
date = "2022-12-09" #date creation
title = "LibDogecoin" #name of the project
aliases = ["LibDogecoin"] # name of the project
type = "projects" # projects
social_Type = "github" # types available: twitter, github, reddit, outher
social_User = "dogecoinfoundation"
social_URL = "https://github.com/dogecoinfoundation"
social_Image = "https://avatars.githubusercontent.com/u/6355206?s=200&v=4" # leave blank to not use any image
version = "v0.1.1"
description = "Libdogecoin will be a complete implementation of the Dogecoin Protocols, as a C library (and series of bindings to popular languages)"
[ author ]
  name = "Dogecoin Foundation"
+++
<h2 id="quick-start">What is Libdogecoin? </h2>
Libdogecoin will be a complete implementation of the Dogecoin Protocols, as a C library (and series of bindings to popular languages) which will allow anyone to build a Dogecoin compliant product, without needing to worry about the deeper, complicated specifics of the crypto functions.

Libdogecoin is here to make crypto development simple, clean, and fun!

This will be a pure library, providing a set of callable functions to implement in external projects, but not a ‘runnable’ node facility. Although we expect building a Dogecoin Node will be a useful test and early outcome, that will live in another repository.

It is intended that connecting the bits together into an engine be done at the level above, via the networking libraries of the host language.