+++
order = 2 #order of the project
uri = "gigawallet" #name of the folder
date = "2022-12-09" #date creation
title = "GigaWallet" #name of the project
aliases = ["GigaWallet"] # name of the project
type = "gettingstarted" # getting-started
subtype = "introduction" # introduction, install, contents
version = "v0.0.1"
[ author ]
  name = "Dogecoin Foundation"
+++
The Dogecoin GigaWallet is a backend service which provides a convenient integration API for platforms such as online shops, exchanges, social media platforms etc, to transact Dogecoin on behalf of their users.

The purpose of the GigaWallet is to allow the rapid uptake of Dogecoin as a payment option, by taking the complexity and risk out of integrating Dogecoin payments.

<h2>DogeConnect: Payment Protocol</h2>

The DogeConnect JSON protocol for authorising Dogecoin transactions via interaction with a user's wallet on their device is a key part of the GigaWallet project.

The DogeConnect protocol make it possible for any wallet provider to act as an authorising agent for transactions initiated by platforms using GigaWallet (or other payment backend implementing the protocol.)