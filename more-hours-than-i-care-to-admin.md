date: 2012-05-12T01:00:00-400
title: More Hours Than I Care To Admin

So I'm currently into my Nth hour writing my Sinatra based blog from this tutorial.  The tutorial was going so smoothly I thought I would take a break to deploy to production, and why not go all out and use Phusion Passenger as I'm already running an Apache server on my production hosts... errrgggggg....  Well I'll get into the details later but I had demo code in my site calling the Sinatra::Application method <code>run!</code> underneath the rackup config.  This was a major PITA.
