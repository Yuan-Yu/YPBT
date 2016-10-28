# Youtube Progress Bar Tagger 
[![Build Status](https://travis-ci.org/Yuan-Yu/YPBT.svg?branch=master)](https://travis-ci.org/Yuan-Yu/YPBT)

Youtube Progress Bar Tagger (YPBT) is a gem that tracks the comments following a youtube movie and captures the time points of popularity.

## Installation

If you are working on a project, add this to your Gemfile: `gem 'YPBT'`

For ad hoc installation from command line:

```$ gem install YPBT```

## Quick Start  
  Export your [Youtube api key](https://console.developers.google.com/apis/credentials)  
  
    export YOUTUBE_API_KEY='Your_Youtube_API_Key'
  Install essential gem  
  
    bundle install
  Then do a basic test for our module  
  
    rake spec
