# Personal Dashboards

This repository is a proposal for a nonfiction book about building simple personal analytics dashboards with commercial tracking hardware/software (e.g. activity trackers, wifi-enabled scales and body composition analyzers, etc.) IFTTT, and Google Data Studio.

## Table of Contents
1. [Introduction](#introduction)
2. [The Quantified Self Movement]( )
3. [Dashboard Concepts]( )
4. [Tracking Hardware]( )
  1. [Pedometers]( )
  2. [Heart Rate]( )
  5. [Exercise]( )
  3. [Weight and Body Composition]( )
  4. [Sleep]( )
  5. [Inbox Depth]( )
  6. [Twitter Engagement]( )
  7. [Personal Finance]( )
5. [If This Then That (IFTTT)]( )
6. [Google Data Studio]( )
  1. [Connecting to Google Sheets]( )
  2. [Connecting to Google Cloud SQL]( )
7. [Advanced Dashboard Concepts]( )
  1. [Multi-Foci Displays]( )
  2. [Geovisualization]( )
  3. [Calendar Heatmaps]( )
  3. [Setting and Tracking Goals]( )
8. [Displaying your Dashboard]( )
  1. [Lock Screen and Screensaver Dashboards]( )
  2. [Permanent Displays with Raspberry Pi]( )
9. [Additional Resources]( )

## Introduction

The past decades have brought a remarkable transformation in our ability to track and quantify our personal lives. Everyone around you is carrying a very advanced set of sensors at all times, including accelerometers, GPS, the ability to log and track activities and health data, and — most importantly — the ability to communicate all this data to the cloud, where it can be logged, analyzed, remixed, and presented back to us.

All of these technologies were once available only within the rarefied air of research laboratories and military circles, but each is now available to every teenager with a smartphone. The ARPAnet because the internet of Facebook and Snapchat. Accelerometers were needed to activate car air bags and the ensuing economies of scale drove their unit price down from hundreds of dollars to pennies. GPS was once cutting edge military satellite technology that is now used to find and swipe right on potential mates. The relentless trend has been for these technologies to start off as very costly curiosities, then expensive but powerful tools of the military and corporations, then affordable consumer tools, eventually becoming so cheap and ubiquitous that they're included in children's toys.

Dashboards have followed a similar trajectory. Consumers are intimately familiar with the literal dashboards in our cars, but the notion of dashboards as a project or mission specific analytics tool is not something in most people's daily lives. When we went to space, and then the moon, Americans watched the progress unfold in part through the lens of mission control's big wall board and rows and rows of consoles. In business, and in particular in the technology and startup world, product dashboards are now a norm. But just as many people once questioned why anyone would want a personal computer, the need for a personal dashboard is not obvious to everyone today.

The emergence of a small but growing community of "quantified self" enthusiasts has proven that there is a group of people interested and motivated to look at themselves and their lives through the lens of numbers, graphs, and trends. Industry has taken note of this market and has brought gadgets to market to track exercise, heart rate, weight, body composition, running and cycling cadence, etc. This has created a great backlog of personal analytics data which provides fertile ground for visualization to bloom in the form of dashboards.

Until recently, creating these dashboards was the domain of only the most time and expertise-rich software developers. They have created some amazing dashboards and won much deserved acclaim and attention by giving talks and presenting them, but the path they took was difficult; it is not one that any sufficiently curious and self-examining person could follow.

This has changed quite recently due to several factors. Tracking hardware is now sold next to the TVs and cameras in many stores. Many of these devices now connect directly to free data flow tools such as [_If This Then That_]() (IFTTT, pronounced "ift"). IFTTT logs data to free spreadsheet tools like [Google Sheets]( ), where data can easily be analyzed and transformed with templates, even by non-programmers. Finally [Google Data Studio]( ) allows you to "draw" an attractive and functional dashboard, and provides you with a web address which automatically updates. With this URL, a spare display, a Raspberry Pi, you can set up a permanent physical dashboard and watch your daily progress.

This book will provide you with the step-by-step instructions and tools you need to make your own personal dashboard. We'll provide advice about which hardware to buy, how to unbox and configure it, and how to set it up to send data all the way through your processing pipeline and display it on your personal dashboard. Each chapter is structured as a recipe which will result in a new visualization on your dashboard. All the ingredients are provided in form of configuration details, Google Sheets templates, and in the final chapter, Raspberry Pi disk images. When you complete the book, you will have both a working personal dashboard, and the general theory of operation necessary to extend it and add your own new statistics of interest.
