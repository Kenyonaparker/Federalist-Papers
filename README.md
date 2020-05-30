# Federalist Papers 

Using sorting methods in Ruby programming language to read through the many pages of the Federalist Papers to organize a list.

## Introduction

Ruby programming Language is great for using one file to import a text document to sort and create a html output of the finished product.


## Technologies
Using Ruby in Linux it needs to start with this format in order for it to work properly 
```
# Reading the Federalist Papers 
#
# A Fed object contains one Federalist paper
# (Right now it has only the number)
#
class Fed
    attr_accessor :fedno
    attr_accessor :title
    attr_accessor :publication
    attr_accessor :author
    
    # Constructor
    def initialize
      @fedno=0
      @title=[]
      @publication=[]
      @author=[]
    end

    # Method to print data on one Fed object
    def prt
       puts "Federalist #@fedno"
       puts "Title: " + @title.join(" ")
       puts "Publication:  " + @publication.join(" ")
       puts "Author:  "  + @author.join(" ")
             
    end
end
```

## Launch
To run application you will need Ruby programming language, any browser, a text editor like Notepad++.
MobaXterm is good to us for Unix capabilities. MobaXterm brings all the essential Unix commands to Windows desktop, 
in a single portable exe file which works out of the box.
